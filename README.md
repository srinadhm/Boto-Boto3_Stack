# Boto-Boto3_Stack

https://www.oodlestechnologies.com/dev-blog/boto3-sdk-use-cases/

jenkins 
-------
Advantages 
disadvantages
use cases 
best practises while using jenkins 
---------
Ansible 
Advantages 
disadvantages
use cases 
best practises while using Ansible  
-----------

docker
Advantages 
disadvantages
use cases 
best practises while using docker 
-----------

terraform 
Advantages 
disadvantages
use cases 
best practises while using terraform 
------------

lambda
Advantages 
disadvantages
use cases 
best practises while using lambda 
---------

boto3
Advantages 
disadvantages
use cases 
best practises while using boto3 
---------

shell scripting 
Advantages 
disadvantages
use cases 
best practises while using shell scripting 
---------

Kubernetes 

Advantages 
disadvantages
use cases 
best practises while using k8s 
-----------

ELK stack /EFK stack 

Advantages 
disadvantages
use cases 
best practises while using ELK/EFK 
-----------

Promotheus and Grafana

Advantages 
disadvantages
use cases 
best practises while using Promotheus and Grafana 


Kubernetes :
==========================================
1) what is taint and toleration 
2) node affinity an pod affinity 
3) how to check the logs of a pod or deployment? kubectl logs 
4) how to check how many pods are running kubectl get pods
5) what are deployment strategy used in your project 
6) what is init container
7) what is statefullset
8) what is ingress
9) difference between headfull and headless service
10) difference between secret and configmap
11) what is livenessprobe and readynesspeobe
12) how to access other pods in a cluster 
13) what is a pod
14) how you will make sure that the database should start first and then application
15) Types of storage class used in your project
16) difference between statefullset and stateless
17) describe kubernetes architecture
18) difference between PV and pvc
19) 2 containers are running inside a pod if one container goes down then will it affect other running container
20)  Update the password in secret without restarting the pod or deployment ,is it possible ?
21) how to rollback the deployment?
22) what is the reason for pod eviction?
22) pod is in pending state ,what are the possible reasons?
23) how you will make sure that in rolling update strategy 2 pods are always available?
24) crashloopbackoff, what are the possible reasons?
25) why you are using 3 master node in production?
26) how you will make sure that pod should be running on a specific node?
27) how to check what are the activities performed by the container while creating the pod
28) how to get the ip of a pod ?
29) which network plugin you are using?
30) how you are monitoring the kubernetes cluster and the containers
31) Job should be terminated after 40 seconds ? ActiveDeadLineSeconds: 40

==================================================================================
DOCKER :
=============================================================================================

1) difference between add and copy ?
2) difference between CMD and entry point ?
3) ADD . .
4) what is docker file ?
5) how to check how many containers are running ?
6) docker logging driver ?
7) what is difference between bridge network and custom bridge network?
8) difference between  overlay network and host network ?
9) what is port forwarding in docker what is the use of it ? 
10) how to login/enter to a container? 
11) what is docker  system prune and docker image prune?
12) how many types of volumes are there in Docker? (Local and network)
13) How to check image vulnerabilty ?



-----------------------------------------------------------------------------------------------------


1.    Jenkins, Maven, Master/Slave, Pipelines - scripted, declarative - # 1 CI tool
2.    Git – BitBucket/GitHub/Azure Git - # 1 - SCM tool
3.    Terraform # 1 Infrastructure automation tool 
4.    Ansible- # 1 Configuration Management tool
5.    Docker- # 1 Container platform  
6.    Azure DevOps, Pipelines – Microsoft platform for migrating applications to Azure Cloud
7.    Puppet # 2 Configuration Management tool
8.    SonarQube – # 1 Code quality tool
9.    Slack – # 1 Collaboration tool
10.  Nexus – # 2 Binary repo manager 

Finally having some scripting knowledge is also good – Python, YAML playbooks, JSON script
Cloud experience - AWS and Azure



https://www.youtube.com/watch?v=EBSdyoO3goc&list=PLAojaZQlas_ij3cyOQlRK0Zh1uQ_hWpet

https://www.youtube.com/watch?v=Ey9waqflzI4&list=PLjJWtyuv5yrrMl5xVF5B_NrMcb7fjenDt&index=11

Boto3 Urls
___________

Boto/Boto3 Installation


1. You’ll first use the yum package manager to install Python and the pip Python package installer:

yum install python python-devel python-pip -y

2. Now we will install the Boto package via pip:

pip install boto3 

Finally, we can test if everything has been successfully installed on our Linux box:
python -c "
import boto3; 
print boto3.__version__"

2.9.6

boto3.__version__

--------------------------


https://dashbird.io/blog/boto3-aws-python/

https://www.oodlestechnologies.com/dev-blog/boto3-sdk-use-cases/

https://www.oodlestechnologies.com/blog/tagged/AWS/1

https://cloudacademy.com/blog/boto-python-automate-aws-services/

https://pypi.org/project/boto/

https://github.com/boto/boto boto 

https://github.com/boto/boto3 boto3

https://cloudacademy.com/library/devops/



https://boto3.amazonaws.com/v1/documentation/api/latest/guide/s3-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/ec2-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/iam-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/cw-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/dynamodb.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/kms-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/secrets-manager.html


https://boto3.amazonaws.com/v1/documentation/api/latest/guide/ses-examples.html

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/sqs-examples.html



https://www.learnaws.org/posts/10/

https://www.learnaws.org/2019/09/27/choose-right-aws-tools/  

https://www.learnaws.org/2020/12/18/aws-ses-boto3-guide/

https://www.learnaws.org/2021/05/05/aws-sns-boto3-guide/

https://www.learnaws.org/2020/12/16/aws-ec2-boto3-ultimate-guide/

https://www.learnaws.org/2021/05/12/aws-iam-boto3-guide/

https://www.learnaws.org/2021/02/26/aws-secrets-manager-boto3-guide/

https://www.learnaws.org/2021/02/20/aws-kms-boto3-guide/

https://www.learnaws.org/2020/12/17/aws-sqs-boto3-guide/


https://www.learnaws.org/2021/06/25/eks-github-ci/

https://boto3.amazonaws.com/v1/documentation/api/latest/guide/iam-examples.html



