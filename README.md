# General Dev Tools.

A curated collection of development tools, libraries, services, and learning resources I use, like, or want to explore.

## Quick Index by Team

- **DBA** → [Databases](#databases), [Data Storage](#data-storage), [Catalogs & Lineage](#catalogs--lineage), [Secrets Management](#secrets-management)
- **Integrations** → [Ingestion (ETL/ELT)](#ingestion-etlelt), [APIs](#apis), [Webscraping](#webscraping), [Automation](#automation)
- **Analytics / Reporting** → [Visualization](#visualization), [Notebooks](#notebooks), [Statistics & Data Manipulation](#statistics--data-manipulation), [Geospatial & Enrichment](#geospatial--enrichment), [Machine Learning](#4-machine-learning)

---

## Ongoing Reading — Medium Lists

Curated reading lists I maintain on Medium:

- [AI / ML](https://medium.com/@hantsawilliams/list/aiml-related-b3bb02fe4ba3)
- [LLMs](https://medium.com/@hantsawilliams/list/llms-eb59cf5ccace)
- [Data Governance](https://medium.com/@hantsawilliams/list/data-governance-4b8035857ace)
- [Data Storage](https://medium.com/@hantsawilliams/list/data-storage-d884ff6c9017)
- [General Reading List](https://medium.com/@hantsawilliams/list/reading-list)

## Podcasts

Regular rotation — a mix of AI, security, and Python:

| Podcast | Cadence | Length | Focus |
| --- | --- | --- | --- |
| [The AI Daily Brief](https://podcasts.apple.com/us/podcast/the-ai-daily-brief-artificial-intelligence-news/id1680633614) | Daily | ~15 min | AI news |
| [NVIDIA AI Podcast](https://podcasts.apple.com/us/podcast/nvidia-ai-podcast/id1186480811) | Weekly | ~30 min | AI applications |
| [Cybersecurity Headlines](https://podcasts.apple.com/us/podcast/cybersecurity-headlines/id1527478719) | Daily | ~5 min | Security news |
| [Python Bytes](https://podcasts.apple.com/us/podcast/python-bytes/id1173690032) | Weekly | ~30 min | Python ecosystem |
| [Darknet Diaries](https://podcasts.apple.com/us/podcast/darknet-diaries/id1296350485) | Monthly | 1–2 hr | Hacking / attack stories |

---

## 1. Data Platform

### Databases
- **Modern**
  - [FaunaDB](https://medium.com/codesphere-cloud/is-faunadb-the-next-big-database-technology-4c5a67915d6e)
  - [SingleStore](https://www.singlestore.com)
  - [Apache Druid](https://druid.apache.org/) — competitor to SingleStore
  - [RethinkDB](https://rethinkdb.com) — live DB
  - Firebase
  - DynamoDB

### Data Storage
- **Decentralized cloud storage**
  - [Storj](https://www.storj.io/) — interesting for future encrypted messaging use cases
- **Data reading/writing (GCP, Azure, AWS)**
  - [Smart Open](https://github.com/RaRe-Technologies/smart_open)

### Ingestion (ETL/ELT)
- [Flatfile](https://flatfile.io/) — data onboarding platform
- [Fivetran](https://fivetran.com/) — cloud data integration
- Matillion — cloud data integration
- Apache Gobblin — open-source distributed data integration
- [Singer](https://www.singer.io/) — open-source standard for data movement scripts
- Meltano — open-source ELT for DataOps
- [Airbyte](https://airbyte.io/) — open-source data integration
- [Stitch](https://www.stitchdata.com/) — simple, extensible cloud ETL (Talend)
- Hevo — no-code data pipeline
- Apache Hop — open-source data integration
- Meroxa — real-time data ingestion
- Portable — cloud-hosted ELT
- Others: Talend, StreamSets, Alooma (Google), Xplenty, Striim, Panoply, Stambia, HVR

### Transformations
- [dbt](https://www.getdbt.com/) — transformations
- Apache Beam

### Data Lineage
- Pachyderm

### Data Management
- [Dataframe.ai](https://josephmoon.medium.com/dataframe-ai-a-comprehensive-data-context-management-tool-for-modern-data-teams-df47c8a1ce17)
- [WHALE](https://github.com/hyperqueryhq/whale) — search-like data tool

### Catalogs & Lineage
- [Comparison: DataHub / Atlas / Amundsen](https://medium.com/@gosin/finding-the-right-data-catalog-solution-a265a4b3c0c3)
- [Setting up a data discovery tool](https://medium.com/hipay-tech/setting-up-a-data-discovery-tool-why-and-which-solution-to-choose-5e03fcbed458)
- [OpenMetadata](https://blog.open-metadata.org/openmetadata-0-8-0-release-ca09bd2fbf54)

### Data Stack Reference
- [The modern data stack: open-source edition](https://www.datafold.com/blog/the-modern-data-stack-open-source-edition)
- [data-tools curated list](https://github.com/victorcouste/data-tools#ingestion)

---

## 2. Analytics & Reporting

### Visualization
- Superset
- Streamlit
  - [Streamlit with Sweetviz](https://discuss.streamlit.io/t/this-is-how-to-use-sweetviz-with-streamlit/10897)

### Notebooks
- Hex
- Deepnote <!-- TODO: add link/notes -->
- [Polynote (Netflix)](https://medium.com/dataseries/netflixs-polynote-is-a-new-open-source-framework-to-build-better-data-science-notebooks-4bdab6b8d0ae)
- [best-of-jupyter — collection](https://github.com/ml-tooling/best-of-jupyter#notebook-environments)

### Statistics & Data Manipulation
- **Summary statistics**
  - [Sidetable](https://levelup.gitconnected.com/sidetable-an-efficient-tool-to-summarize-pandas-dataframe-330958528a82) — pandas sidecar
- **Test selection**
  - [Statistical Tests Mind Map](http://www.sciences.ch/tmp/data_science_map/MindMap_Statistical_Tests_EN_2022_06_22_v0_2_r1230.html)
- **Dates**
  - [Ultimate Python dateparser with holidays & paydays](https://danilzherebtsov.medium.com/ultimate-python-dateparser-with-holidays-paydays-and-all-the-good-stuff-fffe270a236)
  - [verstack dateparser docs](https://verstack.readthedocs.io/en/latest/#dateparser)
- **Time series**
  - [Darts](https://unit8co.github.io/darts/index.html)
- **General**
  - [Pingouin](https://github.com/raphaelvallat/pingouin) — stats
  - [Repeated Measures (Rizopoulos)](https://www.drizopoulos.com/courses/EMC/CE08.pdf)
  - *Handbook of Parametric and Nonparametric Statistical Procedures*, 5th Edition
- **Data checks / schema / types**
  - [Pandera](https://pandera.readthedocs.io/en/stable/schema_inference.html)
  - [Pydantic](https://pydantic-docs.helpmanual.io/)
  - [mypy](https://mypy.readthedocs.io/en/stable/index.html)

### Geospatial & Enrichment
- **Libraries & toolkits**
  - [Kepler.gl](https://kepler.gl/) — geocoding / visualization
  - [MovingPandas](https://anitagraser.github.io/movingpandas/)
  - GeoPandas
  - geopy
  - [geog](https://pypi.org/project/geog/)
  - [python-geospatial — collection](https://github.com/giswqs/python-geospatial)
  - [22 Python libraries for geospatial data analysis](https://ishanjain-ai.medium.com/22-python-libraries-for-geospatial-data-analysis-f498959101bf)
  - [Clustering geospatial data — example](https://towardsdatascience.com/clustering-geospatial-data-f0584f0b04ec)
  - [Using SingleStore as a geospatial DB](https://medium.com/@VeryFatBoy/using-singlestore-as-a-geospatial-database-28ddf92684af)
- **Geographic enrichment by ZIP code**
  - [ZIP / ZCTA / judicial crosswalk for ACS](https://github.com/censusreporter/acs-aggregate/tree/master/crosswalks)
  - [ZIP-to-FIPS crosswalk (HUD)](https://www.huduser.gov/portal/datasets/usps_crosswalk.html) — select `ZIP-COUNT`
  - [Census Reporter](https://censusreporter.org/)
  - [Census API](https://github.com/censusreporter/census-api/blob/master/API.md) — demographics, economics, families, housing, social, health insurance, poverty/SNAP
- **Historical data**
  - [Visual Crossing — historical weather](https://www.visualcrossing.com/weather-api)
  - [Covid Act Now API](https://apidocs.covidactnow.org/#register) — historical COVID by state / FIP
- **Health & disparities**
  - [Neighborhood Atlas (UW)](https://www.neighborhoodatlas.medicine.wisc.edu/)
    - [My GitHub mirror for county health data](https://github.com/hantswilliams/countyhealthrankings)
  - [County Health Rankings](https://www.countyhealthrankings.org/)
- **Food environments**
  - [USDA Food Environment Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/go-to-the-atlas/)
- **Food retail stores**
  - [NY retail food stores example](https://catalog.data.gov/ne/dataset/retail-food-stores)
- **Regulated agencies**
  - [TTB](https://www.ttb.gov/) — wine, alcohol, fuel, guns, etc.
  - [DC liquor licenses](https://opendata.dc.gov/datasets/liquor-licenses/explore?location=38.902497%2C-77.008884%2C12.73)

---

## 3. Integrations & APIs

### APIs
- **API directories**
  - [Public API search](https://publicapis.sznm.dev/)
  - [listt.xyz](https://listt.xyz/)
  - [m3o.com](https://m3o.com/)
  - [Nylas](https://www.nylas.com/) — communication-focused
- **Payments**
  - [Stripe Connect](https://stripe.com/connect)
  - [Stripe Payment Links](https://stripe.com/payments/payment-links)
- **Security**
  - [TypingDNA](https://www.typingdna.com/) — typing biometric
- **Scheduling**
  - [OnSched](https://onsched.com/)
  - [Timekit](https://www.timekit.io/)
  - [Vyte](https://www.vyte.in/en/scheduling-api)
- **Speech / NLP**
  - [AssemblyAI](https://www.assemblyai.com/)
- **Food**
  - [Chomp](https://chompthis.com/api/)
- **News**
  - [NewsAPI](https://newsapi.org/)
- **Signatures**
  - [Concord](https://www.concordnow.com/)

### Webscraping
- [Stealth web scraping in Python](https://uxdesign.cc/stealth-web-scraping-in-python-avoid-blocking-like-a-ninja-8cb76db119ae)

### Automation
- Airflow
- See also: [Open-source Airflow alternatives](#open-source-alternatives)

### Deployment Helpers
- [ngrok](https://ngrok.com/) — quick localhost tunneling

### Diagrams
- [AWS diagram creator](https://alanblackmore.medium.com/aws-diagram-creator-8f596052952c)

---

## 4. Machine Learning

### Core Frameworks
- TensorFlow (Google)
- [PyTorch (Meta)](https://github.com/pytorch/pytorch)

### Cheat Sheets
- [Stanford CS229 cheatsheet](https://github.com/afshinea/stanford-cs-229-machine-learning)

### Labeling
- [Label Studio](https://labelstud.io)
- [DataNeuron](https://dataneuron.ai/product)

### Bias
- [Fairness in AI](https://github.com/dreji18/Fairness-in-AI)

### Drift / Monitoring
- [NannyML](https://www.nannyml.com/)

### Scary Use Cases
- [Awful AI](https://github.com/daviddao/awful-ai)

### Explainable
- [Shapash](https://github.com/MAIF/shapash)
- [Explainer Dashboard](https://github.com/oegedijk/explainerdashboard)
- [PiML Toolbox](https://github.com/SelfExplainML/PiML-Toolbox)

### Forecasting
- [Neuralforecast (Nixtla)](https://github.com/Nixtla/neuralforecast)

### Features
- [Feathr (LinkedIn)](https://github.com/linkedin/feathr)

### NLP
- spaCy
- [NER annotation example](https://github.com/vopani/waveton/tree/main/apps/data_apps/ner_annotation)
- **Language translation**
  - [FairSeq / NLLB (Meta)](https://github.com/facebookresearch/fairseq/tree/nllb)
- **Science journals**
  - [PubMed analysis (EBM-NLP)](https://github.com/bepnye/EBM-NLP)
  - [Articles → JSON (s2orc-doc2json)](https://github.com/allenai/s2orc-doc2json)
  - [Paper similarities (Stripnet)](https://github.com/stephenleo/stripnet)
  - [PDF parsing — tables/figures (Layout Parser)](https://github.com/Layout-Parser/layout-parser)
  - [Athena — NLP with graph + human search](https://github.com/boopalanjayaraman/athena) ([TigerGraph winner](https://www.tigergraph.com/graph-for-all/winners/third-place-most-impactful/))

### Computer Vision
- [DALL·E 2 (PyTorch)](https://github.com/lucidrains/DALLE2-pytorch) — text-to-image
- [Awesome Text-to-Image (free)](https://github.com/Yutong-Zhou-cv/Awesome-Text-to-Image)
- [AugLy (Meta)](https://github.com/facebookresearch/AugLy) — image augmentation
- [FaceSynthetics (Microsoft)](https://github.com/microsoft/FaceSynthetics) — synthetic faces
- [face_recognition](https://github.com/ageitgey/face_recognition)
- [Norfair](https://github.com/tryolabs/norfair) — real-time tracking
- [DeepSORT walkthrough](https://learnopencv.com/understanding-multiple-object-tracking-using-deepsort/)
- **Digital cloning**
  - [Identity Cloning Toolkit](https://github.com/titanlambda/identity-cloning-toolkit-ICT)
  - [Real-Time Voice Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning)
  - [Voice Cloning App](https://github.com/BenAAndrew/Voice-Cloning-App)
  - [Synthesia (paid)](https://www.synthesia.io/)

### Recommendation
- [Microsoft Recommenders — best practices](https://github.com/microsoft/recommenders)
- [Surprise](http://surpriselib.com/)
- **Collaborative**
  - [Walkthrough](https://sunjackson.github.io/2016/05/30/3cca3bba88363e21bbe6e536e4178018/)
  - [implicit](https://github.com/benfred/implicit)

### Session-Based Recommendations
- **Competitions**
  - [RecSys Challenges](https://recsys.acm.org/challenges/) — [2022](http://www.recsyschallenge.com/2022/)
- **Notebooks**
  - [NextItNet / GRU4Rec / Caser](https://github.com/microsoft/recommenders/blob/main/examples/00_quick_start/sequential_recsys_amazondataset.ipynb)
  - [SR-GNN](https://colab.research.google.com/drive/1XwQ0njqSZL8vbHJMnRRHlH4ar0kYYFVz?usp=sharing)
  - [SASRec](https://github.com/microsoft/recommenders/blob/main/examples/00_quick_start/sasrec_amazon.ipynb)
  - [Transformers4Rec tutorial](https://github.com/NVIDIA-Merlin/Transformers4Rec/blob/main/examples/tutorial/03-Session-based-recsys.ipynb)
- **Libraries**
  - [RecBole — sequential recsys](https://recbole.io/docs/user_guide/model_intro.html#sequential-recommendation)
  - [Spotlight](https://github.com/maciejkula/spotlight)
  - [Transformers4Rec](https://github.com/NVIDIA-Merlin/Transformers4Rec)
  - [Microsoft Recommenders](https://github.com/microsoft/recommenders)

### Pre-Made ML / AI
- [Hugging Face](https://huggingface.co/)
- [BlobCity Cloud](https://cloud.blobcity.com/code/explore)
- [Homemade ML](https://github.com/trekhleb/homemade-machine-learning)
- [Model Zoo](https://modelzoo.co/)
- Pretrained model collections: [Audio](https://github.com/balavenkatesh3322/audio-pretrained-model), [NLP](https://github.com/balavenkatesh3322/NLP-pretrained-model), [CV](https://github.com/balavenkatesh3322/CV-pretrained-model)

### AutoML
- MLJar
- [AutoGluon](https://auto.gluon.ai/stable/index.html)
- [TPOT](http://epistasislab.github.io/tpot/)
- [mljar-supervised](https://github.com/mljar/mljar-supervised)
- [AWS SageMaker Autopilot](https://aws.amazon.com/sagemaker/autopilot/)

### Awesome Lists & Notebooks
- [Awesome production ML](https://github.com/EthicalML/awesome-production-machine-learning)
- [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)
- [best-of-jupyter](https://github.com/ml-tooling/best-of-jupyter)
- [DL Colab notebooks — fakes / audio / video / pose](https://github.com/tugstugi/dl-colab-notebooks)
- **Starter notebooks**
  - [awesome-notebooks](https://github.com/jupyter-naas/awesome-notebooks) — GoogleSheets, Airtable, Sendgrid, Slack, etc.
  - [Homemade ML](https://github.com/trekhleb/homemade-machine-learning)
  - [LazyProgrammer ML examples](https://github.com/lazyprogrammer/machine_learning_examples)
  - [Susan Li — ML with Python](https://github.com/susanli2016/Machine-Learning-with-Python)
  - [TensorFlow examples](https://github.com/aymericdamien/TensorFlow-Examples)
  - [PyTorch examples](https://github.com/pytorch/examples)
  - [AWS SageMaker examples](https://github.com/aws/amazon-sagemaker-examples)

### Datasets for Testing
- [Data repositories for almost every project type](https://towardsdatascience.com/data-repositories-for-almost-every-type-of-data-science-project-7aa2f98128b)

---

## 5. Infrastructure & DevOps

### IaC
- **Pulumi**
  - [Pulumi — a true IaC paradigm](https://betterprogramming.pub/pulumi-a-true-infrastructure-as-code-paradigm-ac07c530e219)
- **Terraform tooling**
  - [Infracost](https://github.com/infracost/infracost)
  - [Brainboard](https://www.brainboard.co/) — auto-generate Terraform
  - Checkov — config error scanning
- **Ansible**
  - [ansible-for-devops](https://github.com/geerlingguy/ansible-for-devops)
  - [ansible-examples](https://github.com/ansible/ansible-examples)

### CaaS (Cloud-as-a-Service)
- My own (based on Pulumi + AWS) <!-- TODO: add link/notes -->
- [OpenStack](https://www.openstack.org/software/)
- [CloudStack (Apache)](https://cloudstack.apache.org/)
- [OpenNebula](https://opennebula.io/evaluate-opennebula/#try_now)

### Kubernetes
- Helm
- [Knative](https://knative.dev/docs/)
- Kubeflow
- [Crossplane](https://crossplane.io)

### AWS Specific / Labs
- [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler)
- [AWS Labs](https://github.com/awslabs)

### Monitoring
- [Uptime Kuma](https://github.com/louislam/uptime-kuma)

### Testing
- **Chaos engineering**
  - [Gremlin](https://www.gremlin.com/product/)

### Free Cloud Resources
- [Oracle — Always Free](https://www.oracle.com/cloud/free/#always-free)
- Vercel — has always-free tier
- Heroku

---

## 6. Security

### Cloud Checks
- Scout Suite

### Identity Management
- [StrongDM](https://www.strongdm.com)

### Secrets Management
- [Doppler](https://www.doppler.com)
- Vault

### Multi-Cloud Account Switching
- [Leapp](https://www.leapp.cloud/) — [GitHub](https://github.com/Noovolari/leapp)

### Pen Testing
- [Metasploit (Rapid7)](https://github.com/rapid7/metasploit-framework)
- [Metasploitable3 — vulnerable VM](https://github.com/rapid7/metasploitable3)
- [Onion Browser](https://github.com/OnionBrowser/OnionBrowser)
- **Python-based**
  - [awesome-pentest-tools-in-colab](https://github.com/brinhosa/awesome-pentest-tools-in-colab)
  - [python-pentest-tools](https://github.com/dloss/python-pentest-tools)
- **Non-Python**
  - [awesome-pentest (most starred)](https://github.com/enaqx/awesome-pentest)
  - [awesome-pentest-cheat-sheets](https://github.com/coreb1t/awesome-pentest-cheat-sheets)
  - [awesome-nodejs-pentest](https://github.com/jesusprubio/awesome-nodejs-pentest)
  - [Awesome Cloud PenTest](https://github.com/CyberSecurityUP/Awesome-Cloud-PenTest)
  - [Awesome PenTest Practice](https://github.com/CyberSecurityUP/Awesome-PenTest-Practice)

---

## 7. Application Development

### SaaS Starter Kits

**Next.js**
- Enterprise: [nextlessjs.com](https://nextlessjs.com/)
- Free (same author): [Next-js-Boilerplate](https://github.com/ixartz/Next-js-Boilerplate)

**Codebase Generators**
- [Divjoy](https://divjoy.com/) — pick backend / frontend / deployment

**Paid**
- [Reactapp](https://reactapp.dev/) — $19 lifetime
- [SaaS Rock](https://saasrock.com/) — $149 lifetime
- [Serverless.page](https://serverless.page/) — $199 lifetime
- [Bedrock](https://bedrock.mxstbr.com/) — $396 per project
- [Nextless](https://nextlessjs.com/) — $699 per project
- [Rocketapp](https://rocketapp.me/)
- [Gravity](https://usegravity.app/) — [docs](https://docs.usegravity.app/)
- [ShipSaaS](https://shipsaas.com/)

**Free**
- [async-labs/saas](https://github.com/async-labs/saas)
- [SAAS Starter Kit Pro](https://github.com/Saas-Starter-Kit/SAAS-Starter-Kit-Pro)
- [Nextacular](https://nextacular.co/) — [GitHub](https://github.com/nextacular/nextacular)

**My evaluation notes (Free options)**
- [Nextacular](https://nextacular.co/)
  - Billing: Stripe
  - Documentation: limited / WIP — [docs](https://docs.nextacular.co/)
  - Deployment: Vercel (auto SSL)
  - Databases: relational only (SQL / PostgreSQL / Aurora)
  - Pros: multi-domain; relational DB; teams + workspaces; Stripe; Tailwind; email handling
- [SaaS Starter Kit](https://www.saasstarterkit.com/)
  - Billing: Stripe
  - Documentation: good / mostly fleshed out — [docs](https://docs.saasstarterkit.com/docs/intro/welcome/)
  - Deployment: on your own
  - Databases: relational (Postgres) + non-relational (MongoDB)
  - Pros: ML example built in; onboarding; Docker; Stripe; AWS APIs

### Low Code / No Code
- **Backend**
  - Supabase
  - [Parse](https://parseplatform.org/)
  - [Appwrite](https://appwrite.io/)
  - [Nhost](https://nhost.io)
  - Hasura
  - [PocketBase](https://github.com/pocketbase/pocketbase)
- **Frontend**
  - AppGyver

### Frontend Multi-Deployment
- [Flutter](https://flutter.dev/)
- [FlutterFlow](https://flutterflow.io/)

### Frontend Styles
- **Fonts / styles**
  - [Why you should use a developer font](https://medium.com/@anthonyjdella/why-you-should-use-a-developer-font-b19d5269d767)
- **UX examples**
  - [Really Good UX](https://www.reallygoodux.io)

### Authorization
- [Authorizer](https://medium.com/@SamaniLakhan/introducing-authorizer-9b89edb810fd)

### Documentation Tools
- [Docusaurus](https://docusaurus.io)
- [Docz](https://www.docz.site)
- **API documentation**
  - [readme.com](https://docs.readme.com/)
  - [ReDoc / Redocly](https://redocly.com/) — [GitHub](https://github.com/Redocly/redoc)

### Search Tools
- Meilisearch
- [Typesense](https://typesense.org/)
- [Deephaven](https://deephaven.io)
- [Elasticsearch overview](https://diawahad.medium.com/elasticsearch-the-open-source-distributed-restful-json-based-search-engine-ready-for-the-big-640430fd655b)

### Misc Utilities
- **UUIDs**
  - [NanoID — URL-friendly unique identifiers](https://javascript.plainenglish.io/introducing-a-url-friendly-unique-identifier-nanoid-fbf4d2162322)
- **Linux cheatsheets**
  - [xmind cheatsheet](https://www.xmind.net/m/WwtB/)

### Open Source Alternatives
- **Airflow**
  - [NocoDB](https://nocodb.com)
  - [Top low/no-code databases](https://medium.com/swlh/top-3-low-and-no-code-databases-for-creative-entrepreneurs-b10f069c36b3)
- **Calendly**
  - [Cal.com](https://cal.com)

---

## 8. Training & General Ed

### Resources
- **Blogs**
  - [Chubby Developer](https://www.chubbydeveloper.com/)
  - Medium
- **Podcasts** <!-- TODO: add podcast recommendations -->

### Architecture & System Design
- [ByteByteGo](https://bytebytego.com/) — system design archive <!-- TODO: previously linked a LinkedIn PDF that's expired — replace with current source -->
- [Software architecture patterns (5 min read)](https://orkhanscience.medium.com/software-architecture-patterns-5-mins-read-e9e3c8eb47d2)
- [SSH tunneling explained](https://goteleport.com/blog/ssh-tunneling-explained/)
- [Stanford ML systems (CS329S)](https://stanford-cs329s.github.io/syllabus.html)

### ML Learning
- [Intro to ML with scikit-learn (Data School)](https://courses.dataschool.io/introduction-to-machine-learning-with-scikit-learn)
- [Visual intro to ML (R2D3)](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [Fun ML example — diapers and beer](https://medium.com/mlearning-ai/if-i-buy-a-diaper-i-will-surely-pick-up-a-beer-e692895a0c65)
- [Non-technical guide to SHAP / Explainable AI](https://www.aidancooper.co.uk/a-non-technical-guide-to-interpreting-shap-analyses/)
- [ML cheatsheet](https://github.com/soulmachine/machine-learning-cheat-sheet)
- [Approaching (Almost) Any ML Problem — Kaggle](https://github.com/abhishekkrthakur/approachingalmost)
- [MIT 15.003 — Data Science Tools](https://github.com/shervinea/mit-15-003-data-science-tools)
- [Interpretable ML book](https://christophm.github.io/interpretable-ml-book/index.html)
- [Resource of resources](https://www.linkedin.com/posts/vipulppatel_ultimate-guide-to-ai-data-science-machine-activity-6860243081434828800--w_7)
- [Kirill Eremenko (Udemy)](https://www.udemy.com/user/kirilleremenko/)

### SQL Training
- [SQL Fiddle](http://sqlfiddle.com/) — playground for queries
- [SQL Bolt](https://sqlbolt.com/) — interactive tutorial for beginners
- [Select Star SQL](https://selectstarsql.com/) — interactive tutorial
- [SQL Murder Mystery](https://lnkd.in/en3-VnT9) — intermediate/advanced <!-- TODO: replace lnkd.in shortlink with canonical URL -->
- [SQL Indexing for Devs](https://lnkd.in/egBCqJPa) <!-- TODO: replace lnkd.in shortlink -->
- [SQL Zoo](https://lnkd.in/eeGAxE7q) <!-- TODO: replace lnkd.in shortlink -->
- [SQL Tutorial for Data Analysis](https://lnkd.in/eUq7VvMp) <!-- TODO: replace lnkd.in shortlink -->
- **Other**
  - [Databases & SQL for DS (IBM, Coursera)](https://www.coursera.org/learn/sql-data-science)
  - [Learn SQL Basics for DS (Coursera)](https://www.coursera.org/specializations/learn-sql-basics-data-science)
  - *SQL Cookbook* — O'Reilly
  - *SQL 57 Practice Problems* — Sylvia Vasilik
  - *SQL for Data Analytics* — Packt

### Python Training
- **Official / standard**
  - [Official Python tutorial](https://bugs.python.org/file47781/Tutorial_EDIT.pdf)
  - [Pandas Tutor](https://pandastutor.com/index.html)
  - [milaan9 — Jupyter learning notebooks](https://github.com/milaan9?tab=repositories) — `02_python_datatypes`, `04_python_dictionaries`
- **Stanford**
  - [Variables (CS106A)](https://web.stanford.edu/class/archive/cs/cs106a/cs106a.1206/lectures/4-Variables/4-Variables.pdf)
  - [Python review (CS224N)](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/readings/python-review.pdf)
  - [Stanford Python lectures](https://stanfordpython.com/#/lectures)
  - [Lecture 2 — full](https://stanfordpython.com/lecture/lecture-2-full.pdf)
  - [Cloud computing intro (CS349D)](https://web.stanford.edu/class/cs349d/docs/L01_overview.pdf)
- **Harvard**
  - [Python intro PDF](http://tdc-www.harvard.edu/Python.pdf)
- **UCSF**
  - [Data Science programming](https://www.library.ucsf.edu/ask-an-expert/data-science/programming/)
  - [Python novice inflammation](https://swcarpentry.github.io/python-novice-inflammation/)
- **ECU**
  - [Python intro PDF](https://ofe.ecu.edu/wp-content/pv-uploads/sites/277/2021/05/Python_intro_2021OFE.pdf)
- **Duke**
  - [Python tutorial PDF](https://courses.cs.duke.edu/compsci260/fall14/resources/python.tutorial.1.2014.pdf)
- **Emertxe**
  - [Slideshare presentations](https://www.slideshare.net/EmertxeSlides/presentations/5)
  - [Python data types](https://www.slideshare.net/EmertxeSlides/python-data-types)
- **Bootcamps & books**
  - [Powerful Python bootcamp](https://powerfulpython.com/bootcamp/)
  - [2022 Complete Python Bootcamp (Udemy)](https://www.udemy.com/course/complete-python-bootcamp)
  - [Complete Python Developer (Udemy)](https://www.udemy.com/course/complete-python-developer-zero-to-mastery)
  - *Python Crash Course* (2nd ed.) — Eric Matthews
  - *Python Cookbook* — O'Reilly
  - *Elements of Programming Interviews in Python* — Adnan & Amit

### Statistics Training
- [Intro to Statistics (Udacity)](https://www.udacity.com/course/intro-to-statistics--st101)
- [Intro to Inferential Statistics (Udacity)](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [Statistics & Probability (Khan Academy)](https://www.khanacademy.org/math/statistics-probability)
- *Statistics in Plain English* — Timothy C. Urdan
- *Head First Statistics* — Dawn Griffiths
- *ISLR* (Introduction to Statistical Learning)
- *ESLR* (Elements of Statistical Learning)
- [Ashington — Medium blog](https://ashington.medium.com/)
