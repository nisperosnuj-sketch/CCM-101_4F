# Google Cloud Platform (GCP) Research

## 1. Overview
Google Cloud Platform (GCP), launched publicly in 2008, is Google's suite of cloud computing services running on the same internal infrastructure that Google uses for its end-user products, such as Google Search, YouTube, and Gmail.

## 2. Global Infrastructure
* **Regions:** 40+ Regions worldwide.
* **Zones:** 120+ Zones distributed across regions.
* **Network:** High-speed, private global fiber-optic network backbone connecting all data centers.

## 3. Cloud Management Console
The GCP Console (`console.cloud.google.com`) provides a clean, unified interface organized by projects. Operations can also be driven via the `gcloud` CLI, Cloud Shell, and Deployment Manager / Terraform.

*Screenshot Evidence:*  
![GCP Console Overview](assets/screenshots/gcp-console.png)

## 4. Core Services

* **Compute — Google Compute Engine (GCE):** High-performance customizable virtual machines hosted on Google's infrastructure.
* **Storage — Cloud Storage:** Unified, durable object storage with globally consistent access classes (Standard, Nearline, Coldline, Archive).
* **Networking — VPC (Virtual Private Cloud):** Global-scope virtual private networks that allow resources in different regions to communicate internally without traversing the public internet.
* **Identity — Cloud IAM:** Provides fine-grained access control and visibility for managing Google Cloud resources permissions centrally.

## 5. Three Key Advantages
1. **Leadership in AI/ML & Data Analytics:** Industry standard tools including BigQuery, Vertex AI, and custom TPU (Tensor Processing Unit) hardware.
2. **Kubernetes & Container Innovations:** GCP originated Kubernetes (GKE) and leads in container-native serverless technology.
3. **Global Private Network:** Traffic between GCP data centers travels across Google's own private fiber network, reducing latency and transit costs.

## 6. Enterprise Use Cases
* Advanced Data Analytics and real-time streaming pipelines using BigQuery and Dataflow.
* Containerized microservice deployments managed via Google Kubernetes Engine (GKE).
* Machine Learning model development and training using Google Vertex AI.
