# aws-cicd-pipeline-project
This repository showcases a complete Serverless CI/CD Pipeline setup using AWS services like ECR, ECS, Fargate, CodePipeline, and Route 53.

# 🚀 AWS CI/CD Pipeline Project

This project demonstrates a complete **Serverless CI/CD Pipeline** on AWS using services like:
- **ECR (Elastic Container Registry)**
- **ECS with Fargate**
- **CodePipeline**
- **Route 53**
- **CloudWatch Logs & Alarms**

---

## 🔧 Tools & Services Used

- **AWS EC2, ECR, ECS, Fargate**
- **Docker**
- **GitHub**
- **AWS CodePipeline**
- **Route 53**
- **CloudWatch & S3**
- **Load Balancer with HTTPS Certificate**

---

## 📸 Architecture Diagram

![Server Based Architecture](./images/Screenshot-architecture.png)

---

## 📝 Project Documentation

- `docs/AWS & DevOps.docx` → DevOps Basics + AWS Integration
- `docs/CICD ON AWS.docx` → Full step-by-step pipeline setup
- `docs/CICD Architecture.drawio` → CI/CD Pipeline diagram
- `docs/Microservices architecture.drawio` → Microservices deployment plan

---

## 🔁 Pipeline Flow Summary

1. **Launch EC2** and set up Docker + Git
2. **Clone application repo**
3. **Build Docker Image** and push to **ECR**
4. Create **ECS Cluster** and define Task Definition
5. Use **AWS Load Balancer + HTTPS**
6. Connect domain via **Route 53**
7. Monitor using **CloudWatch** and **S3 logs**
8. Automate all using **AWS CodePipeline**

---

## 📬 Contact

👤 **Karunakar Jadi**  
📧 karunakarjadi000@gmail.com  
🔗 [GitHub](https://github.com/Karunakarjadi1609) | [LinkedIn](https://linkedin.com/in/karunakarjadi123)
