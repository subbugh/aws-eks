# aws-eks
Amazon Elastic Kubernetes Service - The most trusted way to run Kubernetes.
---------------------------------------------------------------------------
It is an detailed Hands-on guide/ POC/ Case Study/ Use Case. For more details please refer to the PPT or PDF enclosed in this repo AWS_EKS.pptx and AWS_EKS.pdf. 

Details of the Case Study/ POC:
-------------------------------
•Deploying an nginxsample application on the Amazon EKS Cluster.

•There will an EKS cluster created on the AWS with the Worker nodes connected, which are configured with Auto scaling.

Steps, Hands-on activity:
-------------------------
1.Create Role –Create IAM role with necessary policies attached to make the user to access EKS services.

2.Create VPC –Through a CloudFormationtemplate, to create the necessary secured networking for the EKS services.

3.Create EKS Cluster.

4.Install Kubectl–Used to access EKS cluster through CLI.

5.Install Eksctl–Enables the users to access the EKS services through CLI.

6.Install aws-iam-authenticator -Enables the users to authenticate and access the EKS Cluster through CLI from the remote systems.

7.Create Worker nodes.

8.Map the worker nodes with EKS Cluster.

9.Deploy the Sample application.

10.Delete Worker nodes and the EKS Cluster.
