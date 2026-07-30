<div align="center">

# Muhammad Zaenal Abidin Abdurrahman

**Data Science • Applied Machine Learning • Analytics • AI/Data & IoT Systems**

Telecommunication Engineering student at **Telkom University**<br>
Building practical systems across **machine learning, analytics, APIs, telemetry, and operational workflows**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-zendin1102-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zendin1102/)
[![Email](https://img.shields.io/badge/Email-zendin.work%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:zendin.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Zendin110206-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Zendin110206)

<p>
  <img height="165" src="https://streak-stats.demolab.com?user=Zendin110206&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>

</div>

---

## Profile

I use this GitHub profile as a curated portfolio of projects I am building while growing across data science, applied machine learning, analytics, and practical AI/data and IoT systems.

My strongest interest is turning data into useful technical outputs: analysis that explains a problem, models that are evaluated honestly, APIs or telemetry pipelines that make the result usable, and documentation that makes the scope clear.

The portfolio is intentionally broad enough for data science, data analyst/product analyst, AI intern, and applied ML opportunities, while still giving stronger emphasis to projects that connect analysis or modeling with usable workflows.

My current focus is [FTM - Fuel Tank Management](https://github.com/Zendin110206/solar-tank-monitoring-system), an ongoing operational IoT system in active field use within a limited pilot during my practical internship with PT Telkom Infrastruktur Indonesia (TIF/InfraNexia). Registered field devices send live fuel-tank telemetry into a monitored data pipeline that supports operational users with visibility, device management, and support workflows. Additional devices are now being prepared for controlled, needs-based expansion.

I am still developing my depth in this field, so I keep each project clear about its scope, limitations, ownership, and what it is meant to demonstrate.

---

## Long-Term Direction

| Direction                         | What I am trying to build                                                                |
| --------------------------------- | ---------------------------------------------------------------------------------------- |
| Data science workflows            | EDA, feature engineering, model evaluation, segmentation, and business-facing explanation |
| Applied ML systems                | ML prototypes that can be served through APIs, connected to apps, and explained clearly  |
| Analytics and decision tools      | SQL/Python analysis, KPI thinking, dashboards, and decision-support outputs              |
| AI/data integration               | Practical AI or data features connected to product flows and backend services            |
| Telco, IoT, and operational data  | Telemetry, monitoring, forecasting, and anomaly analysis for field and network operations |

---

## Featured Portfolio

### [FTM - Fuel Tank Management](https://github.com/Zendin110206/solar-tank-monitoring-system)

Ongoing operational IoT system in active field use within a limited pilot during my practical internship with PT Telkom Infrastruktur Indonesia (TIF/InfraNexia). Registered ESP8266 devices connected to ultrasonic sensors send live fuel-tank telemetry through an authenticated Next.js ingestion service into Aiven MySQL, supporting operational monitoring for users and admins, device provisioning, CSV export, Telegram, and helpdesk workflows.

**My contribution:** project coordination; application architecture; server-side and database work; identity and device workflows; deployment; integration; testing; review; and documentation, in collaboration with field/device/firmware and UI/UX contributors.

**Verified pilot snapshot (13-14 July 2026):** 6 registered locations, 6 tanks, and 6 physical devices; 191.954 telemetry readings; 3 devices reporting fresh data and 3 requiring follow-up. Live views use the latest per-device snapshot, while 5-minute historical rollups reduce row growth by about 15x versus storing every 20-second reading.

**Quality snapshot (16 July 2026):** TypeScript typecheck, ESLint, all 160 automated tests, and the Next.js production build passed on the current main branch.

**Shows:** operational data systems, IoT telemetry ingestion, full-stack architecture, MySQL data lifecycle, authentication and provisioning, field collaboration, CI, and public-safe technical documentation

**Stack:** `Next.js 16` `React 19` `TypeScript` `MySQL` `ESP8266` `Telegram Bot API` `Vercel` `Vitest`

**Status and scope:** In active operational use within a limited field pilot; not a nationally deployed or fully production-hardened corporate system. Additional devices are being prepared for controlled expansion, while the repository remains ongoing beyond the internship period through security, calibration, alerting, recovery, access control, observability, and operational analytics work.

**Links:** [Live application](https://solar-tank-monitoring-system.vercel.app) · [Operational status](https://github.com/Zendin110206/solar-tank-monitoring-system/blob/main/docs/current-operational-truth.md) · [Architecture](https://github.com/Zendin110206/solar-tank-monitoring-system/blob/main/docs/architecture.md)

---

### [KoopCare MLOps Credit Scoring API](https://github.com/Zendin110206/koopcare-mlops-credit-scoring-api)

FastAPI-based ML inference service for a cooperative financing decision-support prototype. It loads an XGBoost model artifact, applies the saved preprocessing flow, returns probability/risk information, and keeps the final financing decision under human review.

**Shows:** ML API design, inference workflow, preprocessing parity, response schema design, model documentation, human-in-the-loop decision support

**Stack:** `Python` `FastAPI` `XGBoost` `scikit-learn` `Pydantic` `Model Card`

**Scope:** Prototype using public/Home Credit-style data, not a production credit decisioning system.

---

### [KoopCare Fullstack Demo Platform](https://github.com/Zendin110206/koopcare-fullstack-demo-platform)

Fullstack demo platform that connects a member financing application flow with ML-assisted review. It includes application intake, backend validation, status lookup, admin review queue, scoring, rescoring, and decision workflow.

**Shows:** fullstack product flow, backend-to-ML API integration, admin/user workflow design, AI as decision support

**Stack:** `React` `Vite` `TypeScript` `Express` `REST API` `ML Integration`

**Scope:** Portfolio demo for workflow integration, not a production financial platform.

---

### [Telco KPI MLOps Platform](https://github.com/Zendin110206/telco-kpi-mlops-platform)

Telecom-focused data and ML prototype for KPI forecasting and anomaly candidate detection using public anonymized operator time-series data. This is the project that most directly connects my telecom background with applied ML.

**Shows:** time-series forecasting, residual-based anomaly scoring, canonical data loading, model documentation, telco analytics direction

**Stack:** `Python` `PostgreSQL` `FastAPI` `Docker` `SARIMA` `Time Series`

**Scope:** Prototype for portfolio and learning use, not a production NWDAF, IDS, or private operator monitoring platform.

---

### [BookFlix - End-to-End Book Recommendation System](https://github.com/Zendin110206/End-to-End-Book-Recommendation-System)

Collaborative filtering book recommender with a modular ML pipeline, KNN-based recommendation logic, Streamlit interface, and Docker support. It is structured beyond a notebook-only workflow.

**Shows:** recommender system fundamentals, data pipeline structure, model serialization, Streamlit inference app, deployment-aware organization

**Stack:** `Python` `Pandas` `scikit-learn` `KNN` `Streamlit` `Docker`

---

### [IMV Customer Segmentation with K-Means](https://github.com/Zendin110206/imv-customer-segmentation-kmeans)

Customer segmentation project using the Olist Brazilian E-Commerce Public Dataset. It turns raw relational e-commerce tables into customer-level behavioral features, evaluates K-Means cluster options, and explains the final customer segments in business-friendly language.

**Shows:** customer analytics, raw data audit, customer-level feature engineering, clustering evaluation, segment profiling, business interpretation

**Stack:** `Python` `Pandas` `NumPy` `scikit-learn` `K-Means` `Matplotlib` `Seaborn`

**Scope:** Individual machine learning assignment using public anonymized e-commerce data, not production customer labels.

---

### [HackerRank SQL Certification Prep](https://github.com/Zendin110206/hackerrank-sql-certification-prep)

Structured SQL certification and interview-readiness portfolio with 57 documented accepted practice solutions across Basic, Intermediate, and Advanced tracks. It includes challenge tracking, concept notes, a SQL style guide, practice logs, and verified HackerRank SQL Basic, Intermediate, and Advanced certificates.

**Shows:** SQL fluency, joins and aggregation, CTE/subquery reasoning, query documentation, certification discipline, data foundation for ML and analytics work

**Stack:** `SQL` `MySQL-style Queries` `CTE` `Joins` `Aggregation` `Documentation`

**Credentials:** [SQL Basic](https://www.hackerrank.com/certificates/86438a7fe347) · [SQL Intermediate](https://www.hackerrank.com/certificates/8c305d999682) · [SQL Advanced](https://www.hackerrank.com/certificates/fae5f9081831)

**Scope:** Public-safe practice and certification evidence, not live certification assessment content.

---

### [HR Analytics SQL + Power BI](https://github.com/Zendin110206/hr-analytics-sql-powerbi)

Analytics dashboard project for employee attrition exploration and intervention prioritization. It uses SQL-based preparation and Power BI reporting to move from descriptive analysis toward action-oriented analytics.

**Shows:** SQL data preparation, BI dashboard storytelling, KPI design, rule-based risk framework, business-facing analytics

**Stack:** `SQL Server` `Power BI` `DAX` `Data Cleaning` `KPI Design`

**Scope:** The risk score is rule-based prioritization, not a validated predictive ML model.

---

### ML Foundations and AI Learning Portfolio

A combined learning track that supports the applied projects above: math notes, ML derivations, from-scratch implementation, structured AI development assignments, 21-project Python practice with tests/linting, SQL certification practice, database practice, and NLP/RAG exercises.

**Shows:** mathematical intuition, structured learning discipline, Python/SQL fluency, notebook-based ML practice, testable small-program implementation, and gradual preparation for applied ML work

**Related:** [ML Path to Mastery](https://github.com/Zendin110206/ml-path-to-mastery), [ML Hands-On Learning Lab](https://github.com/Zendin110206/ml-hands-on-learning-lab), [AI Development B10 Learning Portfolio](https://github.com/Zendin110206/tugas_python_ai_b10), [Python Projects Learning Portfolio](https://github.com/Zendin110206/python-projects-learning-portfolio), [HackerRank SQL Certification Prep](https://github.com/Zendin110206/hackerrank-sql-certification-prep), [Linear Regression from Scratch](https://github.com/Zendin110206/linear-regression-scratch-python), [NLP with HF Transformers](https://github.com/Zendin110206/NLP_with_HF_Transformers), [RAG Parameter Exploration](https://github.com/Zendin110206/tugas-rag-nlp)

---

## Project Map

### Core Portfolio

| Area               | Project                                                                                                  | Short Description                                                                                      |
| ------------------ | -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Operational IoT    | [FTM - Fuel Tank Management](https://github.com/Zendin110206/solar-tank-monitoring-system)              | Ongoing field pilot connecting fuel-tank telemetry, MySQL, device operations, dashboards, and Telegram |
| ML API             | [KoopCare MLOps Credit Scoring API](https://github.com/Zendin110206/koopcare-mlops-credit-scoring-api)   | ML inference API for credit-scoring decision support with documented limitations                       |
| ML + Product       | [KoopCare Fullstack Demo](https://github.com/Zendin110206/koopcare-fullstack-demo-platform)              | Fullstack workflow connecting financing applications with ML-assisted review                           |
| Telco ML           | [Telco KPI MLOps Platform](https://github.com/Zendin110206/telco-kpi-mlops-platform)                     | Forecasting and anomaly candidate detection for telecom KPI time-series data                           |
| Recommender System | [BookFlix](https://github.com/Zendin110206/End-to-End-Book-Recommendation-System)                        | End-to-end collaborative filtering app with Streamlit and Docker                                       |
| Customer ML        | [IMV Customer Segmentation](https://github.com/Zendin110206/imv-customer-segmentation-kmeans)            | K-Means segmentation on Olist e-commerce customer behavior with business interpretation                |
| Data Foundations   | [HackerRank SQL Certification Prep](https://github.com/Zendin110206/hackerrank-sql-certification-prep)   | 57 accepted SQL practice solutions with verified SQL Basic, Intermediate, and Advanced certificates    |
| ML Foundations     | [Linear Regression from Scratch](https://github.com/Zendin110206/linear-regression-scratch-python)       | NumPy implementation of linear regression, MSE, and gradient descent                                   |
| Learning Log       | [ML Path to Mastery](https://github.com/Zendin110206/ml-path-to-mastery)                                 | Long-term math and ML foundation notes for applied machine learning                                    |
| ML Practice        | [ML Hands-On Learning Lab](https://github.com/Zendin110206/ml-hands-on-learning-lab)                     | Problem-first practice for EDA, preprocessing, model evaluation, and explain-back learning             |
| AI Learning        | [AI Development B10 Learning Portfolio](https://github.com/Zendin110206/tugas_python_ai_b10)             | Structured Python, SQL, ML, deep learning, NLP, RAG, and practice archive                              |
| Python Practice    | [Python Projects Learning Portfolio](https://github.com/Zendin110206/python-projects-learning-portfolio) | 21-project Python practice portfolio with documentation, automated checks, linting, and GitHub Actions |
| Business Analytics | [HR Analytics SQL + Power BI](https://github.com/Zendin110206/hr-analytics-sql-powerbi)                  | Attrition analytics dashboard with SQL preparation and action-oriented BI                              |
| Business Analytics | [Hotel Revenue Analysis](https://github.com/Zendin110206/PowerBI_SQL_Hotel_Analysis)                     | SQL Server and Power BI analysis of hotel revenue, seasonality, and parking demand                     |
| Business Analytics | [Retail Shop Analysis](https://github.com/Zendin110206/retail-shop-analysis-mysql)                       | MySQL and Power BI workflow for retail sales and operational KPI analysis                              |
| Customer Analytics | [Online Retail Segmentation](https://github.com/Zendin110206/online-retail-customer-segmentation)        | RFM analysis and K-Means clustering for customer segmentation                                          |
| SQL Practice       | [COVID Data Exploration](https://github.com/Zendin110206/covid-data-exploration-sql)                     | SQL exploration using joins, CTEs, window functions, temp tables, and Tableau-ready views              |
| SQL Practice       | [Nashville Housing Cleaning](https://github.com/Zendin110206/sql-data-cleaning-nashville)                | Practical SQL data cleaning with date standardization, parsing, and deduplication                      |

<details>
<summary><strong>Full repository map</strong></summary>

| Group                | Repository                                                                                                                         | Notes                                                                                                            |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Profile              | [Zendin110206](https://github.com/Zendin110206/Zendin110206)                                                                       | This GitHub profile README                                                                                       |
| Operational IoT      | [solar-tank-monitoring-system](https://github.com/Zendin110206/solar-tank-monitoring-system)                                       | Active limited FTM pilot for telemetry, device provisioning, monitoring, Telegram, and operational workflows    |
| Flagship ML/API      | [koopcare-mlops-credit-scoring-api](https://github.com/Zendin110206/koopcare-mlops-credit-scoring-api)                             | FastAPI + XGBoost decision-support inference API                                                                 |
| Flagship ML/Product  | [koopcare-fullstack-demo-platform](https://github.com/Zendin110206/koopcare-fullstack-demo-platform)                               | Fullstack financing workflow demo integrated with ML scoring                                                     |
| Flagship Telco       | [telco-kpi-mlops-platform](https://github.com/Zendin110206/telco-kpi-mlops-platform)                                               | Telco KPI forecasting and anomaly candidate detection prototype                                                  |
| Flagship Recommender | [End-to-End-Book-Recommendation-System](https://github.com/Zendin110206/End-to-End-Book-Recommendation-System)                     | BookFlix collaborative filtering app with Streamlit and Docker                                                   |
| Analytics            | [hr-analytics-sql-powerbi](https://github.com/Zendin110206/hr-analytics-sql-powerbi)                                               | HR attrition analytics dashboard with SQL and Power BI                                                           |
| Analytics            | [PowerBI_SQL_Hotel_Analysis](https://github.com/Zendin110206/PowerBI_SQL_Hotel_Analysis)                                           | Hotel revenue analysis with SQL Server and Power BI                                                              |
| Analytics            | [retail-shop-analysis-mysql](https://github.com/Zendin110206/retail-shop-analysis-mysql)                                           | Retail sales analysis using MySQL and Power BI                                                                   |
| Analytics            | [imv-customer-segmentation-kmeans](https://github.com/Zendin110206/imv-customer-segmentation-kmeans)                               | Olist customer segmentation with K-Means, feature engineering, clustering metrics, and segment interpretation    |
| Analytics            | [online-retail-customer-segmentation](https://github.com/Zendin110206/online-retail-customer-segmentation)                         | RFM analysis and K-Means customer segmentation                                                                   |
| Analytics            | [indonesia-market-expansion-intelligence](https://github.com/Zendin110206/indonesia-market-expansion-intelligence)                 | In-progress public-data market expansion intelligence project                                                    |
| SQL Foundations      | [hackerrank-sql-certification-prep](https://github.com/Zendin110206/hackerrank-sql-certification-prep)                             | SQL certification prep with 57 accepted Basic/Intermediate/Advanced practice solutions and verified certificates |
| SQL Foundations      | [covid-data-exploration-sql](https://github.com/Zendin110206/covid-data-exploration-sql)                                           | SQL exploration and Tableau-ready COVID data views                                                               |
| SQL Foundations      | [sql-data-cleaning-nashville](https://github.com/Zendin110206/sql-data-cleaning-nashville)                                         | SQL data cleaning, parsing, standardization, and deduplication                                                   |
| ML Foundations       | [linear-regression-scratch-python](https://github.com/Zendin110206/linear-regression-scratch-python)                               | Linear regression implemented from first principles in NumPy                                                     |
| ML Foundations       | [ml-path-to-mastery](https://github.com/Zendin110206/ml-path-to-mastery)                                                           | Math and ML foundation notes for long-term applied ML preparation                                                |
| ML Practice          | [ml-hands-on-learning-lab](https://github.com/Zendin110206/ml-hands-on-learning-lab)                                               | Problem-first learning lab for EDA, preprocessing, model evaluation, and applied ML practice                    |
| ML Practice          | [titanic-survival-prediction](https://github.com/Zendin110206/titanic-survival-prediction)                                         | Kaggle Titanic classification practice with feature engineering                                                  |
| AI Learning          | [tugas_python_ai_b10](https://github.com/Zendin110206/tugas_python_ai_b10)                                                         | Structured Python, SQL, ML, deep learning, NLP, and RAG learning archive                                         |
| Python Practice      | [python-projects-learning-portfolio](https://github.com/Zendin110206/python-projects-learning-portfolio)                           | 21 small Python projects for fundamentals, CLI apps, tests, Ruff linting, and CI practice                        |
| NLP/RAG              | [NLP_with_HF_Transformers](https://github.com/Zendin110206/NLP_with_HF_Transformers)                                               | Hugging Face Transformers practice for common NLP tasks                                                          |
| NLP/RAG              | [tugas-rag-nlp](https://github.com/Zendin110206/tugas-rag-nlp)                                                                     | RAG parameter exploration with chunking, retrieval, reranking, and generation settings                           |
| NLP/Recommender      | [semantic-book-recommender](https://github.com/Zendin110206/semantic-book-recommender)                                             | In-development semantic book recommender                                                                         |
| AI-Agent Experiment  | [semantic-book-recommender-codex-agent-benchmark](https://github.com/Zendin110206/semantic-book-recommender-codex-agent-benchmark) | AI-agent benchmark experiment, not positioned as primary personal coding proof                                   |
| Product/Team Context | [Daskomku](https://github.com/Zendin110206/Daskomku)                                                                               | Internal recruitment workflow platform for lab candidate operations                                              |
| Product/Team Context | [daskomrec25](https://github.com/Zendin110206/daskomrec25)                                                                         | Team/fork recruitment platform context                                                                           |
| Product/Team Context | [flocify-app](https://github.com/Zendin110206/flocify-app)                                                                         | Flutter/Firebase aquaculture app prototype from earlier product exploration                                      |
| Product/Team Context | [flocify-timeline](https://github.com/Zendin110206/flocify-timeline)                                                               | Internal project timeline/dashboard prototype                                                                    |
| Product/Team Context | [Plantify](https://github.com/Zendin110206/Plantify)                                                                               | Team/fork plant e-commerce platform                                                                              |
| Product/Team Context | [Website-Studi-Kasus-Academy-Ruang-Desa](https://github.com/Zendin110206/Website-Studi-Kasus-Academy-Ruang-Desa)                   | Team web case-study project for village information/services                                                     |
| Frontend/Profile     | [zaenal-abidin-portfolio](https://github.com/Zendin110206/zaenal-abidin-portfolio)                                                 | Personal portfolio frontend prototype                                                                            |
| Learning Archive     | [2024-Academy](https://github.com/Zendin110206/2024-Academy)                                                                       | Academy resource/fork archive                                                                                    |
| Learning Archive     | [complete-pandas-tutorial](https://github.com/Zendin110206/complete-pandas-tutorial)                                               | Pandas tutorial/fork used for learning                                                                           |
| Learning Archive     | [dart_latihan](https://github.com/Zendin110206/dart_latihan)                                                                       | Dart fundamentals practice                                                                                       |
| Placeholder          | [superstore-profit-leak](https://github.com/Zendin110206/superstore-profit-leak)                                                   | Empty/placeholder repository, not featured                                                                       |

</details>

---

## Toolbox

### Core

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

### Data and Machine Learning

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

### Analytics and Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

### API and App Integration

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

### Operational IoT and Delivery

![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

---

## Working Style

- I prefer projects with a clear problem, data flow, and practical output.
- I document assumptions and limitations so the project does not claim more than it proves.
- I care about clear data assumptions because models are only useful when their inputs, limits, and decisions can be explained.
- I value field feedback, contributor attribution, public-safe documentation, and small reviewable checkpoints.
- I run type, lint, test, and build checks where the project supports them, and I treat operational data and credentials as private by default.
- I use telecom as a strong domain interest while keeping my portfolio open to broader data and ML problems.
- I am gradually improving project structure, model evaluation, API design, deployment, observability, and operational reliability.

---

<div align="center">

Thanks for visiting. I keep this profile updated as the portfolio becomes more focused, field-informed, and mature.

</div>
