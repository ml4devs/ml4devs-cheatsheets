# ML4Devs Cheat Sheets and Diagrams

One-page cheat sheets and diagrams for developers and engineers building data, ML, and AI applications. Each one links to the [ML4Devs](https://www.ml4devs.com) article.

- [Cheat Sheets](#cheat-sheets)
  - [Big Data Pipelines on AWS, Azure, and Google Cloud](#big-data-pipelines-on-aws-azure-and-google-cloud)
  - [SQL vs. NoSQL: Cheat Sheet for AWS, Azure, and Google Cloud](#sql-vs-nosql-cheat-sheet-for-aws-azure-and-google-cloud)
  - [MLOps Cheat Sheet: Google Cloud](#mlops-cheat-sheet-google-cloud)
  - [Cloud Deployment Cheat Sheet for AWS, Azure, and Google Cloud](#cloud-deployment-cheat-sheet-for-aws-azure-and-google-cloud)
  - [SQL Joins Cheat Sheet](#sql-joins-cheat-sheet)
  - [Popular Machine Learning Models](#popular-machine-learning-models)
  - [5 Faster Alternatives to Pandas DataFrame apply()](#5-faster-alternatives-to-pandas-dataframe-apply)
- [Diagrams](#diagrams)
  - [Big Data Architecture Diagram](#big-data-architecture-diagram)
  - [Data Pipeline Stages Diagram](#data-pipeline-stages-diagram)
  - [OLAP Cube Diagram](#olap-cube-diagram)
  - [SQL vs. NoSQL Comparison Diagram](#sql-vs-nosql-comparison-diagram)
  - [MLOps Lifecycle Diagram](#mlops-lifecycle-diagram)

All cheat sheets and diagrams are © [Satish Chandra Gupta](https://www.linkedin.com/in/scgupta/) and licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). Share them with credit and a link to the source page. For commercial use or adaptations, [get in touch](https://www.ml4devs.com/contact/).

## Cheat Sheets

### Big Data Pipelines on AWS, Azure, and Google Cloud

The five stages of a big data pipeline (capture, ingest, store, compute, and use), with orchestration and data catalog services, mapped to AWS, Azure, and Google Cloud.

[![Big data pipeline cheat sheet: AWS, Azure, and Google Cloud services for the capture, ingest, store, compute, and use stages](https://www.ml4devs.com/images/illustrations/big-data-pipeline-v2022.webp)](https://www.ml4devs.com/articles/big-data-pipeline-architecture/)

Article: [Big Data Pipeline Architecture: Patterns and Design Guide](https://www.ml4devs.com/articles/big-data-pipeline-architecture/)

### SQL vs. NoSQL: Cheat Sheet for AWS, Azure, and Google Cloud

A decision tree from data type and use case to relational, columnar, key-value, in-memory, wide column, time series, ledger, geospatial, graph, document, text search, or blob storage, with the matching databases on each cloud.

[![SQL vs. NoSQL database cheat sheet: decision tree by data type, with matching AWS, Azure, Google Cloud, and cloud-agnostic databases](https://www.ml4devs.com/images/illustrations/sql-vs-nosql-cheatsheet.webp)](https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/)

Article: [SQL vs. NoSQL Database: When to Use, How to Choose](https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/)

### MLOps Cheat Sheet: Google Cloud

Vertex AI and Google Cloud data services across the Data, ML, Dev, and Ops loops of the machine learning lifecycle, as of 2023.

[![MLOps cheat sheet for Google Cloud: Vertex AI and data services across the Data, ML, Dev, and Ops lifecycle](https://www.ml4devs.com/images/illustrations/mlops-tools-on-gcp-v2023.webp)](https://www.ml4devs.com/articles/mlops-on-gcp-aws-azure/)

Article: [MLOps Tools & Services](https://www.ml4devs.com/articles/mlops-on-gcp-aws-azure/)

### Cloud Deployment Cheat Sheet for AWS, Azure, and Google Cloud

A decision tree for new builds and migrations that picks IaaS, CaaS, serverless CaaS, PaaS, or FaaS, with the matching compute service on each cloud.

[![Cloud deployment cheat sheet: decision tree for IaaS, CaaS, serverless CaaS, PaaS, and FaaS, with AWS, Azure, and Google Cloud services](https://www.ml4devs.com/images/illustrations/cloud-deployment-cheatsheet.webp)](https://www.ml4devs.com/articles/serverless-architecture-for-microservices-on-aws-vs-google-cloud-vs-azure-as-iaas-caas-paas-faas/)

Article: [Serverless Computing on AWS, Azure, and Google Cloud](https://www.ml4devs.com/articles/serverless-architecture-for-microservices-on-aws-vs-google-cloud-vs-azure-as-iaas-caas-paas-faas/)

### SQL Joins Cheat Sheet

Inner, left, right, and full outer joins: the SELECT syntax, a Venn diagram, how the keys match, and the result table with NULLs.

[![SQL joins cheat sheet: inner, left, right, and full outer join syntax, Venn diagrams, and result tables](https://www.ml4devs.com/images/illustrations/sql-joins-cheatsheet.webp)](https://www.ml4devs.com/articles/sql-joins-tutorial-inner-join-left-join-right-join-full-join-cross-join/#sql-joins-cheat-sheet)

Article: [Types of SQL Joins: Inner, Left, Right, and Full](https://www.ml4devs.com/articles/sql-joins-tutorial-inner-join-left-join-right-join-full-join-cross-join/)

### Popular Machine Learning Models

A mind map of statistical modeling (supervised and unsupervised), ensemble models, reinforcement learning, and neural networks, with example algorithms for each.

[![Machine learning models cheat sheet: statistical modeling, ensemble models, reinforcement learning, and neural networks](https://www.ml4devs.com/images/illustrations/ml-intro-types-of-models.webp)](https://www.ml4devs.com/articles/machine-learning-intro-for-developers/)

Article: [An Engineer's Trek into Machine Learning](https://www.ml4devs.com/articles/machine-learning-intro-for-developers/)

### 5 Faster Alternatives to Pandas DataFrame apply()

Code for itertuples(), list comprehension, map(), NumPy vectorize(), and Pandas vectorization, with benchmark timings against apply().

[![Pandas apply() alternatives cheat sheet: itertuples, list comprehension, map, NumPy vectorize, and vectorization, with benchmark timings](https://www.ml4devs.com/images/illustrations/pandas-dataframe-apply-alternatives.webp)](https://www.ml4devs.com/articles/pandas-dataframe-apply-function-iterate-over-rows/#recommendations)

Article: [Pandas Apply: 12 Ways to Apply a Function to Each Row in a DataFrame](https://www.ml4devs.com/articles/pandas-dataframe-apply-function-iterate-over-rows/)

## Diagrams

### Big Data Architecture Diagram

Data sources (mobile, web, microservices, IoT, and batch) flowing through the capture, ingest, store, compute, and use stages. The streaming path runs through an event queue and stream processing. The batch path runs through a data lake, a data warehouse, and batch processing. Orchestration, data quality, catalog, and governance span all stages.

[![Big data pipeline architecture diagram: batch and streaming paths across the capture, ingest, store, compute, and use stages](https://www.ml4devs.com/images/illustrations/big-data-pipeline-architecture.webp)](https://www.ml4devs.com/what-is/data-architecture/#big-data-architecture-diagram)

Explainer: [Data Architecture: Blueprint of How Data Powers the Business](https://www.ml4devs.com/what-is/data-architecture/)

### Data Pipeline Stages Diagram

The five stages of a data pipeline: sources in capture, extract in ingest, load into a data warehouse and data lake in store, transform in compute, and sinks such as dashboards, ML models, and event streams in use.

[![Big data pipeline stages diagram: capture, ingest, store, compute, and use, with orchestration, data quality, catalog, and governance](https://www.ml4devs.com/images/illustrations/big-data-pipeline-stages.webp)](https://www.ml4devs.com/what-is/data-pipeline/#data-pipeline-stages)

Explainer: [Data Pipeline: Batch, Streaming, and Idempotent Patterns](https://www.ml4devs.com/what-is/data-pipeline/)

### OLAP Cube Diagram

A hypercube along time (Q1 to Q4), product, and geography (NA, LATAM, EMEA, APAC) dimensions, showing the slice, dice, drill down, and roll-up operations.

[![OLAP cube diagram: multi-dimensional array of nested summarizations along time, product, and region dimensions](https://www.ml4devs.com/images/illustrations/olap-cube.webp)](https://www.ml4devs.com/what-is/olap-online-analytical-processing/#what-is-an-olap-cube)

Explainer: [Online Analytical Processing (OLAP) and OLAP Cubes](https://www.ml4devs.com/what-is/olap-online-analytical-processing/)

### SQL vs. NoSQL Comparison Diagram

SQL and NoSQL databases compared on model, data, schema flexibility, transactions, consistency, availability, and scale, plus the four NoSQL types: key-value, wide column, document, and graph.

[![SQL vs. NoSQL comparison diagram: model, data, flexibility, transactions, consistency, availability, and scale, plus the four NoSQL types](https://www.ml4devs.com/images/illustrations/sql-vs-nosql-comparision.webp)](https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/#sql-vs-nosql-database-comparison-diagram)

Article: [SQL vs. NoSQL Database: When to Use, How to Choose](https://www.ml4devs.com/articles/datastore-choices-sql-vs-nosql-database/)

### MLOps Lifecycle Diagram

The machine learning lifecycle drawn as an eternal knot of four interlocking loops: Data (collect, curate, transform, validate), ML (explore, train, evaluate, formulate), Dev (plan, code, build, test), and Ops (release, deploy, operate, monitor).

[![MLOps lifecycle diagram: Data, ML, Dev, and Ops loops of the machine learning lifecycle](https://www.ml4devs.com/images/illustrations/ml-lifecycle-mlops-eternal-knot.webp)](https://www.ml4devs.com/what-is/mlops/#mlops-lifecycle-diagram)

Explainer: [MLOps: A Practical Guide To Production Machine Learning](https://www.ml4devs.com/what-is/mlops/)
