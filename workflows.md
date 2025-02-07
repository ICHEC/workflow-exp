# List of Workflow Orchestrators

---

| Orchestrator | Description | Language | Open Source | Graph Type | Use Case |
|--------------|-------------|----------|-------------|------------|----------|
| [Apache Airflow](https://github.com/apache/airflow) | Python-based platform for running DAGs of tasks | Python | Yes | DAGs | ETL, Data Engineering  |
| [Argo Workflows](https://github.com/argoproj/argo-workflows) | Kubernetes-native workflow engine for containerized tasks | YAML/JSON | Yes | DAGs | Kubernetes, DevOps  |
| [Cadence](https://github.com/uber/cadence) | Orchestration engine for long-running business logic (Uber) | Multiple (SDKs) | Yes | Cyclical | Microservices, Event-Driven  |
| [Covalent](https://github.com/AgnostiqHQ/covalent) | Workflow orchestration for quantum/HPC | Python | Yes | DAGs | Scientific Computing  |
| [Cylc](https://github.com/cylc/cylc-flow) | Cyclic workflow engine for weather/climate modeling | Python/YAML | Yes | Cyclical | Scientific Workflows  |
| [Dagster](https://github.com/dagster-io/dagster) | Data orchestrator for ML and analytics | Python | Yes | DAGs | Data Engineering, ML  |
| [Flyte](https://github.com/flyteorg/flyte) | Type-safe workflow platform for large-scale ML | Python/Golang | Yes | DAGs | ML Pipelines  |
| [Kubeflow Pipelines](https://github.com/kubeflow/pipelines) | End-to-end ML workflows on Kubernetes | Python/YAML | Yes | DAGs | Machine Learning  |
| [Luigi](https://github.com/spotify/luigi) | Python module for batch job pipelines | Python | Yes | DAGs | ETL, Batch Processing  |
| [Metaflow](https://github.com/Netflix/metaflow) | Human-friendly library for data science workflows | Python/R | Yes | DAGs | Data Science  |
| [Nextflow](https://github.com/nextflow-io/nextflow) | Reproducible workflows for computational pipelines | Groovy/DSL | Yes | DAGs | Bioinformatics  |
| [Prefect](https://github.com/PrefectHQ/prefect) | Modern workflow management system | Python | Yes | Dynamic DAGs | Automation, Data Engineering  |
| [Temporal](https://github.com/temporalio/temporal) | Fork of Cadence for microservice orchestration | Multiple (SDKs) | Yes | Cyclical | Distributed Systems  |
| [Zeebe](https://github.com/camunda/zeebe) | BPMN-based engine for microservices orchestration | Java | Yes | DAGs | Business Process Automation  |

---

### Key Additions & Notes:  
1. **Graph Type**:  
   - Most tools (e.g., Airflow, Dagster) focus on **DAGs**, while **Cylc**, **Cadence**, and **Temporal** support **cyclical workflows** for recurring or stateful processes .  
   - **Covalent** and **Flyte** are optimized for computational and ML workflows, respectively.  

2. **Language & Use Cases**:  
   - **Python** dominates data-centric tools (Airflow, Luigi), while **Kubernetes-native** engines (Argo, Kubeflow) use YAML/JSON .  
   - **Scientific workflows** (e.g., Cylc, Nextflow) often rely on domain-specific languages (DSLs) .  

3. **Open Source**:  
   - All listed tools are open source, though some (e.g., Camunda, Temporal) offer enterprise editions .  


| Workflow Engine | Language of Coding | Dynamic / Static | Graph Type Supported | Open Source | Learning Curve | Workflow Type | Primary Use Case | GitHub Stars |
|---|---|---|---|---|---|---|---|---|
| [Activepieces](https://github.com/activepieces/activepieces) | JavaScript/TypeScript | Dynamic | DAG | Yes | Low | No-code automation | Business process automation | ![GitHub stars](https://img.shields.io/github/stars/activepieces/activepieces.svg) |
| [AiiDA](https://github.com/aiidateam/aiida-core) | Python | Dynamic | DAG | Yes | Medium – High | Task orchestration & provenance | Computational science (materials science, simulation workflows) | ![GitHub stars](https://img.shields.io/github/stars/aiidateam/aiida-core.svg) |
| [Airflow](https://github.com/apache/incubator-airflow) | Python | Dynamic | DAG | Yes | Medium | Task scheduling & orchestration | Data engineering, ETL processes | ![GitHub stars](https://img.shields.io/github/stars/apache/incubator-airflow.svg) |
| [Argo Workflows](https://github.com/argoproj/argo-workflows) | Go | Dynamic | DAG | Yes | Medium | Container-native workflows | Kubernetes-native workflows | ![GitHub stars](https://img.shields.io/github/stars/argoproj/argo-workflows.svg) |
| [Arvados](https://github.com/arvados/arvados) | Various (Polyglot) | Dynamic | DAG | Yes | High | Data & workflow management | Reproducible data analysis | ![GitHub stars](https://img.shields.io/github/stars/arvados/arvados.svg) |
| [Azkaban](https://azkaban.github.io/) | Java | Static | DAG | Yes | Medium | Batch job scheduling | Hadoop job orchestration | ![GitHub stars](https://img.shields.io/github/stars/azkaban/azkaban.svg) |
| [Brigade](https://brigade.sh/) | JavaScript | Dynamic | DAG | Yes | Medium | Scriptable task automation | Kubernetes-based CI/CD | ![GitHub stars](https://img.shields.io/github/stars/brigadecore/brigade.svg) |
| [Bytechef](https://www.bytechef.io/) | JavaScript/TypeScript | Dynamic | DAG | Yes | Low | Low-code automation | API integration & workflow automation | ![GitHub stars](https://img.shields.io/github/stars/bytechefhq/bytechef.svg) |
| [CabloyJS](https://cabloy.com) | JavaScript | Dynamic | DAG | Yes | Medium | Full-stack framework with workflow engine | Web application development | ![GitHub stars](https://img.shields.io/github/stars/zhennann/cabloy.svg) |
| [Cadence](https://github.com/uber/cadence) | Go | Dynamic | DAG | Yes | Medium | Orchestration engine | Asynchronous business logic execution | ![GitHub stars](https://img.shields.io/github/stars/uber/cadence.svg) |
| [Camunda](https://camunda.com) | Java | Static | BPMN | Yes | High | BPMN-based workflow engine | Business process management | ![GitHub stars](https://img.shields.io/github/stars/camunda/camunda-bpm-platform.svg) |
| [CDS](https://ovh.github.io/cds/) | Go | Dynamic | DAG | Yes | Medium | Continuous delivery & DevOps automation | CI/CD pipelines | ![GitHub stars](https://img.shields.io/github/stars/ovh/cds.svg) |
| [CGraph](https://github.com/ChunelFeng/CGraph) | C++ | Static | DAG | Yes | High | DAG framework | High-performance computing | ![GitHub stars](https://img.shields.io/github/stars/ChunelFeng/CGraph.svg) |
| [CloudSlang](http://www.cloudslang.io/) | Java | Static | DAG | Yes | Medium | Workflow automation | DevOps automation | ![GitHub stars](https://img.shields.io/github/stars/CloudSlang/cloud-slang.svg) |
| [Conductor](https://github.com/conductor-oss/conductor) | Java | Dynamic | DAG | Yes | Medium | Microservices orchestration | Scalable application flows | ![GitHub stars](https://img.shields.io/github/stars/conductor-oss/conductor.svg) |
| [Copper](https://github.com/copper-engine/copper-engine) | Java | Static | DAG | Yes | Medium | Workflow engine | High-performance workflow execution | ![GitHub stars](https://img.shields.io/github/stars/copper-engine/copper-engine.svg) |
| [Couler](https://github.com/couler-proj/couler) | Python | Dynamic | DAG | Yes | Medium | Unified workflow interface | Workflow construction & management | ![GitHub stars](https://img.shields.io/github/stars/couler-proj/couler.svg) |
| [Covalent](https://covalent.xyz) | Python | Dynamic | DAG | Yes | Medium | Workflow orchestration | Quantum computing and HPC workflows | ![GitHub stars](https://img.shields.io/github/stars/AgnostiqHQ/covalent.svg) |
| [Cromwell](https://github.com/broadinstitute/cromwell) | Scala/Java | Static | DAG | Yes | High | Workflow engine | Genomics and scientific data pipelines | ![GitHub stars](https://img.shields.io/github/stars/broadinstitute/cromwell.svg) |
| [Cylc](https://github.com/cylc/cylc-flow) | Python | Dynamic | Cyclic & Acyclic | Yes | High | Workflow orchestration | Complex distributed workflows | ![GitHub stars](https://img.shields.io/github/stars/cylc/cylc-flow.svg) |
| [Dagster](https://github.com/dagster-io/dagster) | Python | Dynamic | DAG | Yes | Medium | Data orchestrator | Machine learning, analytics, ETL | ![GitHub stars](https://img.shields.io/github/stars/dagster-io/dagster.svg) |
| [DigDag](https://github.com/treasure-data/digdag) | Java | Static | DAG | Yes | Medium | Workflow scheduler | Complex pipelines of tasks | ![GitHub stars](https://img.shields.io/github/stars/treasure-data/digdag.svg) |
| [Elsa Workflows](https://github.com/elsa-workflows/elsa-core) | C# | Dynamic | DAG | 

The full list is here: [awesome-workflow-engines](https://github.com/meirwah/awesome-workflow-engines/tree/master)
