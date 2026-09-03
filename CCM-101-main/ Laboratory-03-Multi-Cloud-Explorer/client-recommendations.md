# Client Cloud Recommendations

## Scenario Analysis & Recommendations

### Client A – Startup Company
* **Recommended Platform:** Amazon Web Services (AWS)
* **Justification:** AWS is ideal for startups due to its generous AWS Activate credit program, extensive ecosystem, and vast array of off-the-shelf developer tools. Its pay-as-you-go pricing model allows startups to launch at minimal cost and scale seamlessly as traffic expands. AWS also offers extensive serverless capabilities that reduce operational overhead for small engineering teams.
* **Recommended Services:**
  1. **AWS Amplify / AWS Elastic Beanstalk:** For rapid mobile backend deployment and hosting.
  2. **Amazon DynamoDB:** Fully managed NoSQL database for flexible data scaling.
  3. **Amazon S3:** To store user-generated media and static assets.

---

### Client B – University
* **Recommended Platform:** Microsoft Azure
* **Justification:** Azure is the clear choice for a university already reliant on Active Directory, Windows Server, and Microsoft 365. Migrating to Azure enables identity synchronization via Microsoft Entra ID (formerly Azure AD) with minimal friction. Furthermore, the university can leverage Azure Hybrid Benefit to reuse existing Windows Server licenses, significantly reducing cloud migration costs.
* **Recommended Services:**
  1. **Microsoft Entra ID:** To extend on-premises Active Directory identities seamlessly to cloud resources.
  2. **Azure Virtual Machines:** To migrate legacy Windows Server workloads without re-architecting.
  3. **Azure SQL Database:** For hosted academic record databases with built-in high availability.

---

### Client C – AI Research Company
* **Recommended Platform:** Google Cloud Platform (GCP)
* **Justification:** GCP leads the industry in data analytics, machine learning frameworks, and AI infrastructure. Its proprietary Tensor Processing Units (TPUs) provide accelerated hardware performance specifically optimized for deep learning workloads. Additionally, Google Cloud’s unified Vertex AI platform streamlines the entire ML lifecycle from data preparation to deployment.
* **Recommended Services:**
  1. **Vertex AI:** End-to-end platform to build, deploy, and scale machine learning models.
  2. **Cloud GPUs / Cloud TPUs:** Custom hardware accelerators for high-performance ML training runs.
  3. **BigQuery:** Serverless, highly scalable data warehouse for processing research datasets.

---

### Client D – Global E-Commerce Company
* **Recommended Platform:** Amazon Web Services (AWS)
* **Justification:** AWS possesses the largest global infrastructure network, making it suitable for high-traffic, multi-region e-commerce operations requiring strict uptime. AWS offers multi-region active-active database configurations and robust edge caching capabilities. Furthermore, retail companies often avoid Microsoft Azure or GCP due to strategic retail competition, making AWS the industry standard for e-commerce.
* **Recommended Services:**
  1. **Amazon Route 53 & CloudFront:** Global DNS and Content Delivery Network (CDN) for fast, low-latency asset delivery.
  2. **Amazon Aurora (Global Database):** High-performance relational database with multi-region replication.
  3. **AWS Auto Scaling & Amazon ECS/EKS:** For dynamic capacity adjustments during high-traffic shopping events.

---

## Checkpoint 6: Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | Amazon Web Services | Generous startup credits, serverless maturity, fast setup time. |
| **Enterprise Organization** | Microsoft Azure | Native integration with corporate Microsoft stacks and hybrid configurations. |
| **Microsoft Environment** | Microsoft Azure | Direct compatibility with Active Directory, Windows Server, and Azure Hybrid Benefit licensing. |
| **AI / Machine Learning** | Google Cloud Platform | State-of-the-art Vertex AI ecosystem, BigQuery integration, and TPU hardware access. |
| **Kubernetes Deployment** | Google Cloud Platform | Home of Kubernetes development; GKE offers the most mature managed container environment. |
| **Global Web Application** | Amazon Web Services | Expansive global availability zone footprint, CloudFront edge network, and multi-region database scaling. |
