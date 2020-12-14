+++
title = "Phil Kershaw - AWS Solutions Architect and Certified ScrumMaster™"
+++

## Personal Profile

{{< figure class="avatar" src="https://s.gravatar.com/avatar/7bf13c9d27600b733cec879994746108?s=157" >}}

Hi, I am Phil Kershaw, an accomplished Lead Engineer with a background in software engineering and SecDevOps across a range of business sectors - including but not limited to Telecomms and Big Pharma – as well as extensive experience in the design and delivery of large-scale projects on AWS.

I have a particular interest in Architecting Solutions for AWS (including COTS or OpenSource components when necessary), Big Data and ML/AI.

## Certifications

|                                               | Expiry              |
| --------------------------------------------- | --------------------|
| AWS Certified Solutions Architect - Associate | Oct 2018 – Oct 2021 |
| Certified ScrumMaster (CSM)                   | Feb 2018 – Feb 2022 |

## Recent Experience 
### AstraZeneca UK Ltd – Contract (October 2019 – Present) 
Joining the Imaging Platform team at grass roots I quickly established myself as the Tech Lead across 2 projects and AWS SME on a 3rd: 
###### Key Responsibilities Across all Projects: 
- Ensured testability of all infrastructure as code using AWS CDK TypeScript 
- Established a CI/CD pipeline to manage multiple environments using BitBucket Server, Jenkins Pipeline, Serverless Framework and AWS CDK 
- Provided guidance, advice on AWS and its services and liaise with AWS Concierge Service where necessary 
- Liaised with CSIS (Cloud Management) to procure AWS accounts dedicated to the Imaging Platform 
- Liaised with Networking to set up VPN connectivity from On-Prem network to two Imaging Platform AWS Accounts 
- Served as Scrum Master and advised imaging projects as a Scrum coach 
##### SCIENCE DATA FOUNDATION IMAGING PLATFORM 
The SDF Imaging Platform serves as the "one stop shop" data lake for biomedical images and related metadata at AstraZeneca. It provides the ability to discover and access images relevant to a particular avenue of research. 
###### Key Achievements: 
- Lead on design and delivery of the SDF Imaging Platform release 1 using AWS cloud services. Taking an existing PoC and producing a cloud native solution. 
- Created Ansible Playbooks to provision EC2 instances across all environments (dev, test, staging, production) 
- Develop nano-services to perform extraction of medical images in DICOM format and Whole Slide Images in a range of formats including SVS and NDPI 
- Designed Step Function state machine to orchestrate activities on images and their metadata based on source and format and eventual destination  
- Designed an API for providing access to the complex and diverse imaging metadata using AppSync (GraphQL) and DynamoDB in addition to supplying pub/sub capabilities using SNS 
- Implemented dashboard in CloudWatch to monitor image processing activity and throughput 
- Implemented custom alerting based on application log output using custom metrics, CloudWatch Alarms and SNS 
- Advised on Agile practices and; recommend iterative changes to the way the team worked and organised based on the Scrum Framework 

*More recently in this role:*
- Created a cross-platform CLI utility written in Python 3 for obtaining AWS STS keys when authenticated via Ping Federate SAML - AWS integration and assuming a Federated Role to replace the distribution of IAM Keys 
- Instrumental in the Solution Architecture of an API that enables:  
  - Multiple imaging workstreams to contribute to a universal database of imaging metadata 
  - Free text searching of image metadata 
  - More complex querying of metadata using GraphQL 
- Lead on the design and delivery of a solution for an internal HTTP API to enable Validation, Transformation and Governance of imaging metadata using API Gateway (Private), VPC Interface Endpoint 
- Liaised with MuleSoft architecture and development to establish integration with the internal API 
- Lead on the design and delivery of a solution for deploying distributed graph database, Dgraph using AWS Fargate 
##### HALO UPLIFT PROJECT 
The Halo Uplift Project was a Proof of Concept to answer the questions of “Can we migrate on-prem Halo to the Cloud?” and “How much will it cost to deploy and run?” 
###### Key Achievements: 
- Lead on the design and delivery of configurable and reusable (dev, test etc..) infrastructure using AWS CDK to deploy scalable clustered EC2 instances of varying size and a MySQL Database cluster using AWS RDS 
- Created Ansible playbooks to provision the EC2 instances and install: Halo Clients; Halo AI; Halo Link; Halo API; Halo Analysis 
- Lead a Proof of Concept to assess the possibility of using AWS AppStream for end-user access management and governance 
- Liaised with Data Scientists on system testing 
- Liaised with Product Owner and Business Analyst on solution costing and viability 
- Liaised with Indica Labs on the installation process for each of the Halo products 

##### CPSS IMAGING DATABASE 
The CPSS Imaging Database is an image data and metadata management system for digital pathology, in-vivo, and mass spectrometry imaging designed around a BPMN engine (Camunda Zeebe). Its purpose is to gather metadata from services internally – such as eSlide Manager, bioELN – and externally, such as BSI – before combining these data with metadata extracted from image files (in various formats: SVS, NDPI, bif, DICOM), transforming it using JSONata, and storing in Dgraph. 

###### Key Achievements: 
- Lead on the design and building of infrastructure in AWS CDK for deploying more than 15 services to AWS Fargate. Services included: Camunda Zeebe; Camunda Operate; Elastic Search & Kibana; Dgraph 
- Implemented persistent storage for containers running in AWS Fargate using AWS EFS 
- Designed and implemented inter-service connectivity by applying Service Discovery using Cloud Map and on-prem connectivity using a combination of internal Application and Network Load balancers 
- Designed and implemented hub-and-spoke CI/CD pipeline using Jenkins Pipeline, samver 
- Assumed Scrum Master role. Facilitated daily Stand-up events and regular Backlog Refinement events. 

My time served across these projects has resulted in my becoming very confident around Medical and Whole Slide Imaging. Particularly DICOM and WSI formats supported by BioFormats. However, most instrumental in my achievements here have been the relationships I’ve built across many departments including CSIS, TTA, Precision Medicine, Networks, Architecture, Cyber Security, DevOps not to mention the dedicated AWS Concierge Team. 
###### Key Skills: 
Team Leadership, Mentoring, AWS Solution Architecture, AWS CDK, CI/CD, Jenkins, TypeScript, Python 

### yboo Ltd – Contract (October 2018 – August 2019) 
yboo was a platform designed to provide mobile users with accurate mobile provider recommendations based on usage (voice, sms, mms and data) and frequented locations. The technology stack consisted of Ruby on Rails, nodejs, MongoDB Atlas running on Heroku. 
###### Key Achievements: 
- Lead the migration from Ruby/Heroku to NodeJS/AWS Cloud native for real-time data ingress and processing 
- Managed scaling and sharing of the MongoDB Atlas cluster to improve throughput of realtime data 
- Reconfigured MongoDB to provide dedicated analytics node 
- Implemented event stream processing using API Gateway, Kinesis, lambda 
- Lead on implementing best practice and CI/CD process to enable faster delivery to market 
- Managed 3rd party mobile app development and established new working agreement to improve quality



| Previous Relevant Employment |
| ---------------------------- |
| The Dining Club Group – Contract (May 2018 – August 2018) Skills: AWS Services and Tools, in particular: Terraform, API | Gateway, IAM, Lambda, S3, DynamoDB, DeepLens, Amplify, PHP, Go, TDD (PHPUnit, testing.T), MySQL, Docker, Jenkins, DevOps |
| William Hill Plc - Contract (March 2016 - February 2018) Skills: Team Leadership, Mentoring, Python, Go, TDD (unittest.py,testing.T), Splunk, Docker, API Integration, Ruby, JavaScript, TDD (RSpec, Jest), Ruby On Rails, Postgresql, Docker, Marathon/Mesos, Jenkins, DevOps, Scrum |
| IntechnologyWIFI - Contract (October 2015 - January 2016) Skills: Python, PHP, MySQL, API integration |
| Vodafone UK – Contract (May 2015 – August 2015) Skills: Python, Django, Scrum |
| LED Hut Ltd (June 2014 - November 2014) Skills: PHP, Magento, Laravel, SysAdmin, MySQL |
| Wilson and Cooke (November 2013 - June 2014) Skills: PHP, WordPress, SysAdmin, MySQL |
| Docnet Ltd (January 2013 - November 2013) Skills: PHP, Zend Framework, SysAdmin, MySQL |
| Begbies Traynor Group Plc (February 2012 - January 2013) Skills: PHP, Python, Django, Symphony, Doctrine, MySQL |
| Zimo Communications Ltd (June 2011 - February 2012) Skills: PHP, Zend Framework, MySQL |
| Manchester Metropolitan University (April 2007 - June 2011) Skills: PHP, CakePHP, MySQL, SysAdmin |
 