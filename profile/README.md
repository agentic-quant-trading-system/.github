# 📈 Agentic Quant Trading System

Welcome to the **Agentic Quant Trading System**, a multi-component architecture dedicated to automated, AI-driven quantitative trading. This organization houses the end-to-end lifecycle of the trading system, from machine learning operations to live dashboarding and agent-based execution.

## 🏗️ System Architecture

This project is decoupled into three primary repositories, separating the data engineering, core trading logic, and user interface:

* **[`agentic-ai-trading`](https://github.com/agentic-quant-trading-system/agentic-aI-trading)**
    * **Role:** The backbone of the system.
    * **Description:** Handles daily scheduled market and macro data fetching financial APIs and store them in Azure Blob containers.

* **[`azure-mlops-trading-pipeline`](https://github.com/agentic-quant-trading-system/azure-mlops-trading-pipeline)**
    * **Role:** The brain of the system.
    * **Description:** Handles the MLOps and quantitative data pipelines deployed on Azure. Responsible for data ingestion, model training, and ensuring the robust delivery of macro and market data to the trading agents. Contains the core Agentic AI logic, manages the decision-making processes, strategy execution, and the underlying AI models that drive the trading behavior.

* **[`quant-portfolio-dashboard`](https://github.com/agentic-quant-trading-system/quant-portfolio-dashboard)**
    * **Role:** The visualization and monitoring layer.
    * **Description:** A live agentic sector rotation dashboard utilizing K-Means Macro Clustering. It provides real-time insights into portfolio performance, active agent strategies, and macro-economic regime shifts.

## 🛠️ Tech Stack & Methodologies
* **Languages:** Python 
* **Infrastructure:** Microsoft Azure, GitHub Actions (CI/CD)
* **Data Science:** Jupyter Notebooks, K-Means Clustering, MLOps best practices
* **Paradigm:** Agentic AI, Quantitative Finance, Microservices

## 👨‍💻 About the Maintainer
This architecture is developed and maintained by **MSM Macksood**, bridging advanced academic research from a Data Science Masters with practical, production-grade cloud engineering. 

---
*Disclaimer: The code and strategies within this organization are for educational and research purposes. They do not constitute financial advice.*
