# 📊 Netflix Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a Netflix dataset to uncover trends, patterns, and insights about movies and TV shows available on the platform.

The analysis focuses on understanding content distribution, release trends, ratings, genres, and other key features using Python.

---

## 🎯 Objective

* Identify trends and patterns in Netflix content
* Perform summary statistics
* Conduct correlation analysis
* Visualize insights using graphs

---

## 📂 Dataset

* Dataset: Netflix Movies and TV Shows (Updated up to 2025)
* Format: CSV
* Features include:

  * Title
  * Type (Movie/TV Show)
  * Release Year
  * Country
  * Duration
  * Rating
  * Genres (`listed_in`)

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📊 Key Analysis Performed

### 🔹 1. Data Understanding

* Checked dataset structure using `.info()`
* Identified missing values

### 🔹 2. Data Cleaning

* Removed null values
* Fixed column names
* Converted data types

### 🔹 3. Summary Statistics

* Used `.describe()` for numerical and categorical data

### 🔹 4. Trend Analysis

* Content release over years
* Movies vs TV Shows distribution
* Top countries producing content

### 🔹 5. Genre Analysis

* Extracted and analyzed top genres
* Handled multiple genres using string splitting

### 🔹 6. Duration Analysis

* Extracted numeric duration from mixed values
* Analyzed movie duration distribution

### 🔹 7. Correlation Analysis

* Heatmap of numerical features

---

## 📈 Visualizations

* Count plots (Movies vs TV Shows)
* Line plot (Content over years)
* Bar charts (Top countries, genres)
* Histogram (Duration distribution)
* Heatmap (Correlation matrix)

---

## 💡 Key Insights

* 📌 Movies dominate the Netflix catalog compared to TV shows
* 📌 Significant growth in content after 2015
* 📌 USA is the leading content producer
* 📌 Drama and International genres are most popular
* 📌 Most movies fall within 80–120 minutes duration

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/netflix-eda.git
cd netflix-eda
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook or script:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```bash
netflix-eda/
│── netflix_movies_detailed_up_to_2025.csv
│── eda.ipynb
│── README.md
```

---

## 📌 Future Improvements

* Add interactive dashboards (Plotly / Power BI)
* Perform sentiment analysis on descriptions
* Build recommendation system

---

## 👨‍💻 Author

**Savan Patel**

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
