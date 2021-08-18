#Nanodegree: DevOps Engineering Nanodegree
#Task:       Project 2 Deploying a high availability web app using cloudformation

I am Emmanuel Odenyire, a BIT Udacity Scholar taking Cloud DevOps Engineering Nanodegree.
The Nanodegree requires us take five projects and I am currently, I am undertaking my second project which requires me to 
deploy a high availability web application using CloudFormation script.
We have been given the project requirements as: deployment of 4 servesrs, with two located in each private subnets, configuration 
to be used by an autoscaling group, 
two vCPUs and at least 4GB of RAM in the servers, with the operating system dictated to be Ubuntu 18.

We have also been directed to create an IAM role that allow instances to use the S3 service among other requirements.

#Oroject undertook

In this project, I am deploying web servers for a highly available web app using CloudFormation. 
I have written the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up as instructed. 
I will begin with deploying the networking components, followed by servers, security roles and software. 

After the basic structure of network and servers are set up, I will also set a cloudwatch alarm to notify when the total error rate exceeds 

We have set up a SNS service to receive email in the scenario of this alarm getting triggered.

Attached with this ReadMe file are:
1. Shell scripts used in Windows platform
2. AWS Templated for network and servers parameters
3. AWS YAML files for the network and servers parameters



