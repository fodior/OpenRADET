# OpenRADET

Open-source Medallion Data Warehouse for HIV Program Analytics.

## Overview

OpenRADET is designed to transform RADET datasets into analytics-ready structures using a Medallion Architecture.

Layers:

- Bronze → Raw data ingestion
- Silver → Cleansed and standardized data
- Gold → Reporting and analytics marts

## Technology Stack

- PostgreSQL
- Python
- dbt
- Apache Airflow
- Apache Superset
- Docker
- GitHub

## Project Structure

OpenRADET/
├── data/
├── bronze/
├── silver/
├── gold/
├── scripts/
├── sql/
├── models/
├── docs/
├── tests/
├── superset/
├── dags/
├── notebooks/
├── docker/

## Status

Sprint 1 in progress