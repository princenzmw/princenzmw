# Prince Nzamuwe

Data Science & ML Engineering Student | BSc Data Science & Analytics, USIU-Africa (expected 2028)
Nairobi, Kenya | Open to internships, part-time engineering roles, and freelance work

[Portfolio](https://nzamuwe.com) | [LinkedIn](https://www.linkedin.com/in/princenzmw/) | [Email](mailto:prince@nzamuwe.com)

---

I build end-to-end data products in Python and SQL: calibrated machine learning pipelines, PostgreSQL and TimescaleDB backends, and weighted Power BI models. Mastercard Foundation Scholar at USIU-Africa, previously trained through the Andela Technical Leadership Program (ATLP) and ALX Software Engineering Foundations.

## Selected Projects

| Project | What it does | Stack | Links |
| :--- | :--- | :--- | :--- |
| [Credio](https://github.com/princenzmw/credit-risk-scorecard) | Credit-risk scorecard trained on the Kaggle Give Me Some Credit benchmark (150,000 borrowers). Leak-free scikit-learn pipeline, calibrated gradient-boosting model (0.869 ROC-AUC, 0.407 PR-AUC, 0.0486 Brier score on 30,000 held-out records), cost-based decision threshold, and 19 CI unit tests. | Python, scikit-learn, pandas, Streamlit, Pytest, Docker, GitHub Actions | [Live App](https://credio.nzamuwe.com/) · [Case Study](https://nzamuwe.com/projects/credio) · [Code](https://github.com/princenzmw/credit-risk-scorecard) |
| [DukaPulse](https://github.com/princenzmw/DukaPulse) | Point-of-sale and analytics backend for Kenyan retail shops (dukas). Atomic PostgreSQL updates verified against a 16-thread, 10,000-attempt oversell race test, TimescaleDB continuous aggregates, pgvector semantic search with Swahili and Sheng query expansion, and Auth0 role-based margin redaction. | Python, FastAPI, PostgreSQL, TimescaleDB, pgvector, Auth0, Streamlit, Docker, GitHub Actions | [Dashboard](https://dukapulse.streamlit.app) · [Case Study](https://nzamuwe.com/projects/dukapulse) · [Code](https://github.com/princenzmw/DukaPulse) |
| [FinAccess Kenya 2024](https://github.com/princenzmw/finaccess-kenya-dashboard) | Streaming Python ETL pipeline that compacts the 290 MB CBK/KNBS/FSD Kenya household survey into an 8 MB weighted dataset (19,750 adults representing 28.1M). Reconciles to published national toplines (84.8% formal access, 9.9% excluded) and feeds a 5-page Power BI report exposing a 45-point county access gap. | Python, pandas, Power BI, DAX | [Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYTJjMDVkMmUtZGYxMC00ZTExLTlhZGEtYjcyZTZiNjk1YzhkIiwidCI6IjE2ZDgzZWU2LTI1NGEtNDY5ZC1hNmNjLTU0ZTJjYTIzMTNlNyIsImMiOjh9&embedImagePlaceholder=true&pageName=a09621f88fac873c711f) · [Case Study](https://nzamuwe.com/projects/finaccess) · [Code](https://github.com/princenzmw/finaccess-kenya-dashboard) |
| [Mzigo Chakula](https://github.com/princenzmw/mzigo-chakula) | County-level analysis of Kenya food-price inflation from 2007 to 2026 using 55,692 rows of World Bank Real Time Food Prices across 233 markets and 27 counties. Built as a 4-table star schema with 15 DAX measures and a 4-page Power BI PBIR report (USIU-Africa DSA 3050A). | Power BI (PBIR), DAX, Power Query, Python | [Code](https://github.com/princenzmw/mzigo-chakula) |

Additional public work includes [grid-ops-search](https://github.com/princenzmw/grid-ops-search) and [VoltStream](https://github.com/princenzmw/voltstream) (real-time TimescaleDB power-grid telemetry joined with pgvectorscale StreamingDiskANN semantic search).

## Core Stack

- **Data & ML:** Python, SQL (PostgreSQL, TimescaleDB, pgvector), pandas, NumPy, scikit-learn, feature engineering, probability calibration (Brier score, calibration curves), classification evaluation (ROC-AUC, PR-AUC).
- **Backend & Web:** FastAPI, Flask, TypeScript, Next.js, Auth0 RBAC, Streamlit.
- **BI & Analytics:** Power BI (PBIR, DAX, Power Query), star-schema modeling, weighted survey analysis.
- **Testing & Delivery:** Pytest, Docker, GitHub Actions, Linux/Bash, Git.
