---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## [Profile]({{ base_path }}/)
Machine Learning Researcher and Engineer designing and evaluating AI solutions for enterprise environments. My work includes NLP-based query automation, LLM optimization initiatives to improve efficiency and reduce operational costs, along with building RAG and knowledge-guided NLP systems.
Currently, my research is focused at the intersection of LLM Interpretability and AI Safety, including jailbreaking LLMs and specifically understanding why models behave unsafely, so we can make them more trustworthy. I aim to develop intelligent and reliable systems translating AI capabilities into real-world business impact.

## Professional Experience 
* **Standard Chartered**
  * **Machine Learning Engineer** (Sept 2026. - Present)
  * **Analyst, Development - Finance** (Sept 2025 - Sept 2026)
    * Designed and developed a Natural Language-to-SQL (NL2SQL) on SAP HANA Cloud as part of an apprenticeship program, enabling business users to generate ad-hoc queries through natural language, reducing query turnaround time from 1–2 days to a few hours, and proposing a DistilBERT-based query routing layer to optimize LLM utilization.
    * Implemented a metadata vectorization layer using SAP's native NLP embedding model, enabling semantic mapping of user intent to database schema columns via cosine similarity ranking.
    * Built dynamic SQL generation pipelines utilizing SQLScript stored procedures, allowing runtime query construction and execution.
    * Evaluated scalable Text to SQL architectures incorporating LLMs via SAP AI Core for enterprise-grade query automation deployment.
    * Coordinated release management for 10+ deployments and created data transformation procedures for dimensional restatement in Financial Reporting.
    * Developed a Retail & Wealth tool banking application prototype utilizing React, Spring Boot, and PostgreSQL.
  
## Publications & Projects
* [**Weaving Stories: using LLMs to generate historical narratives**](/files/Weaving_Stories_FinalReport.pdf) (Feb 2025 - July 2025)
  * *Engineered a Beyond-Vanilla RAG system using a custom Knowledge Graph (NetworkX/GML) and Hybrid Semantic Search (FAISS) to enable multi-hop reasoning over historical narratives.*
  * *Developed sophisticated Memory Orchestration pipelines including entity-centric query expansion and NLP-driven topic extraction to provide high-quality, long-context awareness to Gemini 1.5 Pro.*
  * *Optimized the intersection of Structured Memory (Knowledge Graphs) and Unstructured Data to improve narrative faithfulness and reduce hallucinations in streaming LLM environments.*

* **Parkinson's Disease Diagnosis from Patients Speech Analysis (IEEE)** (Oct 2023 - Dec 2023)
  * *Achieved 95% diagnostic accuracy using Random Forest and XGBoost, utilizing SHAP to identify the top 6 most influential features.*
* **Deep Learning-Based Analysis of Pediatric Pneumonia Detection in Children using Fine-tuned NasNetMobile Model (IEEE)** (Mar 2024 - May 2024)
  * *Achieved a 92% F-score in pediatric pneumonia detection by fine-tuning a NasNetMobile CNN architecture with Mish activation on a dataset of over 5,000 chest X-rays.*

* **Comparative Image Analysis of Chest X-RAY Image Encryption using Symmetric and Asymmetric Key Encryption Algorithms (IEEE)** (Mar 2024 - May 2024)
  * *Identified AES with RSA as the optimal multilayer encryption strategy for medical images, delivering the best decryption speed while guaranteeing Confidentiality, Integrity, and Authentication (CIA).*

*(For a detailed view of my work, please visit my [Publications]({{ base_path }}/publications/) page.)*

## Technical Skills
* **Core:** Data Structures & Algorithms, Software Engineering, Agile Software Development
* **AI/ML:** Machine Learning, Deep Learning, NLP, RAG Systems
* **Languages:** Java, Python, C++, C
* **Tools/Tech:** TensorFlow, SQL

## Education
* **B.Tech in Computer Science and Engineering** (Sept 2021 - July 2025)
  * **Amrita Vishwa Vidyapeetham University**
    * CGPA: 8.65, First Class with Distinction.
* **Exchange Program** (Feb 2025 - July 2025)
  * *University of Twente*
    * Conducted research on utilizing Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) to generate engaging historical narratives.
    * Evaluated Semantic, Hybrid, and Graph-Based RAG approaches to optimize narrative coherence and mitigate hallucinations.

## Leadership & Experience
* **Toastmasters International**
  * **Area G3 Director** (July 2024 - June 2025)
    * Served five corporate clubs with ~130 professionals and leaders across the industry.
    * Achieved 100% club retention, and Select Distinguished Status.
  * Organized Feb 2024 Leadership Conclave with a team of four, over the course of three months, securing a keynote address and two executive-led panel discussions in a corporate venue. (2023-24)
  * Revitalized an underperforming club through targeted strategic planning. (2023-24)


<br>
<hr>

<div style="text-align: center; margin-top: 40px; margin-bottom: 20px;">
  <a href="#" onclick="window.print();return false;" class="btn btn--info" id="download-btn">
    <i class="fas fa-file-pdf"></i> Download CV
  </a>
</div>

<style>
  @media print {
    #download-btn, .sidebar, .masthead, .page__footer, .author__urls-wrapper {
      display: none !important;
    }
    
    .page__content, .archive, .page__inner-wrap {
      width: 100% !important;
      max-width: 100% !important;
      margin: 0 !important;
      float: none !important;
      padding: 0 !important;
    }

    a[href]::after {
      content: "" !important;
    }

    body {
      font-size: 11pt !important;
      line-height: 1.3 !important;
    }
    h2 {
      margin-top: 15px !important;
      margin-bottom: 5px !important;
      padding-bottom: 2px !important;
      border-bottom: 1px solid #ccc;
    }
    p, ul {
      margin-bottom: 10px !important;
    }
    li {
      margin-bottom: 3px !important;
      page-break-inside: avoid; 
    }
    h2, h3 {
      page-break-after: avoid !important;
    }
  }
</style>