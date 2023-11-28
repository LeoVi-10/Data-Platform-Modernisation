
# Data Platform Modernisation



## Overview
XYZ Corp, a prominent Consumer Goods Company specializing in tool manufacturing, is confronted with data availability issues attributed to an Aging Architecture and Operational Silos within their existing on-premises Enterprise Data Warehouse (EDW). The key objectives for their Modern Data Platform initiative encompass:

- Establishing a scalable Data and Analytics Infrastructure on the cloud.
- Overcoming performance bottlenecks and optimizing costs.
- Facilitating diverse data ingestion capabilities.
- Supporting operational and business intelligence reporting.
- Integrating Data Science models across Lines of Business (LOB).
- Assimilating 3rd-party data sources for advanced analytics.

## Current Tech Landscape & Challenges
ABC Corp's on-premises technology stack includes Teradata, IBM Data Manager, SQL Server, and IBM Cognos Report Studio. Challenges include segmented operational metrics and manual reporting processes.

## High-Level Technical Framework
### Cloud-Based Data Platform
- Deployment of cloud infrastructure for scalability and flexibility.
- Adoption of modern tools for seamless data ingestion.
- Implementation of shared infrastructure to boost performance.
- Recommendation of reporting tools (e.g., Power BI, Tableau) and analytics platforms (e.g., Apache Spark).
- Designing the platform to accommodate Data Science model development.

## Infrastructure

### Architecture Diagram
![Architecture](https://github.com/Lovi-10/Data-Platform-Modernisation/blob/main/Architecture%20Diag.PNG?raw=true)


### Tools and Services
#### Data Sources
Twitter, FB, CSV for HR dataset

#### Ingestion
![Kinesis](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_Amazon-Kinesis_16.svg)
![Kinesis Firehose](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_Amazon-Kinesis-Firehose_16.svg)
![EC2](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Compute/16/Arch_Amazon-EC2_16.svg)

#### Raw and Staging Layer
![S3](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Storage/16/Arch_Amazon-Simple-Storage-Service_16.svg)
#### orchestration and ETL
![Glue](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_AWS-Glue_16.svg)
#### Analytics
![Athena](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_Amazon-Athena_16.svg) ![Kinesis Data Analytics](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_Amazon-Athena_16.svg)
#### Dashboarding
![Opensearch](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Analytics/Arch_16/Arch_Amazon-OpenSearch-Service_16.svg)
#### Machine learning
![Sagemaker](https://raw.githubusercontent.com/weibeld/aws-icons-svg/5e0e14e5472f1eefed879d7ea7e1d79652858d14/q1-2022/Architecture-Service-Icons_01312022/Arch_Machine-Learning/16/Arch_Amazon-SageMaker_16.svg)





## Code
<a href='https://github.com/Lovi-10/Data-Platform-Modernisation/blob/main/main.ipynb'>Code</a>
