<div align="center">  

# 🎬 Movie Data Analysis  

📊 *Exploratory Data Analysis (EDA) of Movie Dataset using Python*  

![Python](https://img.shields.io/badge/Python-Data%20Analysis-green)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-blue)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)  
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)  

</div>  

---

## 🎯 Project Overview  

This project is focused on **exploring and analyzing a movie dataset** containing **9,827 rows and 9 columns**.  
The dataset includes information such as **movie title, release date, genre, popularity, votes, and ratings**.  

The main goal of this project is to:  

- Understand the **distribution of movies** across genres and years  
- Explore **popularity trends** to identify the most and least popular movies  
- Categorize movies based on **vote averages** into popularity bins  
- Visualize patterns in data to generate actionable insights  

By leveraging **Python libraries** like Pandas, NumPy, Matplotlib, and Seaborn, the project demonstrates the **complete EDA workflow** — from **data loading and cleaning** to **visualization and insights**.  

---

## 🛠️ Tech Stack  

| Tool | Purpose |  
|------|---------|  
| **Python** | Core programming language |  
| **Pandas & NumPy** | Data cleaning, preprocessing, and transformation |  
| **Matplotlib & Seaborn** | Data visualization and statistical plots |  
| **Jupyter Notebook** | Interactive development environment |  

---

## 📂 Dataset  

- **File Name:** `mymoviedb.csv`  
- **Size:** 9,827 rows × 9 columns  
- **Important Columns:**  
  - `Title` – Movie name  
  - `Genre` – One or multiple genres per movie  
  - `Release_Date` – Original release date  
  - `Popularity` – Popularity score  
  - `Vote_Average` – Average rating given by users  
  - `Vote_Count` – Number of user votes  

The dataset was cleaned, preprocessed, and transformed before visualization.  

---

## 🔎 Extended Description of Workflow  

### 1. Data Exploration  
- Loaded the dataset into a Pandas DataFrame  
- Checked data types, missing values, and duplicates  
- Verified overall structure (**9827 rows × 9 columns**)  

### 2. Data Cleaning  
- Converted `Release_Date` into **datetime format** and extracted the **release year**  
- Dropped irrelevant columns: `Overview`, `Original_Language`, `Poster_Url`  
- Ensured consistency by handling multiple genres  

### 3. Data Transformation  
- Categorized `Vote_Average` into 4 bins:  
  - `not_popular`  
  - `average`  
  - `below_average`  
  - `popular`  
- Split multiple genres into separate rows for per-genre analysis  

### 4. Data Visualization & Analysis  
- **Genre Analysis**: Identified the most frequent movie genres  
- **Vote Distribution**: Compared vote averages across popularity categories  
- **Release Trends**: Analyzed movies released over time, discovering a peak around 2021  
- **Popularity Analysis**:  
  - 🎬 *Most Popular Movie*: *Spider-Man: No Way Home* (popularity score: **5083.95**)  
  - 🎬 *Least Popular Movies*: *The United States vs. Billie Holiday* & *Threads*  

---

## 📊 Key Insights  

- The dataset shows a **surge of movie releases in 2021**, indicating a modern bias in the data.  
- Popularity scores are highly skewed, with a few blockbuster movies dominating the dataset.  
- Splitting genres allowed for **multi-genre analysis**, which revealed overlapping trends.  
- Categorizing movies based on `Vote_Average` simplified the interpretation of movie quality.  

---

---

</div>  

---

## 📫 Contact  

👤 **Suraj Budakoti**  
📧 [surajbudakoti11@gmail.com](mailto:surajbudakoti11@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/suraj-budakoti-55a8b2379)  

---

✨ *This project demonstrates how structured EDA helps in extracting business insights from raw data, highlighting the role of Python in data analytics.*  
