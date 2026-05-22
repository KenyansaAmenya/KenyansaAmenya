## Hi there I am Felix Amenya Kenyansa 👋

Data scientist | Data Analyst | Machine learning enthusiast | Monitoring and Evaluation

[My portfolio](https://felix-amenya-portfolio.vercel.app/)

## About me
I'm Passionate about Data Science, Analytics, and AI. I build data-driven solutions, uncover insights, and experiment with machine learning to solve real-world problems.
[Limuru, Kenya](https://maps.app.goo.gl/QbARiErBnMpFGsy46)


🛠️ Tech Stack & Expertise
```
tech_stack = {
    "programming": ["Python", "SQL", "Jupyter Notebooks"],
    "visualization": ["Tableau", "Power BI", "Excel", "Matplotlib", "Seaborn"],
    "DataBases": ["MongoDB", "Postgres"],
    "specialties": ["Machine learning", "Data Analytics", "Operational Intelligence", "Data Quality"]
    "streaming": ["Apache Kafka", "Python", "Real-time ETL"],
    "orchestration": ["Apache Airflow"],
    "Frameworks": ["FastAPI", "Flask"]
}
```
## Core Technologies

- Python
- Airflow
- SQL
- Jupyter
- Docker

🚀 Featured Projects 

### [🏥 1. Healthcare AI Prediction System](https://github.com/KenyansaAmenya/healthcare-ml-pipeline.git) 
## [Clinical sanctuary UI](https://clinical-sanctuary-web.vercel.app/)

Built a production-grade ML system to address the lack of real-time healthcare risk prediction. Designed an end-to-end pipeline for ingesting, cleaning, and modeling patient data, with predictions served via a scalable API.

- Tech: FastAPI, Scikit-learn, XGBoost, PostgreSQL
- Achieved automated model training, versioning, and real-time inference
- Learned: End-to-end ML system design, MLOps practices, and deploying scalable AI APIs

### 2. [Lumina learn AI Adaptive learning system](https://github.com/KenyansaAmenya/lumina-learn.git)
## [Lumina learn UI](https://lumina-wheat-ten.vercel.app/)

LuminaLearn is an AI adaptive learning platform focused on improving how students practice and how teachers monitor progress.

It achieves two big outcomes:

## 1. Personalized student learning

- Generates quiz questions dynamically by topic/difficulty.

- Gives instant AI feedback, hints, and explanations after answers.

- Tracks progress, accuracy, and recurring mistakes over time. 

## 2. Actionable teacher analytics

- Provides dashboards for class performance and topic difficulty.

- Surfaces struggling students early.

- Adds AI-generated teaching recommendations based on performance data. 

It combines a FastAPI backend + service/repository architecture + Groq LLM + PostgreSQL/Supabase to power both the student-facing quiz flow and teacher-facing analytics

### 3. [Global energy prices project](https://github.com/KenyansaAmenya/energy-data.git)

This project is an Energy Data Platform where I built a complete pipeline to collect, process, and serve energy price data. It uses Airflow for ETL orchestration, Python for data validation/transformation, MongoDB for storage, and Flask for APIs and dashboard visualization.

## 1. Problems I was trying to solve
- Energy price data was fragmented and difficult to track consistently.

- Raw source data was often inconsistent in format and quality (missing fields, type issues, duplicates).

- There was no easy way to turn raw market data into usable insights for reporting and decision-making.

- Accessing updated information required manual effort, so I needed an automated and repeatable pipeline.

- I wanted one system that supported both backend data engineering workflows and user-facing analytics access.

## 2. What I achieved
- Built an end-to-end workflow: ingest → validate → transform → store → serve.

- Automated data collection from OilPriceAPI and converted it into structured, queryable datasets.

- Implemented quality checks to improve reliability before loading curated collections.

- Created API endpoints and a dashboard to expose insights like latest prices and trend changes.

- Containerized the full stack with Docker for reproducible local development and deployment.

## 3. What I learned
- How to design a production-style ETL architecture with modular pipeline layers.

- Practical implementation of data quality controls (null, type, range, and duplicate checks).

- How to combine batch orchestration (Airflow) with online serving (Flask APIs/dashboard).

- Better practices for scalable Python project structure and MongoDB-backed analytics systems.

### 4. [formula1 race prediction](https://github.com/KenyansaAmenya/formula1-race-prediction-project.git)
## [F1 UI](https://f1-frontend-2wu6.onrender.com/)

# Project Summary

This project is an end-to-end Formula 1 race prediction platform that combines data engineering, machine learning, and full-stack development. I built it to solve the challenge of turning fragmented motorsport data into useful race insights—such as predicting winners, podium finishes, and points outcomes—through a production-style workflow.

## Tech Used
- **Backend:** Python, FastAPI, Pydantic, SQLAlchemy
- **Data/ML:** Pandas, NumPy, scikit-learn, XGBoost
- **Frontend:** React, TypeScript, Vite, TailwindCSS
- **Infra/Ops:** Docker, Docker Compose, Nginx, optional Redis

## Problem I Was Trying to Solve
F1 data is spread across multiple sources and formats, making it difficult to use directly for analysis or prediction. I wanted to build a single pipeline that ingests, cleans, and engineers this data into model-ready features, then serves predictions through an API and dashboard.

## What I Learned
- How to design an end-to-end ML system beyond just model training
- How to structure reliable ingestion and feature pipelines
- How to expose ML predictions via secure, production-style APIs
- How to integrate a modern frontend with backend inference services
- How containerization and testing improve reproducibility and delivery

## What I Achieved
- Built a multi-source F1 ingestion and processing pipeline
- Trained and evaluated models for winner, top-3, and points prediction
- Delivered authenticated prediction endpoints in FastAPI
- Created a React dashboard for race insights and visualization
- Containerized the stack for local and deployment-ready execution

