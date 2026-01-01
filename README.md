# Smart Fleet Management System (AWS)
## Overview

The Smart Fleet Management System is a cloud-native, event-driven solution built on AWS to monitor, analyze, and optimize vehicle fleet operations using real-time telemetry data.

#### Key Features

Real-time vehicle tracking

Automated maintenance alerts

Fuel consumption analytics

Historical data analysis

Predictive maintenance

Architecture Overview

![Architecture-Flow](architecture/architecture-diagram-(4).gif).

#### Technology Stack

AWS IoT Core – Vehicle telemetry ingestion

Amazon S3 – Raw data lake

AWS Lambda – Event-driven processing

Amazon DynamoDB – Real-time operational data

Amazon Athena – Analytics and querying

Power BI / QuickSight – Dashboards

Amazon SageMaker (Optional) – Predictive maintenance

Data Flow
Vehicles → AWS IoT Core → IoT Rules
   ├── S3 (Historical Data)
   ├── Lambda (Alerts)
   └── DynamoDB (Live State)


#### Setup (High Level)

Create AWS IoT Core things and certificates

Configure IoT Rules for S3, Lambda, DynamoDB

Deploy Lambda functions

Create DynamoDB table

Configure Athena tables

Build dashboards

#### Use Cases

Logistics and delivery companies

Public transport operators

Vehicle leasing firms

Fleet service providers

#### Skills Demonstrated

AWS Solutions Architecture

IoT ingestion

Serverless design

Data lake architecture

Event-driven systems

Cost and scalability trade-offs

Author

Emmanuela.
