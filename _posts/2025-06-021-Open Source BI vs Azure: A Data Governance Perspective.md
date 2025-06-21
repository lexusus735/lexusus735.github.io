#---
#title: "Open Source BI vs Azure: A Data Governance Perspective"
#excerpt_separator: "<!--more-->"
#categories:
 # - Blog
#tags:
 # - Post Formats
  #- readability
  #- standard
#---
---
title: "Open Source BI vs Azure: A Data Governance Perspective"
layout: single
classes: wide
author_profile: true
read_time: true
share: true
related: true
tags: [data governance, digital sovereignty, open source BI, azure, final year project, business intelligence, data engineering]
description: "Comparative study on open-source vs Azure-based BI pipelines for digital sovereignty and data governance. Includes hands-on implementation and structured evaluation."
---

## 🎓 Final Year Project: Business Intelligence and Digital Sovereignty

In an era where data is as valuable as currency, **data sovereignty** is emerging as a key concern for organizations across public, private, and nonprofit sectors. For my final-year thesis, I decided to explore a question at the intersection of technology, governance, and ethics:

> _Can open-source BI tools rival cloud-native solutions like Microsoft Azure when it comes to functionality, while offering stronger control, transparency, and sovereignty over data infrastructure?_

This post documents the journey, architecture, insights, and technical details of the comparative project I built—an evaluation of **two full BI pipelines**, one built on open-source technologies, the other entirely on Microsoft Azure.

---

## 🔍 Motivation

As cloud vendors increasingly dominate enterprise data stacks, questions of **vendor lock-in, compliance**, and **jurisdictional control** over data are no longer theoretical. For governments, NGOs, and data-sensitive industries, reliance on proprietary platforms introduces long-term risks.

My project aims to investigate:

- The **technical viability** of open-source alternatives
- The **real-world trade-offs** in governance, UX, and performance
- How sovereignty principles can guide modern BI architecture

---

## 🛠️ What I Built: Two Competing BI Pipelines

I built and deployed **two parallel BI pipelines** to compare head-to-head:

### 1. **Open Source BI Stack**

- **Airbyte** – Data ingestion from CSVs and cloud APIs  
- **Apache Spark (PySpark)** – Processing and transformation  
- **PostgreSQL** – Structured storage  
- **RStudio + Shiny** – Visual analytics dashboard  
- **OpenMetadata** (optional) – Metadata and governance  
- **Docker Compose** – Local orchestration and portability  
- **Nextcloud** – Secure file collaboration

### 2. **Azure Cloud-Native BI Stack**

- **Azure Data Factory** – ETL workflows  
- **Data Lake Gen2** – Distributed storage  
- **Azure Databricks** – Processing layer  
- **Power BI** – Visualization and reporting  
- **Azure Purview** – Data catalog and governance  
- **SharePoint** – Document and dashboard hosting

Each pipeline was fully deployed, with workflows created from data ingestion to final reporting and metadata management.

---

## ⚖️ Evaluation Framework

I designed a **structured evaluation matrix** based on:

- **11 governance dimensions** from the **DAMA DMBOK2** model
- **3 sovereignty layers**: 
  - Physical (Infrastructure control)
  - Logical (Codebase access)
  - Legal (Data ownership & jurisdiction)
- **3 technical performance metrics**:
  - Scalability
  - User Experience
  - Documentation & Support

Each criterion was scored on a 1–5 scale for both stacks.

---

## 📊 Key Findings

| Criteria                     | Open Source Score | Azure Score | Insights |
|-----------------------------|-------------------|-------------|----------|
| Data Governance             | 4                 | 3           | OpenMetadata offers more transparency |
| Metadata Management         | 4                 | 4           | Both strong; open-source more customizable |
| Infrastructure Sovereignty  | **5**             | **2**       | Full hosting control in open source |
| Codebase Control            | **5**             | **2**       | OSS allows modification and transparency |
| Data Ownership              | **5**             | **3**       | Data stays local in OSS stack |
| Security & Access Control   | 3                 | 4           | Azure wins on IAM and enterprise security |
| Scalability & Performance   | 3                 | **5**       | Azure offers elasticity and auto-scaling |
| UI & Collaboration          | 3                 | 4           | Azure has polished enterprise UX |
| Documentation & Support     | 3                 | **5**       | Azure provides enterprise-grade support |

---

## ✅ Results & Takeaways

- **Open-source BI solutions are viable** for organizations prioritizing autonomy, transparency, and legal control over their data infrastructure.
- However, they **require more manual configuration, integration effort, and long-term maintenance**.
- Azure and similar platforms **excel in user experience, scalability, and enterprise integration**—but pose strategic risks in terms of data jurisdiction and vendor dependence.

> This project affirmed that **technical sovereignty is achievable**, but it requires a clear understanding of trade-offs and a strong internal capacity to maintain open-source infrastructure.

---

## 📁 Project Artifacts

- ✅ Full code for open-source deployment (Docker Compose, Spark jobs, Shiny app)
- 📘 Evaluation matrix based on DAMA DMBOK2
- 📊 Architecture diagrams and performance logs
- 🧾 [Thesis PDF download](#) (add your file link here)

All artifacts are available in [my GitHub repository](https://github.com/yourusername/your-repo-name).

---

## 💡 Skills Demonstrated

- Data Engineering (ETL, transformation, orchestration)
- Cloud Architecture (Azure DevOps, Databricks, Data Factory)
- Data Governance & Security (Purview, OpenMetadata)
- Open Source BI (R, Shiny, PostgreSQL, Spark)
- Research Methodology & Technical Writing

---

## 💬 Final Thoughts

This project was both a **technical challenge** and an **ethical exploration** of how we build data infrastructure in a globalized, surveillance-aware world.

If you're a data team or hiring manager looking for someone with hands-on experience in **governance-conscious data platforms**, **open-source tooling**, and **enterprise-grade architecture**, I’d love to connect.

---

## 📫 Get in Touch

Feel free to reach out on [LinkedIn](https://linkedin.com/in/your-profile) or explore more of my work [on GitHub](https://github.com/yourusername).

---

