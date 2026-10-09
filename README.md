# Samuel Jinadu

**Data Engineer | Python • SQL • PySpark • Airflow • Kafka • Postgres • Docker**

I build reliable data systems that turn messy, high-volume data into trusted datasets for downstream analysis and decision-making. My focus is solving the engineering problems behind useful data: ingestion, validation, transformation, orchestration, real-time processing, and operational reliability.

I am especially interested in modern data pipelines, streaming and event-driven systems, workflow automation, and scalable systems that make data products easier to maintain and trust.

---

## What I Do

- **Build production-minded data pipelines** that extract telemetry and business data from JSON, CSV, and structured sources, validate records, and transform them into analytics-ready datasets.
- **Design medallion architectures** that separate raw, cleaned, and aggregated data across bronze, silver, and gold layers.
- **Solve data quality problems** with configurable validation rules, quality thresholds, rejected-record handling, and transparent pipeline outcomes.
- **Process data at scale** with PySpark and Delta Lake while keeping transformations structured, testable, and maintainable.
- **Orchestrate batch workflows** using Airflow so scheduled jobs run reliably and dependencies are managed cleanly.
- **Build streaming data systems** that move events from producers to consumers, enrich data, detect business anomalies, and persist results for querying.
- **Serve analytical results** through SQL-backed storage and dashboards, helping raw data become usable business insight.
- **Automate reliable workflows** with Docker, YAML configuration, CI checks, logging, and reproducible development environments.

---

## Technical Skills

**Languages:** Python, SQL, Bash  
**Data Engineering:** PySpark, pandas, Airflow, Kafka, ETL/ELT, medallion architecture, data validation, data quality checks, schema design, aggregations, stream processing  
**Data Storage & Analytics:** PostgreSQL, SQLite, Delta tables, SQL analytics, data modeling  
**Visualization & Serving:** Streamlit, dashboards, operational reporting  
**Engineering & DevOps:** Docker, Docker Compose, Git, GitHub Actions, YAML configuration, Linux, cron, CI/CD  
**Quality & Tooling:** pytest, ruff, Black, uv, logging, error handling, reproducible environments, testable code

---

## Featured Projects

| Project | What It Demonstrates | Stack |
|---------|------------------------|-------|
| [iot-data-pipeline](https://github.com/samuel-jinadu/iot-data-pipeline) | A config-driven PySpark IoT pipeline that extracts JSON and CSV telemetry, validates data quality, cleans records, and produces bronze, silver, and gold Delta tables. Includes device aggregation by country, Docker execution, YAML quality thresholds, and pytest CI. | Python, PySpark, Delta Lake, Docker, YAML, pytest |
| [nyc-taxi-duration-pipeline](https://github.com/samuel-jinadu/nyc-taxi-duration-pipeline) | A workflow that ingests NYC taxi trip data, derives trip durations, aggregates results by taxi zone, and serves the output in a dashboard for operational and analytical use. | Python, Airflow, Postgres, Streamlit, SQL |
| [ecom-stream-pipeline](https://github.com/samuel-jinadu/ecom-stream-pipeline) | A real-time e-commerce analytics pipeline where Faker generates orders, Kafka streams events, Python consumers enrich revenue and detect low stock, PostgreSQL stores results, and Streamlit updates a live dashboard. | Python, Kafka, Postgres, Streamlit, Docker |
| [automated-data-pipeline](https://github.com/samuel-jinadu/automated-data-pipeline) | An automated ingestion workflow that validates CSV data against configurable YAML rules, quarantines invalid rows, archives metadata, and runs on a schedule. | Python, pandas, YAML, Docker, cron |
| [system-administration-toolkit](https://github.com/samuel-jinadu/system-administration-toolkit) | Reliable system automation for log rotation, backups, and file synchronization, with dry-run support, standardized exit codes, and test coverage. | Python, Bash, Linux, pytest |
| [sales-trend-analysis](https://github.com/samuel-jinadu/sales-trend-analysis) | A data analysis project covering SQL schema design, data preparation, business analysis, and communicating trends through visual reporting. | SQL, Python, pandas, Tableau |

---

## How I Approach Data Engineering Problems

1. **Understand the data and the decision it supports.**
2. **Make assumptions and business rules explicit through configuration and schemas.**
3. **Validate early and isolate invalid records instead of silently dropping them.**
4. **Separate raw, transformed, and serving layers so the pipeline remains traceable.**
5. **Test transformations and data-quality behavior before deployment.**
6. **Package and automate the workflow so it can be reproduced and operated consistently.**
7. **Design for visibility and observability, especially in streaming and operational systems.**

---

## What I'm Looking For

- Data Engineer opportunities focused on pipelines, streaming, orchestration, analytics, and automation
- Python, PySpark, Kafka, or workflow automation engineering roles
- Contract projects involving ingestion, streaming, data quality, ETL/ELT, and analytics-ready data systems

I am based in Nigeria and open to global remote opportunities.

---

## Contact

- Email: theoriginaljinadusamuel@gmail.com
- LinkedIn: [Samuel Jinadu](https://www.linkedin.com/in/samuel-jinadu-b02ba1264)
