<h1 align="center">Hi, I'm Pranjal Mahajan 👋</h1>
<h3 align="center">Data Engineer & AI Engineer · Building reliable data pipelines and production AI systems</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/pranjal-mahajan-4910b2232/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:pranjalm1203@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Boston,%20MA-555555?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

---

## About Me

I'm an M.S. Information Systems student at **Northeastern University** (graduating **December 2026**) who loves turning messy, real-world data into systems people can trust.

- Built a **production multi-agent AI co-pilot** for the cardiac operating room at **Brigham and Women's Hospital / Harvard Medical School**
- Built ETL pipelines and data models over **10M+ records**, cutting processing time by **60%**
- **Graduate Teaching Assistant** for Program Structures & Algorithms at Northeastern
- **AWS Certified AI Practitioner**
- **Open to full-time Data Engineering and AI Engineering roles starting January 2027**

---

## Experience

**Research AI Intern** · Brigham and Women's Hospital / Harvard Medical School, Division of Cardiac Surgery · *Jan 2025 – Apr 2025*
- Engineered **CardiacGPT**, a voice-driven multi-agent co-pilot with 3 role-specific agents (Anesthesia, Surgeon, Perfusionist) built on LangGraph, the Claude API, and ChromaDB RAG over 1K+ clinical embeddings, returning dosing guidance in **under 3 seconds**
- Designed for reliability: **source citations** on every answer, automatic retries, a safe **"insufficient evidence"** fallback, and **clinician review** of outputs
- Shipped the production backend on **FastAPI, PostgreSQL, and WebSockets** with a **HIPAA-grade PHI de-identification layer**
- Co-built **Xaion**, an on-prem LLM platform that extracted structured data from **700 unstructured clinical documents**

**Data Analyst** · Apex Industries · *Jan 2024 – Aug 2024*
- Built ETL pipelines and dimensional models over **10M+ records**, reducing processing time by **60%**
- Optimized SQL queries for a **40%** performance gain across 5+ teams, and built Tableau dashboards for self-service analytics

**Graduate Teaching Assistant** · Northeastern University · *Sep 2026 – Present*
- Run weekly sessions for **20+ students** on data structures, dynamic programming, and graph algorithms

---

## Featured Projects

###[AI Generated Travel Itinerary](https://github.com/Pranjal125/AI-Generated-Travel-Itinerary-)
**Problem:** Planning trips means pulling scattered data from many sites.
**Built:** 3+ Apache Airflow pipelines with dbt transformations that ingest and normalize **10,000+ records** from TripHobo, IHG, and YouTube into Snowflake and Pinecone, feeding a CrewAI multi-agent system that generates personalized itineraries for 6 U.S. cities.
**Shipped:** Dockerized on GCP Cloud Run, with Airflow on Compute Engine and CI/CD through GitHub Actions.
`Airflow` `dbt` `Snowflake` `Pinecone` `CrewAI` `FastAPI` `Docker` `GCP` `GitHub Actions`

### [LA Crime Analysis Pipeline](https://github.com/Pranjal125/LA_crime_analysis)
**Built:** An end-to-end Databricks pipeline modeling **900K+ crime records** with Delta Live Tables and medallion architecture (Bronze → Silver → Gold), Kimball fact and dimension tables, and automated data quality checks with schema-evolution handling.
`Databricks` `Delta Live Tables` `Delta Lake` `PySpark` `Spark SQL` `Tableau`

### AI-Powered RAG Pipeline: [Part 1](https://github.com/Pranjal125/AI-Powered-Retrieval-Augmented-Generation-RAG-Pipeline-Development-Part-1) · [Part 2](https://github.com/Pranjal125/AI-Powered-Retrieval-Augmented-Generation-RAG-Pipeline-Development-Part-2)
**Problem:** Answering questions across years of dense financial reports.
**Built:** An agentic RAG system over **5 years of NVIDIA quarterly reports**, comparing 3 PDF parsers (pymupdf, Docling, Mistral OCR) and 3 chunking strategies (recursive, token, semantic) across Pinecone and ChromaDB, orchestrated by a LangGraph multi-agent system with Snowflake and web search.
`LangGraph` `Pinecone` `ChromaDB` `Snowflake` `Airflow` `Streamlit` `FastAPI`

### [Food Establishment Inspections](https://github.com/Pranjal125/Food_Establishment_Inspections)
**Problem:** Every city records inspection data differently.
**Built:** Databricks ETL over **100K+ records** that unifies disparate city schemas into a star schema with SCD Type 2, with source-to-target mapping documentation and Power BI dashboards by risk, violation, and location.
`Databricks` `Python` `SQL` `SCD Type 2` `Power BI`

### [IMDb Movie Profiling and Analytics](https://github.com/Pranjal125/IMDb_Movie_Profiling_and_Analytics)
**Built:** An Azure Data Factory pipeline with medallion architecture that profiles, cleans, and models **200M+ IMDb records**, plus Power BI dashboards with DAX measures for YoY growth, weighted ratings, and Top N rankings.
`Azure Data Factory` `Snowflake` `Power BI` `DAX`

<!-- Add the Incremental Data Pipeline project here once its description is ready -->

---

## Tech Stack

**Languages:** Python · SQL · Java · R

**Data Engineering:** Apache Airflow · dbt · Databricks · Apache Spark (PySpark, Spark SQL) · Delta Lake · Azure Data Factory · Alteryx

**Databases & Warehouses:** Snowflake · BigQuery · PostgreSQL · Oracle SQL · ChromaDB · Pinecone

**AI & LLMs:** LangGraph · LangChain · CrewAI · Claude API · Ollama · RAG · FastAPI · Streamlit

**Cloud & DevOps:** AWS · GCP · Azure · Docker · GitHub Actions · Jenkins · Git · Linux

**BI & Modeling:** Power BI · Tableau · Star Schema · Kimball · SCD Type 2 · Medallion Architecture

---

<p align="center"><i>Always happy to talk about data pipelines, AI agents, or anything in between, so feel free to reach out!</i></p>
