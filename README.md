# Spotify-Data-Pipeline-Spark
A Spotify ETL Pipeline using AWS Lambda, Glue, S3, and Snowflake.

# 🎵 Spotify Data Pipeline Project

## 📌 Overview
This project automates the **ETL (Extract, Transform, Load)** process for **Spotify playlist data** using:
- **AWS Lambda** (Data Extraction)
- **AWS Glue** (Data Transformation)
- **AWS S3** (Storage for raw and transformed data)
- **AWS CloudWatch** (Triggering Lambda)
- **Snowflake** (Data Warehousing & Analytics)
- **Spotify API** (Extracting Music Data)
- **Python & PySpark** (Processing Data in Glue)

## 🚀 Architecture
![Pipeline Diagram](PIPELINE.png)

## 📂 Project Structure
- **`spotify_extract.py`** → AWS Lambda script for extracting data
- **`SPOTIFY-SCRIPT.py`** → AWS Glue script for data transformation
- **`Spotify Data pipeline project.ipynb`** → Jupyter Notebook for testing
- **`SNOWFLAKE-SPOTIFY.pdf`** → Snowflake setup details
- **`SPARK-PROJECT-SOP.pdf`** → Project SOP

## 🛠️ Setup Instructions
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Spotify-Data-Pipeline.git
cd Spotify-Data-Pipeline

