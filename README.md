# Hi, I'm Harsh Jha 👋

### Data Analyst · ETL Pipelines · Geospatial Data · Python | SQL | Tableau | Power BI

I build data pipelines that turn messy, scattered sources into clean, verified databases, and the
dashboards, automations and apps people use to act on them, from SAP/Excel → Oracle ETL and
Tableau Server dashboards for **GAIL India Limited** to an India-wide geospatial data platform.

📍 Noida, India · 🎓 B.Tech CSE (Data Science), UPES · 💼 2 years in data analytics

---

### 🚀 What I'm building now

**CGD Station Data Platform** · *private, in active development*
An end-to-end platform mapping **CNG stations of City Gas Distribution operators across India**,
serving 3,000+ stations today.

- **Extraction:** Python pipeline per operator (`discover → fetch → parse → normalize → validate`), with
  robots.txt **and** Terms-of-Use checks before any source is collected
- **Automation:** Prefect flows run a new operator end to end (research report → extraction → audited
  load), with an **Update** mode that only re-checks what changed and a weekly scheduled refresh
- **Exact locations:** stations matched to their own pump on **Ola Maps**, confirmed by a second source
  (OpenStreetMap); every station carries an honest precision class instead of a fake exact point
- **Database:** PostgreSQL + PostGIS with numbered load batches, dry-run-then-commit loads, backups,
  a change-audit table and SQL verification checks
- **App:** FastAPI backend with spatial "near me" queries and a React Native (Expo) app with List/Map views
  and an **Admin page** to run, approve and track extractions, shipped as an Android build and a web app

---

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Languages** | Python (Pandas, NumPy, Matplotlib, Seaborn), SQL, JavaScript |
| **Databases** | Oracle, SQL Server (SSMS), PostgreSQL + PostGIS, MySQL, MongoDB |
| **Data engineering** | ETL pipelines, workflow automation (Prefect), web scraping (Scrapy, Requests, BeautifulSoup, Playwright), data cleaning & validation, data modeling |
| **Geospatial** | PostGIS, OpenStreetMap (Nominatim, Overpass), Ola Maps API, GeoJSON |
| **BI & visualization** | Tableau & Tableau Server, Power BI (DAX), Looker Studio, Excel |
| **Apps & cloud** | FastAPI, React Native / Expo, Next.js, AWS S3, Firebase, Git / GitHub |

---

### 📌 Featured projects

| Project | What it shows |
|---|---|
| [**Automated Tradebook Data Pipeline**](https://github.com/Harsh24102/Automated-Tradebook-Data-Pipeline-ETL-and-SQL-Integration) | Python ETL for **1M+ tradebook records** into SQL Server, optimised procedures, Power BI (DAX) dashboards |
| [**Spyder Project**](https://github.com/Harsh24102/Spyder-Project) | Scrapy pipeline that turns store-locator pages into GeoJSON, with tests (HERE Technologies internship) |
| [**IoT Precision Agriculture**](https://github.com/Harsh24102/IOT-based-Precision-Agriculture) | Raspberry Pi sensors, trained ANFIS model + 15-rule fuzzy controller for irrigation, Firestore logging, live charts |
| [**Vault Cloud**](https://github.com/Harsh24102/Vault_cloud) | Next.js file-sharing rooms: invites, S3 pre-signed uploads, Firestore chat |
| [**SENSEX Crash Analysis**](https://github.com/Harsh24102/Stock-Market-Crash-Analysis) | 28 years of SENSEX drawdowns, crash periods and an early-warning rule tested on real data (pandas, Plotly) |

---

### 💼 Experience

- **Data Analyst**, Firmwise Services India (client: GAIL India Limited) · *Feb 2026 – Oct 2026*
- **Data Analyst**, Arya Fin-Trade Services · *Sep 2024 – Aug 2025*
- **Data Engineer Intern**, HERE Technologies · *Jun – Jul 2023*
- **Data Analyst Intern**, Lendingkart Finance · *Jul 2023*

---

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harshjha24-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshjha24)
[![Email](https://img.shields.io/badge/Email-harshjha24102%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:harshjha24102@gmail.com)
