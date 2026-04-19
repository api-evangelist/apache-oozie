# Apache Oozie (apache-oozie)
Apache Oozie is a workflow scheduler system for managing Apache Hadoop jobs. It enables users to define workflows as directed acyclic graphs (DAGs) of actions including MapReduce, Pig, Hive, Sqoop, and custom Java/shell steps. Coordinator jobs trigger workflows based on time schedules or data availability, while bundle jobs group multiple coordinators. Oozie provides a REST API for job submission, lifecycle management, monitoring, and system administration. Governed by the Apache Software Foundation under the Apache License 2.0, written in Java.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-oozie/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Workflow, Hadoop, Orchestration, Scheduling, Big Data, Apache, Java, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Oozie REST API
The Oozie Web Services API provides REST endpoints for submitting, managing, and monitoring workflow, coordinator, and bundle jobs on Apache Hadoop. Supports full job lifecycle management (submit, start, suspend, resume, kill, rerun), log and status retrieval, DAG visualization, SLA management, and system administration. Available at /oozie/v1 and /oozie/v2 with JSON responses.

**Human URL:** [https://oozie.apache.org/docs/5.2.1/WebServicesAPI.html](https://oozie.apache.org/docs/5.2.1/WebServicesAPI.html)

#### Tags:

 - REST, Hadoop, Workflow Management, Job Scheduling

#### Properties

- [Documentation](https://oozie.apache.org/docs/5.2.1/WebServicesAPI.html)
- [OpenAPI](openapi/apache-oozie-openapi.yaml)
- [JSONSchema - Job Info Schema](json-schema/apache-oozie-job-info-schema.json)
- [JSONSchema - Job List Schema](json-schema/apache-oozie-job-list-schema.json)
- [JSONSchema - Job ID Schema](json-schema/apache-oozie-job-id-schema.json)
- [JSONSchema - System Status Schema](json-schema/apache-oozie-system-status-schema.json)

## Common Properties

- [GitHub Repository](https://github.com/apache/oozie)
- [GitHub Organization](https://github.com/apache)
- [Documentation](https://oozie.apache.org/docs/5.2.1/)
- [Getting Started](https://oozie.apache.org/docs/5.2.1/DG_QuickStart.html)
- [Tutorials](https://oozie.apache.org/docs/5.2.1/DG_Examples.html)
- [Release Notes](https://github.com/apache/oozie/blob/master/release-log.txt)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)
- [Support](https://oozie.apache.org/mailing-lists.html)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/oozie)
- [Spectral Rules](rules/apache-oozie-spectral-rules.yml)
- [Naftiko Capability](capabilities/apache-oozie-workflow-orchestration.yaml)
- [Vocabulary](vocabulary/apache-oozie-vocabulary.yaml)
- [JSON-LD Context](json-ld/apache-oozie-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Directed Acyclic Graph Workflows | Define complex data processing pipelines as DAGs of actions executed on Apache Hadoop. |
| Coordinator Jobs | Schedule recurring workflows triggered by time intervals or data availability conditions in HDFS. |
| Bundle Jobs | Group multiple coordinator jobs into a single bundle for coordinated lifecycle management. |
| REST API Management | Full REST API for job submission, lifecycle control, monitoring, and system administration. |
| Native Hadoop Action Types | Built-in support for MapReduce, Pig, Hive, Sqoop, Distcp, and custom Java/shell actions. |
| SLA Management | Define and monitor service level agreements on workflow and coordinator actions with alert capabilities. |
| DAG Visualization | Generate PNG, SVG, or DOT graph visualizations of workflow DAGs for debugging and documentation. |
| Log Retrieval | Retrieve execution logs, error logs, and audit trails for jobs via REST API with filtering support. |
| High Availability | Built-in HA support with multiple Oozie server instances and distributed state management. |
| Shared Library Support | Manage shared Hadoop libraries across workflows for consistent classpath management. |

## Use Cases

| Name | Description |
|------|-------------|
| ETL Pipeline Orchestration | Orchestrate multi-step ETL pipelines combining Hive queries, MapReduce jobs, and data transfers on Hadoop. |
| Scheduled Data Processing | Run recurring Hadoop batch jobs on time-based schedules using coordinator jobs. |
| Data-Triggered Workflows | Trigger workflows automatically when new data arrives in HDFS using coordinator data-in conditions. |
| Machine Learning Pipeline Automation | Automate ML model training and evaluation pipelines on Hadoop with dependency chaining. |
| Data Migration and Archival | Orchestrate large-scale data migration, compaction, and archival workflows across Hadoop clusters. |
| Multi-Cluster Coordination | Coordinate workflows that span multiple Hadoop clusters using Distcp and remote actions. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | Core integration with HDFS for data storage and YARN for resource management. |
| Apache Hive | Native Hive action type for executing HiveQL queries as workflow steps. |
| Apache Pig | Native Pig action type for data transformation scripts in workflow pipelines. |
| Apache Sqoop | Native Sqoop action type for importing and exporting data between Hadoop and RDBMS. |
| Apache Spark | Spark action type for running Spark jobs within Oozie workflows. |
| Apache MapReduce | Native MapReduce action type as the foundational Hadoop computation framework. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Oozie REST API](openapi/apache-oozie-openapi.yaml)

### JSON Schema

- [System Status](json-schema/apache-oozie-system-status-schema.json)
- [Build Version](json-schema/apache-oozie-build-version-schema.json)
- [System Metrics](json-schema/apache-oozie-system-metrics-schema.json)
- [Job ID](json-schema/apache-oozie-job-id-schema.json)
- [Job Action](json-schema/apache-oozie-job-action-schema.json)
- [Job Info](json-schema/apache-oozie-job-info-schema.json)
- [Job List](json-schema/apache-oozie-job-list-schema.json)
- [Validation Result](json-schema/apache-oozie-validation-result-schema.json)

### JSON Structure

- [System Status](json-structure/apache-oozie-system-status-structure.json)
- [Build Version](json-structure/apache-oozie-build-version-structure.json)
- [System Metrics](json-structure/apache-oozie-system-metrics-structure.json)
- [Job ID](json-structure/apache-oozie-job-id-structure.json)
- [Job Action](json-structure/apache-oozie-job-action-structure.json)
- [Job Info](json-structure/apache-oozie-job-info-structure.json)
- [Job List](json-structure/apache-oozie-job-list-structure.json)
- [Validation Result](json-structure/apache-oozie-validation-result-structure.json)

### JSON-LD

- [Apache Oozie Context](json-ld/apache-oozie-context.jsonld)

### Examples

- [System Status](examples/apache-oozie-system-status-example.json)
- [Build Version](examples/apache-oozie-build-version-example.json)
- [Job ID](examples/apache-oozie-job-id-example.json)
- [Job Action](examples/apache-oozie-job-action-example.json)
- [Job Info](examples/apache-oozie-job-info-example.json)
- [Job List](examples/apache-oozie-job-list-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Oozie REST API](capabilities/shared/apache-oozie.yaml) — 8 operations for admin, job submission, bulk management, and job lifecycle control

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Oozie Workflow Orchestration](capabilities/apache-oozie-workflow-orchestration.yaml) | Apache Oozie REST API | 12 | Data Engineer, Hadoop Pipeline Operator |

## Vocabulary

- [Apache Oozie Vocabulary](vocabulary/apache-oozie-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 14 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Oozie Spectral Rules](rules/apache-oozie-spectral-rules.yml) — 28 rules across 9 categories enforcing Apache Oozie REST API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
