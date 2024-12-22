# DataPipeline-Kafka-OpenWeatherAPI
# Realtime Data Streaming Data Engineering Project | OpenWeather API | Kafka + Spark

## Table of Contents
- [Introduction](#introduction)
- [System Architecture](#system-architecture)

## Introduction

This project serves as a comprehensive guide to building an end-to-end data engineering pipeline. It covers each stage from data ingestion to processing and finally to storage, utilizing a robust tech stack that includes Python, Apache Kafka, Apache Zookeeper, and Apache Spark. Everything is containerized using Docker for ease of deployment and scalability.

## System Architecture

![OpenWeatherAPI-kafka](https://github.com/user-attachments/assets/c9ac11d3-1c4b-46fb-9314-0977256e4b2e)



The project is designed with the following components:

- **Data Source**: We use `openweather` API to generate weather data for our pipeline.
- **Apache Kafka and Zookeeper**: Used for streaming data to the processing engine.
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Apache Spark**: For data processing with its master and worker nodes.

## Technologies

- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Docker

## Getting Started

1. Run Docker Compose to spin up the services:
    ```bash
    docker-compose up
    ```

2. Run data pipeline by jupter Notebook
    OpenWeatherAPI_Kafka.ipynb

3. Other 2 data pipelines with Spark and Pandas
    OpenWeatherAPI_Spark.ipynb, OpenWeatherAPI_Pandas.ipynb
