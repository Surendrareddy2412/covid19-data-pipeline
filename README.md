# COVID-19 Data Pipeline

This project is a data pipeline that extracts COVID-19 data from a public API, transforms the data, and loads it into a PostgreSQL database. The pipeline is orchestrated using Apache Airflow.

## Project Overview

The COVID-19 Data Pipeline automates the process of fetching daily COVID-19 statistics from an external API, processing the data, and storing it in a PostgreSQL database for analysis and reporting purposes.

## Features

- Daily extraction of COVID-19 data from a public API
- Data transformation to clean and format the data
- Loading the transformed data into a PostgreSQL database
- Scheduled and managed using Apache Airflow

## Setup

### Prerequisites

- Docker and Docker Compose
- Git
- Basic knowledge of Python

### Installation

1. *Clone the repository:*
   ```bash
   git clone https://github.com/yourusername/covid19-data-pipeline.git
   cd covid19-data-pipeline
