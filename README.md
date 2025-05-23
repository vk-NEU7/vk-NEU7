![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=vk-NEU7)

# Hi, I'm Vinay Kumar Chelpuri 👋

## ⚡ About Me  

**Software/DevOps Engineer** with 3 years of professional experience, specializing in building **Java applications**, designing multi-cloud solutions with **AWS & GCP**, and leveraging **Kubernetes orchestration** for scalable deployments. My expertise includes developing, testing, and deploying object-oriented and web-based applications using **Java/J2EE technologies**, with a strong foundation in **Servlets, JSP, JDBC, multi-threading, MVC**, and design patterns. I have experience with frameworks such as **Spring MVC, Spring Boot**, and **Hibernate**, and in creating dynamic front-end applications using **Angular** and **TypeScript**.



I enjoy exploring **LLMs (Large Language Models)** by integrating them with **Retrieval-Augmented Generation (RAG)** systems to tackle complex challenges. Constantly experimenting with new technologies, I actively use **Go** for innovative projects and an active member of the **[Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/)**. I also spend time on platforms like **[Hacker News](https://news.ycombinator.com/)** to stay informed about the latest tech advancements.

---

## 🚀 Key Projects

### **[llaMaCVE.ai 🤖](https://github.com/cyse7125-su24-team10)**  
A **[CVE (Cybersecurity Vulnerabilities)](https://cve.mitre.org/) Insights Platform** leveraging LLM's to help users secure their devices, detect vulnerabilities early, and adapt to emerging cyber threats. This platform offers high reliability and a user-friendly interface, powered by **real-time processing** and **scalable infrastructure**. A **production-ready** solution to mitigate LLM data staleness and **hallucinations** by automating continuous vector database updates, ensuring accurate and up-to-date embeddings.

- **RAG Chatbot**: Designed and Developed a **Retrieval-Augmented Generation (RAG) Chatbot** using **Llama-3.1-8b(an Open Source LLM)**, **LangChain**, and **Python** to process **250K CVE JSON records**. Integrated the **[Pinecone](https://www.pinecone.io/) vector database** to store embeddings of CVE data, enabling fast, real-time queries and access to the latest CVE insights.

- **Data Processing & Storage**: Built a suite of **3 microservices** w/ **[Go](https://go.dev/)** for **CVE data normalization** and **[Kafka](https://kafka.apache.org/)** for asynchronous message processing. Ensured seamless data management with **Flyway migrations** for **[PostgreSQL](https://www.postgresql.org/)**, maintaining schema integrity and automating updates.

- **Kubernetes Cluster**: Deployed a **highly available [Kubernetes](https://kubernetes.io/) cluster** on **[AWS](https://aws.amazon.com/eks/)** with **multi-AZ deployment**. Integrated **Istio** for secure service-to-service communication, **Kafka** for real-time messaging, and **KMS** for encryption, ensuring high availability and scalability for **CVE processing** and the RAG model. Managed infrastructure with **Helm charts** and auto-scaling for **CVE processing applications**, ensuring optimal performance under varying workloads.

- **CI/CD Pipelines**: Streamlined application deployments by automating **AWS AMI** image creation using **HashiCorp [Packer](https://www.packer.io/)** with pre-configured **[Jenkins](https://www.jenkins.io/)** and **[NGINX](https://nginx.org/)**. Designed robust **CI/CD pipelines** using **Jenkins DSL** and **[Terraform](https://www.terraform.io/)**, enabling seamless deployment of applications on **Amazon EKS**. Integrated **GitHub Webhooks** for continuous integration, automating Docker image builds and pushes with zero downtime during updates. Adopted **[Semantic Versioning 2.0.0](https://semver.org/)** and enforced **Conventional Commits** for automated GitHub Releases, ensuring consistency across deployments. Extended this approach to container image versioning, enabling reliable traceability and rollbacks.

- **Service Mesh & Security**: Deployed an **[Istio](https://istio.io/) service mesh** with **Ingress**, **VirtualService**, and **mTLS** for secure, reliable communication between microservices. Integrated **Kiali** and **Jaeger** for traffic management, tracing, and visualization, reducing troubleshooting time by **30%** and improving operational efficiency.

- **Centralized Monitoring**: Implemented centralized monitoring with the **[EFK](https://www.elastic.co/elastic-stack) stack** and **[Prometheus](https://prometheus.io/)/[Grafana](https://grafana.com/)** for logging, metrics collection, and visualization. Achieved **99.9% alert accuracy**, reducing **mean time to detection (MTTD)** by **40%**.

- **Kubernetes Operator**: Designed a custom CRD with **[Kubebuilder](https://book.kubebuilder.io/)** to monitor and process hourly CVE releases, automatically fetching new CVE records and integrating them with **Kafka** and **Pinecone** for indexing and real-time processing.

- **Security Posture Enhancement**: Improved security by automating **SSL/TLS certificate management** with **[cert-manager](https://cert-manager.io/)** and **secret management** using **[SOPS](https://github.com/getsops/sops)**, ensuring zero downtime during key rotations and improving security by **35%**.

- **LLM Deployment**: The **Llama-3.1-8b** model is deployed using the **[Ollama](https://artifacthub.io/packages/helm/ollama-helm/ollama/0.4.0) service** on an **AWS GPU instance g5.xlarge**, ensuring efficient and scalable LLM deployment and inference.

#### ⚙ Project Demo  
[![LLaMaCVE Demo](https://img.youtube.com/vi/WlghN6UE7YA/0.jpg)](https://www.youtube.com/watch?v=WlghN6UE7YA)


### **[🌩️ skynetx.me](https://github.com/cloudapp6225)**  
A cloud-native web application focused on performance and scalability, hosted on Google Cloud Platform:  
- Built a robust **RESTful API Server** following **[Twelve-Factor](https://12factor.net/) App** principles, implemented **CI/CD** with **GitHub Actions** on **[Google Cloud](https://cloud.google.com/)**, utilizing **Cloud SQL** and **VPC peering** for secure database access.  
- Developed an **event-driven system** with **[Pub/Sub](https://cloud.google.com/pubsub/docs/overview)** and **Cloud Run**, enhancing scalability to handle 10x traffic spikes while maintaining response times under 200ms.  
- Secured sensitive data with **CMEK encryption** for **Secrets**, **VM disks**, and **Cloud SQL**, and enforced **IAM roles** adhering to **Principle of Least Privilege (POLP)**, strengthening overall security.  

---

## 💼 Work Experience  

### **Graduate Teaching Assistant: Advanced Cloud Computing**  
*Northeastern University, Boston, MA | Jan 2025 – May 2025*  
- Mentored students on leveraging Kubernetes for container orchestration, enabling scalable, highly available system designs in a microservices architecture.
- Guided students in implementing CI/CD pipelines with Jenkins, and GitHub Actions, automating software deployment processes.


### **Software Engineering Analyst**  
*Accenture, Hyderabad, India | Sept 2021 – Aug 2023*  
- Reduced API costs and prevented DDoS attacks by implementing IP rate-limiting for high-traffic microservices using **Spring Boot** and **Redis caching**.  
- Optimized system performance, reducing response times by 80%, and enhanced CI/CD pipelines for 10+ microservices using **Jenkins**.  
- Deployed microservices on **Amazon EKS**, leveraging Kafka for real-time data processing and centralized monitoring with **CloudWatch**.  

### **Associate Software Engineer**  
*Accenture, Hyderabad, India | Nov 2020 – Aug 2021*  
- Built Angular-based order tracking features, reducing ticket resolution times by 50%.  
- Automated deployment workflows and maintained 15+ microservices, ensuring high reliability and scalability.  

---

## 🔧 Skills & Technologies
![Java](https://img.shields.io/badge/Java-ED8B00?logo=java&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=spring-boot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-FF5733?logo=chainlink&logoColor=white)
![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?logo=google-cloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Packer](https://img.shields.io/badge/packer-%23E7EEF0.svg?logo=packer&logoColor=%2302A8EF)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?logo=istio&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-3b82f6?logo=openTelemetry&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apache-kafka&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-00B1B0?logo=pinecone&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=white)
![Cert-Manager](https://img.shields.io/badge/Cert%20Manager-00A99D?logo=cert-manager&logoColor=white)
![Kiali](https://img.shields.io/badge/Kiali-5F8D61?logo=kiali&logoColor=white)
![Jaeger](https://img.shields.io/badge/Jaeger-00B4B6?logo=jaeger&logoColor=white)



---

## 🏆 Certifications  
- **[Certified Kubernetes Administrator (CKA)](https://www.credly.com/badges/b88a39e3-bc9a-43a1-a597-19bb700b3a50/public_url)**  
- **[AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/a0773eaf-4d97-48d8-960c-48a0cb43abd0/public_url)**
- **[Microsoft Certified: Azure Fundamentals](https://www.credly.com/badges/c0044ba4-af2c-4bd9-ad60-ac8705fd1c4f/public_url)**   

---
## 🥷 GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com/?user=vk-NEU7)](https://git.io/streak-stats)


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=vk-NEU7&size_weight=0.5&count_weight=0.5)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=vk-NEU7&show_icons=true&theme=radical)

---

## 📫 Connect with Me  
- [LinkedIn](https://linkedin.com/in/vinaychelpuri) 
- [Email](mailto:chelpuri.v@northeastern.edu)  

---

