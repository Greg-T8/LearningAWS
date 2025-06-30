# My notes from "AWS for Solution Architects" by S. Shrivasta, N. Srivastav, A. Artasanchez, I.Sayed

<img src='images/20250630053312.png' width='350'/> 


<!-- omit in toc -->
## Contents

- [1. Understanding AWS Principles and Key Characteristics](#1-understanding-aws-principles-and-key-characteristics)
  - [Basic cloud and AWS terminology](#basic-cloud-and-aws-terminology)


##  1. Understanding AWS Principles and Key Characteristics

- AWS was launched in 2006
- Major companies begain migrating to AWS in 2008, including Netflix, Robinhood, Lyft, Capital One, and GE.
- AWS has over 200 services and has been the market leader in cloud computing for over a decade.

### Basic cloud and AWS terminology

Cloud providers have different names for the same concenepts. Example for VMs:
- AWS uses Elastic Compute Cloud (EC2) instances.
- Azure uses Azure Virtual Machines.
- GCP uses Google Compute Engine.

| Service                              | AWS                                                                                                                | Azure                                                                                  | GCP                                                                                           |
|-------------------------------------- |--------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| **Compute**                          | • Amazon EC2<br>• Lightsail                                                                                        | • Azure Virtual Machines<br>• Virtual Machine Scale Sets                               | • Google Compute Engine<br>• Graphics Processing Unit (GPU)                                   |
| **Containers**                       | • Amazon Elastic Container Service (ECS)<br>• Amazon Fargate<br>• Elastic Container Service for Kubernetes<br>• Elastic Container Registry<br>• Batch<br>• Amazon EMR | • Azure Kubernetes Service (AKS)<br>• Container Instances<br>• Batch<br>• Service Fabric<br>• Cloud Services | • Google Kubernetes Engine<br>• Knative<br>• Container Security                               |
| **Serverless Technologies**           | • AWS Lambda                                                                                                       | • Azure Functions                                                                      | • Google Cloud Functions                                                                      |
| **Relational Databases**              | • Amazon Relational Database Service (RDS)<br>• Aurora<br>• Redshift                                               | • Azure SQL Database<br>• Data Warehouse<br>• Server Stretch Database<br>• Table Storage<br>• Redis Cache<br>• Data Factory | • Google Cloud SQL<br>• Cloud Spanner                                                         |
| **NoSQL Databases (Key Value)**       | • Amazon DynamoDB                                                                                                  | • Azure Table Storage                                                                  | • Google Cloud Datastore<br>• Google Cloud Bigtable                                           |
| **NoSQL Databases (Indexed)**         | • Amazon SimpleDB                                                                                                  | • Azure Cosmos DB                                                                      | • Google Cloud Datastore                                                                      |
| **Object Storage**                    | • Amazon Simple Storage Service (S3)                                                                               | • Azure Blob Storage                                                                   | • Google Cloud Storage                                                                        |
| **File Storage**                      | • Amazon Elastic Block Store (EBS)<br>• Snowball<br>• Snowball Edge<br>• Snowmobile<br>• Amazon Elastic File System (EFS) | • Azure Managed Disks<br>• Azure File Storage                                          | • Google Compute Engine Persistent Disks<br>• Persistent Disk<br>• ZFS/Avere<br>• Transfer Appliance<br>• Transfer Service |
| **Archival Storage**                  | • Amazon Glacier                                                                                                   | • Azure Archive Storage                                                                | • Google Cloud Storage Nearline and Coldline                                                  |
| **Domain Name Service (DNS)**         | • Amazon Route 53                                                                                                  | • Azure DNS                                                                            | • Google Cloud DNS                                                                            |
| **Peering**                           | • Amazon DirectConnect                                                                                             | • Azure ExpressRoute                                                                   | • Google Cloud Interconnect                                                                   |
| **Virtual Networking**                | • Amazon Virtual Private Cloud (VPC)                                                                               | • Azure Virtual Networks (VNets)                                                        | • Google Virtual Private Cloud                                                                |
| **Elastic Load Balancing**            | • Amazon Elastic Load Balancer                                                                                     | • Azure Load Balancer                                                                  | • Google Cloud Load Balancing                                                                 |
| **PaaS services**                     | • AWS Elastic Beanstalk<br>• VMware Cloud on AWS                                                                   | • App Service and Cloud Services                                                        | • Google App Engine                                                                           |
| **Machine Learning**                  | • SageMaker<br>• Machine Learning<br>• Rekognition<br>• Lex<br>• Polly<br>• Comprehend<br>• Translate<br>• Transcribe<br>• DeepLens<br>• Deep Learning AMIs | • Machine Learning<br>• Azure Bot Service<br>• Cognitive Services                      | • Google Cloud Machine Learning Engine<br>• Dialogflow<br>• Google Cloud Natural Language<br>• Google Cloud Speech API<br>• Google Cloud Translation API<br>• Google Cloud Video Intelligence<br>• Google Cloud Job