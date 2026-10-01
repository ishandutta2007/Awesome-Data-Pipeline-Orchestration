# Awesome-Data-Pipeline-Orchestration

# Top Data Pipeline Orchestration Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Workflow Scheduling, Data Pipeline Orchestration, Asset-Based Pipelines, Event-Driven Flows & Managed Orchestrators*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Pipeline Orchestration**. These systems schedule, run, monitor, and retry complex data workflows across warehouses, lakes, and external systems.

**Examples** include Astronomer, Prefect Cloud, Dagster Cloud, Kestra, Control-M Cloud, Orkes Conductor, Mage Pro, Flyte, Apache Airflow MWAA, and Google Cloud Composer (the category leaders).

**Open-source emphasis**: Orchestration is one of the strongest open-source categories. **Apache Airflow**, **Prefect**, **Dagster**, **Kestra**, **Flyte**, and related projects power the majority of modern data platforms. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Astronomer](https://www.astronomer.io/)**  
  Managed Apache Airflow platform (Astro) with enterprise support, observability, and cloud-native deployments.

- **[Prefect Cloud](https://www.prefect.io/)**  
  Managed orchestration for Python-first, dynamic workflows with hybrid execution and a modern control plane.

- **[Dagster Cloud / Dagster+](https://dagster.io/)**  
  Managed asset-oriented orchestration platform built around software-defined assets and strong observability.

- **[Kestra](https://kestra.io/)**  
  Declarative, language-agnostic orchestration platform (open-source core + enterprise/cloud offerings).

- **[Control-M Cloud (BMC)](https://www.bmc.com/it-solutions/control-m.html)**  
  Enterprise workload automation and orchestration with strong mainframe-to-cloud scheduling heritage.

- **[Orkes Conductor](https://orkes.io/)**  
  Managed Netflix Conductor–based workflow orchestration for microservices and data workflows.

- **[Mage Pro](https://www.mage.ai/)**  
  Managed offering around the Mage open-source data pipeline platform for building and running pipelines.

- **[Flyte](https://flyte.org/)**  
  Cloud-native workflow orchestrator (open-source + commercial support) optimized for data and ML pipelines on Kubernetes.

- **[Apache Airflow MWAA (Amazon)](https://aws.amazon.com/managed-workflows-for-apache-airflow/)**  
  AWS Managed Workflows for Apache Airflow—fully managed Airflow environments on AWS.

- **[Google Cloud Composer](https://cloud.google.com/composer)**  
  Fully managed Apache Airflow service on Google Cloud.

## Open-Source GitHub Projects
- **[Apache Airflow](https://github.com/apache/airflow)**  
  The most widely adopted open-source workflow orchestrator for scheduled batch data pipelines, with a massive provider ecosystem.

- **[Prefect](https://github.com/PrefectHQ/prefect)**  
  Open-source Python-native orchestration framework for dynamic, data-dependent workflows with a modern hybrid model.

- **[Dagster](https://github.com/dagster-io/dagster)**  
  Open-source asset-centric orchestrator that treats data assets as first-class citizens with built-in lineage and observability.

- **[Kestra](https://github.com/kestra-io/kestra)**  
  Open-source declarative orchestration engine using YAML workflows and polyglot task execution.

- **[Flyte](https://github.com/flyteorg/flyte)**  
  Open-source Kubernetes-native workflow engine designed for reproducible data and ML pipelines.

- **[Temporal](https://github.com/temporalio/temporal)**  
  Open-source durable execution platform excellent for long-running, failure-tolerant application and data workflows.

- **[Netflix Conductor](https://github.com/Netflix/conductor)**  
  Open-source microservices orchestration engine (foundation for Orkes Conductor).

- **[Mage](https://github.com/mage-ai/mage-ai)**  
  Open-source data pipeline tool for building, running, and managing ETL/ELT pipelines with a notebook-style experience.

- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  
  Open-source Kubernetes-native workflow engine often used for containerized data and CI pipelines.

- **[Documentation and Airflow / Prefect / Dagster playbooks](https://airflow.apache.org/docs/)**  
  Guides for self-hosting, scaling, and operating open orchestrators in production.

### Additional Strong Open-Source Options
- Choosing **Airflow** for broad ecosystem and scheduled batch pipelines.
- Choosing **Prefect** for dynamic Python workflows.
- Choosing **Dagster** for asset-oriented, observable data platforms.
- Choosing **Kestra** for declarative, language-agnostic flows.
- Choosing **Flyte** or **Temporal** for Kubernetes-native or durable execution needs.
- Accepting that managed reliability, multi-tenant control planes, and enterprise support still drive many teams to Astronomer, Prefect Cloud, Dagster+, MWAA, Composer, etc.
- Focusing open-source efforts on ownership of pipeline code and avoiding orchestrator lock-in.

**Frameworks for building custom systems**: Author DAGs/flows/assets in Airflow, Prefect, or Dagster → run workers on Kubernetes or VMs → monitor with open metrics and lineage → scale with queue-based executors. Suitable for data platform teams. Organizations preferring zero ops often adopt managed Airflow or cloud orchestrators.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Orchestrators control critical data movement. Secure credentials, isolate environments, and plan for failure modes. This list is not operational advice.

---
**Made for data engineers, platform teams, and open orchestration advocates.**
Let's keep pipelines reliable, observable, and as open as practical.
