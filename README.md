# 🚀 Kubernetes for Dummies: From Zero to Deployment

Welcome to **Kubernetes for Dummies**, a hands-on, beginner-friendly course designed to take us from zero to deploying a production-style Spring Boot + MySQL application on a multi-node Kubernetes cluster.

Whether you're a developer like me, DevOps engineer, or simply curious about Kubernetes, this guide will walk you through the essentials — using modern tools like Docker Desktop, kubectl, and NGINX Ingress — and show how everything connects through real-world examples.

---

## 🧠 Course Goal

By the end of this course, we'll have a working deployment of a Kotlin-based Spring Boot app, backed by a MySQL database, running on a Kubernetes cluster with HTTPS access — and we'll **understand** every component we used to get there.

---

## 📚 Course Outline

### **Module 1: Introduction to Kubernetes**
**Objective:** Understand what Kubernetes is and why it matters.
- What is Kubernetes?
- Why use it?
- Key concepts: Cluster, Node, Pod, Deployment, Service
- Real-world analogy to simplify learning

### **Module 2: Setting Up Your Environment**
**Objective:** Set up Kubernetes locally.
- Install Docker Desktop and enable Kubernetes
- Install `kubectl`
- Verify your cluster is working
- Explore `kubectl` basics

### **Module 3: Pods, Deployments, and Services**
**Objective:** Learn how apps run in Kubernetes.
- Run a simple Pod manually
- Use a Deployment for scaling and self-healing
- Create a Service to expose the app

### **Module 4: Deploying a Spring Boot App**
**Objective:** Containerize and run a REST API on Kubernetes.
- Build a simple Kotlin Spring Boot app
- Dockerize the application
- Build and use a local image
- Create Deployment and Service YAML

### **Module 5: Adding MySQL to the Cluster**
**Objective:** Add and connect a database.
- Deploy MySQL with PVC (Persistent Volume Claim)
- Use Secrets for credentials
- Use ConfigMaps for DB connection
- Connect Spring Boot to the MySQL service

### **Module 6: Ingress + HTTPS (TLS)**
**Objective:** Securely expose your app with Ingress.
- Introduction to Ingress
- Installing NGINX Ingress Controller
- TLS Setup
- Creating Ingress Resource
- Testing HTTPS Access

### **Module 7: Scaling and Managing the Cluster**
**Objective:** Learn how to maintain a production-grade cluster.
- Scale applications with replicas
- Use liveness and readiness probes
- Get logs, restart pods, and debug

### **Module 8: Jobs and CronJobs**
**Objective:** Automate batch tasks.
- Create a Spring Boot batch job
- Run a Job
- Schedule tasks with CronJobs
- Export data to CSV using CronJob

---

## 🧪 By the End, You Will Be Able To:

✅ Understand Kubernetes terminology and core architecture  
✅ Deploy full-stack apps using YAML, Secrets, ConfigMaps, and PVC  
✅ Build and run containerized Spring Boot apps  
✅ Expose services through Ingress with HTTPS  
✅ Debug, scale, and manage your app like a pro  
✅ Automate tasks with Jobs and CronJobs  

---
## 📚 Project Modules

Each module builds on the previous to give you hands-on Kubernetes skills.

| Module                                           | Description |
|--------------------------------------------------|-------------|
| [Module 1](./module-1_introduction/README.md)    | Introduction to Kubernetes |
| [Module 2](./module-2_setup-environment/README.md)         | Set Up Local Dev Environment |
| [Module 3](./module-3_pods-deployments-services/README.md) | Pods, Deployments, and Services |
| [Module 4](./module-4_deploy-springboot-app/README.md)     | Deploying a Spring Boot Application |
| [Module 5](./module-5_add-mysql-to-cluster/README.md)      | Add MySQL to the Cluster |
| [Module 6](./module-6_ingress-and-https/README.md)         | Ingress + HTTPS (TLS) |
| [Module 7](./module-7_scaling-and-managing/README.md)      | Scaling and Managing the Cluster |
| [Module 8](./module-8_jobs-and-cronjobs/README.md)         | Running Jobs and CronJobs for Batch Tasks |

---

Happy coding! 🚀
