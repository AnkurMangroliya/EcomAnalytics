# EcomAnalytics

**EcomAnalytics** is an end-to-end **E-commerce Analytics Pipeline** designed to analyze and visualize e-commerce data, providing valuable insights into sales, customer behavior, and product performance. The project leverages PostgreSQL, Python, Docker, and Streamlit to create an efficient pipeline for data ingestion, transformation, and visualization.

---

## **Table of Contents**

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
4. [File Structure](#file-structure)
5. [Steps to Run](#steps-to-run)
6. [Future Enhancements](#future-enhancements)

---

## **Project Overview**

EcomAnalytics provides businesses with an easy-to-implement solution for analyzing e-commerce data. The project includes four main components:

- **Data Ingestion**: Loads data from CSV files into PostgreSQL.
- **Data Transformation**: Aggregates and processes data to generate meaningful insights using SQL queries.
- **Dashboard**: A Streamlit app that visualizes the analytics in an interactive, user-friendly dashboard.
- **Database Setup**: Dockerized PostgreSQL database to store the ingested data.

---

## **Technologies Used**

- **Python**: Data ingestion, transformation, and processing.
- **PostgreSQL**: Database to store customer, product, and order data.
- **Docker**: Containerization for the database.
- **Streamlit**: Web application framework to visualize the data.
- **SQLAlchemy**: ORM for interacting with the PostgreSQL database.

---

## **Getting Started**

### **Prerequisites**

1. **Docker**: Ensure Docker is installed and running on your machine.
2. **Python 3.x**: Ensure Python 3.x is installed.
3. **Streamlit**: Streamlit should be installed in your Python environment.

### **Installation**

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/AnkurMangroliya/EcomAnalytics
   cd EcomAnalytics
