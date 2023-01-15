Project 2 - Deploy a High-Availability Web App using CloudFormation


In this project, I deployed web servers for a highly available web app using CloudFormation. The script creates and deploys the infrastructure and application for the Udagram app. Once the scripts are run, networking components are deployed followed by servers, security roles and software.


The file includes:
* networkandserver.yml : Udagram Project's CloudFormation script.
* networkandserver.json : Udagram Project's CloudFormation script parameters
* deployment images : Screenshots of the results of deployment.
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* delete.sh : Cloudformation delete stack script.

To Deploy : > ./create.sh UdacityUdagram networkandserver.yml networkandserver.json

website LB-EC2-s3 connectivity check - http://udaci-webap-126yfq63nfyjq-1520521550.us-east-1.elb.amazonaws.com/



