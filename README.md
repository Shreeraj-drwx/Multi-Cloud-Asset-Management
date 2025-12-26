# 🌐 Multi-Cloud Asset Management

![Java](https://img.shields.io/badge/Java-17+-orange?style=flat-square&logo=openjdk)
![Maven](https://img.shields.io/badge/Maven-Build-blue?style=flat-square&logo=apachemaven)
![Azure](https://img.shields.io/badge/Azure-Cloud-0089D6?style=flat-square&logo=microsoftazure)
![Google Cloud](https://img.shields.io/badge/GCP-Cloud-4285F4?style=flat-square&logo=googlecloud)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql)
![Tomcat](https://img.shields.io/badge/Tomcat-Server-F8DC75?style=flat-square&logo=apachetomcat)

A unified web application for discovering, managing, and synchronizing cloud assets across multiple cloud providers from a single dashboard.

---

## 📌 Overview

Multi-Cloud Asset Management centralizes cloud infrastructure visibility by fetching and normalizing assets from different cloud providers such as **Microsoft Azure** and **Google Cloud Platform**.  
It provides a single source of truth for cloud resources and serves as a foundation for security analysis and monitoring.

---

## ✨ Features

- ☁️ Multi-cloud virtual machine discovery (Azure & GCP)
- 🔐 Secure storage and automatic loading of cloud credentials
- 🔄 Automatic synchronization between live cloud assets and database records
- 🧩 Unified VM resource model across providers
- 📊 Centralized portfolio/dashboard view
- 🛡️ Designed for future security and compliance integrations

---

## 🏗️ Tech Stack

- **Backend:** Java (Servlets, JSP)
- **Build Tool:** Maven (WAR packaging)
- **Database:** MySQL
- **Cloud APIs:** Azure Management APIs, Google Cloud Compute APIs
- **Server:** Apache Tomcat

---

## ⚙️ Setup

```bash
git clone https://github.com/Shreeraj-drwx/Multi-Cloud-Asset-Management.git
cd Multi-Cloud-Asset-Management
mvn clean package
