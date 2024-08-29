# **GA-MerchInsightsStream**

## **Project Overview**

**GA-MerchInsightsStream** is a data engineering project designed to extract, transform, and visualize data from Google Analytics (specifically, the Google Merchandise Store data). The project uses a combination of tools and technologies to automate the data pipeline, store the data in a PostgreSQL database, and create interactive dashboards for analysis using Streamlit.

## **Project Objectives**

- **Data Extraction**: Pull data from Google Analytics (Google Merchandise Store) using the Google Analytics API.
- **Data Storage**: Store the extracted data in a PostgreSQL database for efficient querying and analysis.
- **Data Orchestration**: Automate the data extraction and loading process using Apache Airflow.
- **Data Visualization**: Develop interactive dashboards using Streamlit to analyze and present insights from the data.
- **Containerization**: Dockerize the services to ensure a consistent and portable development environment.

## **Project Structure**

The project is organized into the following components:

- **data-extraction/**: Contains Python scripts for extracting data from Google Analytics and loading it into PostgreSQL.
- **db/**: Database schema and SQL scripts for setting up the PostgreSQL database.
- **airflow/**: Airflow DAGs for orchestrating the data pipeline.
- **streamlit/**: Streamlit app code for creating interactive dashboards.
- **docker/**: Dockerfiles and docker-compose configurations for containerizing the project components.
- **docs/**: Project documentation, including setup instructions and usage guides.

## **Tools and Technologies**

- **Python**: For scripting data extraction, processing, and visualization.
- **Docker**: To containerize the project and ensure environment consistency.
- **PostgreSQL**: As the database to store the extracted data.
- **Google Analytics API**: To pull data from Google Merchandise Store.
- **Streamlit**: To create interactive dashboards for data analysis.
- **Apache Airflow**: To manage and schedule data pipelines.
- **Canva**: For designing project visuals and banners.
- **GitHub**: Version control and project collaboration.

## **Getting Started**

### **Prerequisites**

Before you begin, ensure you have the following installed:

- Docker
- Python 3.8+
- PostgreSQL
- Google Analytics API credentials
- Apache Airflow

### **Installation**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/GA-MerchInsightsStream.git
   cd GA-MerchInsightsStream
