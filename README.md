# General-Dev-Tools
- this is a repo that contains general development tools that i use, like, or want to explore
- currently has two sections: 
    1. general resources 
    2. training and general ed 

## General Resources 

- Geocoding / geographical 
    - Keplr: dd for for geocoding: https://kepler.gl/ 
    - Pandas Moving -> https://anitagraser.github.io/movingpandas/ 
    - GeoPandas 
    - geopy
    - geog (https://pypi.org/project/geog/) 
    - Collection of python geospatial _> 
        - https://github.com/giswqs/python-geospatial 
        - https://ishanjain-ai.medium.com/22-python-libraries-for-geospatial-data-analysis-f498959101bf?source=userActivityShare-4726d4325967-1629049273 
        - Analysis example -> https://towardsdatascience.com/clustering-geospatial-data-f0584f0b04ec 
    - Article about using SingleStore https://medium.com/@VeryFatBoy/using-singlestore-as-a-geospatial-database-28ddf92684af 
    - Enrichment of geographic data: 
        - General data by zipcode 
            - zipcode / zcta / judicial crosswalk for ACS data: https://github.com/censusreporter/acs-aggregate/tree/master/crosswalks 
            - zipcode to FIPS crosswalk: https://www.huduser.gov/portal/datasets/usps_crosswalk.html (select `ZIP-COUNT` in dropdown) 
            - https://censusreporter.org/ 
            - https://github.com/censusreporter/census-api/blob/master/API.md 
                - Demographics
                - Economics
                - Families
                - Housing
                - Social
                - Health insurance 
                - Poverty (food stamps / SNAP) 
        - Historical
            - Weather 
                - Historical weather data -> https://www.visualcrossing.com/weather-api 
            - COVID 
                - https://apidocs.covidactnow.org/#register // historical covid with state or FIP code 
        - Health + Disparities ->
            - https://www.neighborhoodatlas.medicine.wisc.edu/ 
                - Created my own github repo for easy access to data files: https://github.com/hantswilliams/countyhealthrankings
            - https://www.countyhealthrankings.org/ 
        - Food Environments (USDA) 
            - https://www.ers.usda.gov/data-products/food-environment-atlas/go-to-the-atlas/ 
        - Food Retail Stores 
            - Example NY -> https://catalog.data.gov/ne/dataset/retail-food-stores 
	- Regulated Angencies 
	    - https://www.ttb.gov/ (wine, alcohol, fuel, guns, etc...) 
	    - Examples: 
	    	- Washington DC liquer -> https://opendata.dc.gov/datasets/liquor-licenses/explore?location=38.902497%2C-77.008884%2C12.73 
- Data Storage 
    - De-centralized cloud storage 
        - https://www.storj.io/ 
            - Very cool - I would want to do this for encrypting messages in future 
    - Data reading/writing made easy (GCP, Azure, AWS -> ) 
    	- SMart open - https://github.com/RaRe-Technologies/smart_open 
- AWS specific  / labs 
    - Data Wrangler - https://github.com/awslabs/aws-data-wrangler 
    - Labs-  https://github.com/awslabs 
- Deployement 
    - Quick deployment of localhost test -> https://ngrok.com/ 
- Diagrams:
    - AWS diagram creator https://alanblackmore.medium.com/aws-diagram-creator-8f596052952c 
- Data 
    - Onboarding and Ingestion (ETL/ELT)  
        - Flatfile Data Onboarding platform // https://flatfile.io/
        - Fivetran Cloud data integration platform // https://fivetran.com/
        - Matillion Cloud data integration platform 
        - Apache Gobblin Open Source distributed data integration framework
        - Singer "Open Source standard for writing scripts that move data" // https://www.singer.io/
        - Meltano Open Source ELT for the DataOps
        - Airbyte Open Source data integration platform // https://airbyte.io/
        - Stitch Simple, extensible Cloud ETL platform (Talend) // https://www.stitchdata.com/
        - Hevo No-code data pipeline as a service
        - Apache Hop Open Source data integration platform project
        - Meroxa Real-time data ingestion infrastructure
        - Portable Cloud Hosted ELT Platform
        - Talend, StreamSets, Alooma (Google), Xplenty, Striim, Panoply, Stambia, HVR
    - Transformations
    	- dbt -> transformations / https://www.getdbt.com/ 
	- apache beam 
    - Data Lineage 
    	- Pachyderm - Pachyderm 
    - Data management 
    	- Dataframe.ai - https://josephmoon.medium.com/dataframe-ai-a-comprehensive-data-context-management-tool-for-modern-data-teams-df47c8a1ce17 (dataframe.ai) 
        - Have also built a search-like tool called WHALE -> https://github.com/hyperqueryhq/whale 
    - Data Catalogs 
        - Good comparison - - data hub / atlas / amunddsen -> https://medium.com/@gosin/finding-the-right-data-catalog-solution-a265a4b3c0c3 
        - https://medium.com/hipay-tech/setting-up-a-data-discovery-tool-why-and-which-solution-to-choose-5e03fcbed458 
        - Open Meta Data (https://blog.open-metadata.org/openmetadata-0-8-0-release-ca09bd2fbf54) 
- APIs 
    - Multiple/APIs services (get multiple) 
        - Public API search (new): https://publicapis.sznm.dev/ 
        - https://listt.xyz/
    	- https://m3o.com/ 
    	- Communication focused: https://www.nylas.com/ 
    - Payments 
    	- Stripe Connect - https://stripe.com/connect 
    	- Stripe Payment Link - https://stripe.com/payments/payment-links 
    - Security 
    	- Typing biometric - https://www.typingdna.com/ 
    - Scheduling 
    	- https://onsched.com/ 
    	- https://www.timekit.io/ 
    	- https://www.vyte.in/en/scheduling-api 
    - Speech/NLP 
    	- https://www.assemblyai.com/
    - Food 
    	- https://chompthis.com/api/
    - News 
    	- https://newsapi.org/ 
    - Signatures 
    	- https://www.concordnow.com/ 
- Frontend 
    - Multi-deployment 
    	- flutter: https://flutter.dev/ 
        - flutterflow - https://flutterflow.io/ 
- Authorization 
    - Authorizer - https://medium.com/@SamaniLakhan/introducing-authorizer-9b89edb810fd 
- Automation
    - Airflow 
- Notebook tools 
    - Hex // https://github.com/louislam/uptime-kuma 
    - Deepnote // 
    - PolyNote - https://medium.com/dataseries/netflixs-polynote-is-a-new-open-source-framework-to-build-better-data-science-notebooks-4bdab6b8d0ae 
    - Resources / collections: 
        - https://github.com/ml-tooling/best-of-jupyter#notebook-environments 
- Statistics and Data Manipulation
    - Summary Statistics - Python Sidecar - https://levelup.gitconnected.com/sidetable-an-efficient-tool-to-summarize-pandas-dataframe-330958528a82 
    - Dates 
        - Holidays / etc… https://danilzherebtsov.medium.com/ultimate-python-dateparser-with-holidays-paydays-and-all-the-good-stuff-fffe270a236 
            - https://verstack.readthedocs.io/en/latest/#dateparser 
    - Timeseries
        - https://unit8co.github.io/darts/index.html / Darts 
    - Pinguin - stats - https://github.com/raphaelvallat/pingouin 
- Linux 
    - Command cheetsheets
    	- xmind: https://www.xmind.net/m/WwtB/
- Visualization 
    - Superset 
    - Streamlit 
        - Streamlit with Sweetviz - https://discuss.streamlit.io/t/this-is-how-to-use-sweetviz-with-streamlit/10897 
- SaaS starter kits 
    - Next JS 
        - Enterprise: https://nextlessjs.com/
	- Free (same author): https://github.com/ixartz/Next-js-Boilerplate 
    - Codebase generator (you get to choose backend, frontend framework, deployemnt, etc...) 
        - https://divjoy.com/ 
    - Other paid:
        - https://saasrock.com/ 
        - https://serverless.page/
        - https://bedrock.mxstbr.com/
        - https://rocketapp.me/
        - https://reactapp.dev/
        - https://usegravity.app/
        - https://docs.usegravity.app/
        - https://shipsaas.com/
    - Free
        - https://github.com/async-labs/saas 
        - https://github.com/Saas-Starter-Kit/SAAS-Starter-Kit-Pro
        - https://nextacular.co/ (https://github.com/nextacular/nextacular)  
    - Hants Ordering: 
        - Free: 
            - https://nextacular.co/
                - Billing: Stripe 
                - Documentation: Limited // work in progress // https://docs.nextacular.co/
                - Deployment: vercel (auto SSL) 
                - Databases: only relational (SQL/PostgreSQL/Aurora) 
                - Pros: multi-domain; DB -> relational; teams + workspaces; strip; tailwind; email handling 
            - https://www.saasstarterkit.com/ 
                - Billing: Stripe 
                - Documentation: Good // mostly flushed out // https://docs.saasstarterkit.com/docs/intro/welcome/
                - Deployment: on your own 
                - Databases: relational (postgres) and non-relational (mongoDB) 
                - Pros: ML example buil in; on-boarding; docker; stripe; AWS APIs; 
        - Paid:
            - https://bedrock.mxstbr.com/ (396 p/project) 
            - https://serverless.page/ (199 lifetime) 
            - https://reactapp.dev/ (19 lifetime) 
            - https://saasrock.com/ (149 lifetime) 
            - https://nextlessjs.com/ (699 p/project) 
- Low Code / No code
    - Backend
        - Supabase
        - Parse - https://parseplatform.org/ 
        - Appwrite - https://appwrite.io/ 
        - Nhost - https://nhost.io 
        - Hasura 
	- Pocketbase - https://github.com/pocketbase/pocketbase
    - Frontend
        - AppGyver 
- Data bases DBs
    - Modern:
        - FaunaDB - https://medium.com/codesphere-cloud/is-faunadb-the-next-big-database-technology-4c5a67915d6e  
        - SingleStore - https://www.singlestore.com 
        - Apache Druid / would view this as a competitor to SingleStore - https://druid.apache.org/ 
        - RethinkDB - live DB - https://rethinkdb.com 
        - Firebase 
        - DyanmoDB 
- Frontend - Styles 
    - Fonts / Styles
        - https://medium.com/@anthonyjdella/why-you-should-use-a-developer-font-b19d5269d767
    - Examples of good stuff 
        - https://www.reallygoodux.io 
- Opensource alternatives:
    - Airflow: 
        - https://nocodb.com 
        - More airflow like ones -> https://medium.com/swlh/top-3-low-and-no-code-databases-for-creative-entrepreneurs-b10f069c36b3 
    - Calendly: 
        - https://cal.com 
- Documentation
    - Docusaurus - https://docusaurus.io 
    - Docz - https://www.docz.site       
- UUID - url friendly
    - https://javascript.plainenglish.io/introducing-a-url-friendly-unique-identifier-nanoid-fbf4d2162322 
- Search tools: 
    - Meili search tool 
    - Typesense https://typesense.org/ 
    - DeepHaven - https://deephaven.io  
    - Elastic search - https://diawahad.medium.com/elasticsearch-the-open-source-distributed-restful-json-based-search-engine-ready-for-the-big-640430fd655b 
- Testing
    - Chaos Engineering 
        - https://www.gremlin.com/product/ 
- Monitoring tools 
    - Uptime Kuma - https://github.com/louislam/uptime-kuma 
- Security
    - Cloud checks
        - Scout Suite (cloud specific) 
    - Identity management
        - https://www.strongdm.com 
    - Secrets management
        - Doppler - https://www.doppler.com 
        - Vault 
    - Dealing with multi-cloud account / going back and forth 
        - https://www.leapp.cloud/ // https://github.com/Noovolari/leapp 
    - Pen testing 
    	- Metasploit (now managed by rapid7) - https://GitHub.com/rapid7/metasploit-framework 
    	- VM hackable/volunerable machine testing - metasploitable - https://github.com/rapid7/metasploitable3 
    	- Onion browser - https://github.com/OnionBrowser/OnionBrowser 
    	- python based 
    		- https://github.com/brinhosa/awesome-pentest-tools-in-colab
    		- https://github.com/dloss/python-pentest-tools
    	- non-python based 
    		- https://github.com/enaqx/awesome-pentest (most starred) 
		- https://github.com/coreb1t/awesome-pentest-cheat-sheets 
		- https://github.com/jesusprubio/awesome-nodejs-pentest
		- https://github.com/CyberSecurityUP/Awesome-Cloud-PenTest
		- https://github.com/CyberSecurityUP/Awesome-PenTest-Practice


- IAAS:
    - Pulumi 
        - https://betterprogramming.pub/pulumi-a-true-infrastructure-as-code-paradigm-ac07c530e219 
    - Terraform related tools: 
        - Infracost // https://github.com/infracost/infracost 
        - Brainbooard - automatically create terraform // https://www.brainboard.co/ 
        - Checkgov - Checkov - looks for config errors 
- Data stacks 
    - Article - https://www.datafold.com/blog/the-modern-data-stack-open-source-edition 
    - Github - good list - > https://github.com/victorcouste/data-tools#ingestion 
- Webscraping 
    - Stealth: 
        - https://uxdesign.cc/stealth-web-scraping-in-python-avoid-blocking-like-a-ninja-8cb76db119ae 
- Kubernet tools 
    - Helm - Helm
    - Knative - https://knative.dev/docs/ 
    - Kubeflow - Kubeflow 
    - Crossplane - https://crossplane.io 
- ML
    - Primary: tensorflow (google) 
    - Primary: pyTorch (facebook)
    	- https://github.com/pytorch/pytorch 
    - Cheat sheet 
    	- https://github.com/afshinea/stanford-cs-229-machine-learning
    - Labeling tool
        - https://labelstud.io 
        - https://dataneuron.ai/product 
    - Bias 
        - https://github.com/dreji18/Fairness-in-AI
    - Drift/Monitoring 
        - https://www.nannyml.com/ 
    - Scary Usecases 
        - https://github.com/daviddao/awful-ai 
    - Explainable 
        - https://github.com/MAIF/shapash 
        - https://github.com/oegedijk/explainerdashboard
        - https://github.com/SelfExplainML/PiML-Toolbox
    - Forecasting 
        - https://github.com/Nixtla/neuralforecast
    - Features
        - Feather: https://github.com/linkedin/feathr 
    - NLP - langauge translation 
    	- meta open source FairSeq: https://github.com/facebookresearch/fairseq/tree/nllb 
    - NLP 
        - Spacy 
        - NER annotation - https://github.com/vopani/waveton/tree/main/apps/data_apps/ner_annotation 
    - NLP + Science Journals 
        - Pubmed Analysis - https://github.com/bepnye/EBM-NLP 
        - Taking articles and converting to JSON - > https://github.com/allenai/s2orc-doc2json 
        - Similarities across papers - https://github.com/stephenleo/stripnet 
        - Analyze PDFs -> tables, figures, etc... = https://github.com/Layout-Parser/layout-parser
        - NLP with graph and human search - https://github.com/boopalanjayaraman/athena  - https://www.tigergraph.com/graph-for-all/winners/third-place-most-impactful/
    - Premade ML/AI 
        - https://huggingface.co/ 
        - https://cloud.blobcity.com/code/explore 
        - https://github.com/trekhleb/homemade-machine-learning 
        - https://modelzoo.co/ 
        - Speech and audio: https://github.com/balavenkatesh3322/audio-pretrained-model 
            - NLP: https://github.com/balavenkatesh3322/NLP-pretrained-model 
            - CV: https://github.com/balavenkatesh3322/CV-pretrained-model 
    - AutoML
        - https://auto.gluon.ai/stable/index.html 
        - http://epistasislab.github.io/tpot/ 
        - https://github.com/mljar/mljar-supervised 
        - AWS solution - AWS Sagemaker Autopilot - https://aws.amazon.com/sagemaker/autopilot/
    - Recommendation 
        - Microsoft best practices - https://github.com/microsoft/recommenders
        - Suprise - http://surpriselib.com/
        - Collaborative
            - Good walkthrough of collaborative - https://sunjackson.github.io/2016/05/30/3cca3bba88363e21bbe6e536e4178018/ 
            - https://github.com/benfred/implicit
    - Computer Vision
    	- Text to Pictures -> https://github.com/lucidrains/DALLE2-pytorch
    	- Image augmentation (FB) -> https://github.com/facebookresearch/AugLy 
    	- Bunch of random faces for training -> https://github.com/microsoft/FaceSynthetics 
    	- Simple facial recognition -> https://github.com/ageitgey/face_recognition 
    	- Real time tracking -> https://github.com/tryolabs/norfair 
    	- Item tracking --> DEEPSORT --> https://learnopencv.com/understanding-multiple-object-tracking-using-deepsort/ 
    	- Digital Cloning Examples 
    		- Toolkit: https://github.com/titanlambda/identity-cloning-toolkit-ICT 
    		- Voice cloning: https://github.com/CorentinJ/Real-Time-Voice-Cloning
    		- Voice cloning: https://github.com/BenAAndrew/Voice-Cloning-App
    		- Paid service: https://www.synthesia.io/
     - Github - `Awesome` ML repos  
     	- General ML - https://github.com/EthicalML/awesome-production-machine-learning 
     	 
     	- General jupyter resources 1 - https://github.com/markusschanta/awesome-jupyter
     	- General jupyter resources 2 - https://github.com/ml-tooling/best-of-jupyter
     	- Deep learning (fakes, audio video, pose, etc...) - https://github.com/tugstugi/dl-colab-notebooks 
     - Notebook examples 
     	- General Notebooks/starter templates (GoogleSheets,Airtable,Sendgrid,Slack,etc..) https://github.com/jupyter-naas/awesome-notebooks 
     	- https://github.com/trekhleb/homemade-machine-learning
     	- https://github.com/lazyprogrammer/machine_learning_examples
     	- https://github.com/susanli2016/Machine-Learning-with-Python
     	- Tensorflow -- https://github.com/aymericdamien/TensorFlow-Examples
     	- Pytorch -- https://github.com/pytorch/examples 
     	- AWS sagemaker examples -- https://github.com/aws/amazon-sagemaker-examples


- Datasets for testing: 
	- https://towardsdatascience.com/data-repositories-for-almost-every-type-of-data-science-project-7aa2f98128b 

- Free Cloud Resources 
    - ORACLE - https://www.oracle.com/cloud/free/#always-free  
    - VERCEL - has always free 
    - HEROKU 



## Training and General Ed

- Training and learning stuff: 
    - Arch design / good book - https://bytebytego.com/ - system design the big archcive - https://media-exp2.licdn.com/dms/document/C561FAQHBrAeW02s_yw/feedshare-document-pdf-analyzed/0/1655057292746?e=1655942400&v=beta&t=PhyXPS-R-LcFIPYLrkfgiEXoiLKxNhSwIRg2nlClaSA  
    - Quick read on architecture -> https://orkhanscience.medium.com/software-architecture-patterns-5-mins-read-e9e3c8eb47d2 
    - ML learning with scikit learn: https://courses.dataschool.io/introduction-to-machine-learning-with-scikit-learn 
    - More Ai Visual Exapmle -> http://www.r2d3.us/visual-intro-to-machine-learning-part-1/ 
    - Ml fun example -> https://medium.com/mlearning-ai/if-i-buy-a-diaper-i-will-surely-pick-up-a-beer-e692895a0c65 
    - SSL Tunneling -> https://goteleport.com/blog/ssh-tunneling-explained/ 
    - Stanford Ml systems -> https://stanford-cs329s.github.io/syllabus.html 
    - Explainable Ai -> https://www.aidancooper.co.uk/a-non-technical-guide-to-interpreting-shap-analyses/ 
    - ML cheatsheet - https://github.com/soulmachine/machine-learning-cheat-sheet 
    - Kaggle Allstar book: https://github.com/abhishekkrthakur/approachingalmost 
    - MIT - Assortment of tools / instructions; https://github.com/shervinea/mit-15-003-data-science-tools 
    - Powerful python: https://powerfulpython.com/bootcamp/  
    - Interpretable ML: https://christophm.github.io/interpretable-ml-book/index.html 
    - Resource of resources: https://www.linkedin.com/posts/vipulppatel_ultimate-guide-to-ai-data-science-machine-activity-6860243081434828800--w_7 
    - Udemy course I like: https://www.udemy.com/user/kirilleremenko/ 
    - Sql training - forget what I found this: 
        - SQL Fiddle - a playground environment that let’s you create tables and run SQL queries in the browser 	(http://sqlfiddle.com/)
        - SQL Bolt - An interactive tutorial great for beginners (https://sqlbolt.com/)
        - Select Star SQL - An interactive tutorial (https://selectstarsql.com/)
        - SQL Murder Mystery - For intermediate/advanced SQL. Solve a murder mystery by running SQL queries (https://lnkd.in/en3-VnT9)
        - SQL Indexing for Devs - Indexing is an important concept for making SQL queries more efficient. This blog series provides a good introduction (https://lnkd.in/egBCqJPa)
        - SQL Zoo - Another interactive tutorial (https://lnkd.in/eeGAxE7q)
        - The SQL Tutorial for Data Analysis - Another great tutorial that segments topics by beginner, intermediate, and advanced (https://lnkd.in/eUq7VvMp)

    - Python Basics / Intro level 
    	- Official Python: https://bugs.python.org/file47781/Tutorial_EDIT.pdf
    	- Stanford: 
    		- https://web.stanford.edu/class/archive/cs/cs106a/cs106a.1206/lectures/4-Variables/4-Variables.pdf
		- https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/readings/python-review.pdf
		- https://stanfordpython.com/#/lectures
		- Stanford: https://stanfordpython.com/lecture/lecture-2-full.pdf 
		- Cloud computing intro: https://web.stanford.edu/class/cs349d/docs/L01_overview.pdf
    	- Harvard: 
    		- http://tdc-www.harvard.edu/Python.pdf
    	- UCSF: 
    		- https://www.library.ucsf.edu/ask-an-expert/data-science/programming/
    		- Python: https://swcarpentry.github.io/python-novice-inflammation/
    	- ECU: 
    		- https://ofe.ecu.edu/wp-content/pv-uploads/sites/277/2021/05/Python_intro_2021OFE.pdf
    	- Duke: 
    		- https://courses.cs.duke.edu/compsci260/fall14/resources/python.tutorial.1.2014.pdf
    	- Emertxe Information Technologies: https://www.slideshare.net/EmertxeSlides/presentations/5
    		- Datatypes: https://www.slideshare.net/EmertxeSlides/python-data-types 

