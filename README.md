## Hi, I'm Juliano 👋

Senior Data Engineer and DevOps Engineer at IBOPE, responsible for the cloud data platform behind audience and media measurement: Airflow orchestration on Azure Kubernetes Service, infrastructure as code across production, staging and UAT, and the observability layer that keeps those pipelines accountable.

I work end to end, from ingestion and data modeling through to the executive dashboard and the incident review that follows when something breaks. Five years across multinational FMCG analytics and audience insights, with selected outcomes: manual Excel routines migrated to Python pipelines, cutting Power BI refresh time by 90 percent; an annual target planning model adopted by a 180 person commercial team, removing a full day from the planning cycle; and a supplier monitoring solution that made TV data SLA breaches visible for the first time, enabling contractual penalties the business had previously been unable to claim.

My foundation is long term database administration across Oracle, PostgreSQL and MySQL. I hold a Bachelor's degree in Information Systems from UVA (Universidade Veiga de Almeida, 2024) and I am currently pursuing a Master's in Generative AI and LLMs at PUC-Rio. The research below is where that work meets the failure modes I deal with in production.

### Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

### Applied research

Each repository treats a production observability problem as a measurable research question, with a full evaluation harness and results reported whether or not they favor the method.

**[causal-rca](https://github.com/julianodutraa/causal-rca)**: causal root cause localization for pipeline DAGs. A noisy OR Bayesian network over the task dependency graph, calibrated against 50,000 Monte Carlo simulations and fused with a tool augmented LLM evidence agent. Across 1,000 synthetic incidents the pure Bayesian model with a uniform prior loses to a simple topological heuristic, and the evidence fusion earns its cost on the 6 percent of cases where the two methods disagree. MIT licensed, 26 automated tests.

**[llm-calibrated-log-template-mining](https://github.com/julianodutraa/llm-calibrated-log-template-mining-2026-09-13)**: log template mining for pipeline observability, pairing Drain parsing with a calibrated LLM merge review judge scored by Brier score and expected calibration error, plus Jensen-Shannon divergence for drift detection.

**[telemetry-anomaly-triage-copilot](https://github.com/julianodutraa/telemetry-anomaly-triage-copilot-2026-09-09)**: RAG and LLM-assisted root cause triage for correlated pipeline anomalies, combining STL and MAD statistical detection with a full offline evaluation harness on synthetic data.

📍 Rio de Janeiro, Brazil · Remote

![Juliano's GitHub stats](https://github-readme-stats.vercel.app/api?username=julianodutraa&show_icons=true&count_private=true&theme=default) ![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=julianodutraa&layout=compact&theme=default)
