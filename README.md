# Movie recommendation System

- Movie Recommendation System Based on Spark

# Setup Procedure

## Phase 1: Overview of the Project Architecture

## Phase 2: Setting Up the Basic Environment

- Virtual Machine: virtualbox
- Operating System: centos7
- Tool: Finalshell
- Host: macOS Big Sur

Setting up MongoDB

Setting up Redis

Setting up ElasticSearch

Setting up Azkaban

Setting up Zookeeper

Setting up Spark

Setting up Kafka

Setting up Flume

## Phase 3: Data Loading Service

- Module: **DataLoader**
- Functions:
  - Load data into MongoDB
  - Load data into Elasticsearch

## Phase 4: Building the Recommendation System

- ### Statistics Recommendation Module

  - Module: **StatisticsRecommender**
  - Implementation: **Spark-SQL**

- ### Collaborative Filtering-Based Offline Recommendation Module

  - Algorithm: **ALS**
  - Module: **OfflineRecommender**
  - Implementation: **Spark-MLlib**

- ### Content-Based Recommendation Module

  - Module: **ContentRecommender**
  - Implementation: **Spark-MLlib**

- ### Real-Time Recommendation Module

  - Module: **StreamingRecommender**
  - Implementation: **Spark- Streaming**

## Phase 5: Building Front and Backend

- No need for manual setup for this part, just use the provided **businessServer**.

