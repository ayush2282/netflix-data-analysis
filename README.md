# 📊 Netflix Movie Data Analysis

This project explores a movie dataset inspired by Netflix-style content.  
The goal of this project is to clean the data, analyze patterns, and answer business-related questions using Exploratory Data Analysis (EDA).

---

## 📁 Project Structure

├── 01_data_understanding.ipynb  
├── 02_data_preprocessing.ipynb  
├── 03_data_visualization.ipynb  
└── README.md  

---

## 📌 About the Dataset

The dataset contains 9,827 movie records with the following features:

- Release_Date  
- Title  
- Overview  
- Popularity  
- Vote_Count  
- Vote_Average  
- Original_Language  
- Genre  
- Poster_Url  

The dataset does not contain missing values and is relatively clean.

---

## 🔎 Project Workflow

### 1️⃣ Data Understanding
- Checked dataset shape and structure
- Analyzed data types
- Verified missing values
- Observed distribution of numeric features

### 2️⃣ Data Preprocessing
- Converted Release_Date to datetime
- Extracted Release_Year
- Removed duplicates
- Standardized Genre column
- Created Primary_Genre feature
- Dropped unnecessary columns
- Saved cleaned dataset

### 3️⃣ Data Visualization (EDA)
Answered key business questions such as:

- What is the distribution of movie ratings?
- Which genres dominate the dataset?
- Which genres have the highest average rating?
- Does higher rating increase popularity?
- How has movie production changed over time?
- Which languages are most common?

---

## 📊 Key Insights

- Most movies are rated between 6 and 8.
- Drama is the most common genre.
- High quantity does not always mean high quality.
- Vote_Count strongly influences Popularity.
- Movie production increased significantly in recent years.
- English is the dominant language.

---

## 🛠 Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🎯 Project Goal

This project focuses on Exploratory Data Analysis and extracting meaningful business insights from movie data.  
It is designed as a portfolio project to demonstrate data cleaning, analysis, and visualization skills.

---
