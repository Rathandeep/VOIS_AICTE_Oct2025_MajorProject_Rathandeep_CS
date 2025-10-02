# 📊 Netflix Content Trends Analysis

This project analyzes the **Netflix Dataset** (7,789 records, 11 columns) to uncover content trends and provide **strategic recommendations**. It is developed as a **major internship project** to explore **data cleaning, EDA, and visualization techniques** using Python.

---

## 📌 Problem Statement

Netflix is a leading global streaming platform but faces tough competition from Amazon Prime, Disney+, and regional OTT providers.
The objective of this project is **Content Trends Analysis for Strategic Recommendations**:

* Analyze the distribution of Movies vs. TV Shows.
* Study how content genres have evolved over the years.
* Compare country-wise contributions to Netflix’s catalog.
* Provide actionable insights for content strategy.

---

## 🗂 Dataset

* **Rows:** 7,789
* **Columns:** 11
* **Attributes:** Show ID, Title, Director, Cast, Country, Release Date, Rating, Duration, Type (Movie/TV Show), Category (Genre), Description.
* Covers **2008–2021** across multiple countries and genres.

---

## 🔧 Technologies Used

* **Python 3**
* **Libraries:**

  * `pandas` → Data manipulation
  * `numpy` → Numerical processing
  * `matplotlib` & `seaborn` → Data visualization

---

## 🧹 Project Workflow

1. **Data Cleaning**

   * Removed duplicates & handled missing values
   * Converted dates to `datetime`
   * Extracted year & cleaned duration field

2. **Exploratory Data Analysis (EDA)**

   * Distribution of Movies vs. TV Shows
   * Trends in releases over the years
   * Country-wise contributions
   * Popular genres

3. **Visualization**

   * Count plots, bar plots, time-series trends
   * Top genres & countries
   * Release year analysis

4. **Insights & Recommendations**

   * Strategic content gaps
   * Genre focus areas
   * Country contributions

---

## 📊 Example Visualizations

* Movies vs TV Shows distribution
* Content release trend (2008–2021)
* Top 10 contributing countries
* Top genres on Netflix

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/netflix-analysis.git
   cd netflix-analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open and run **Netflix_Analysis.ipynb**

---

## ✅ Expected Outcomes

* Clear understanding of Netflix’s evolving content strategy
* Identification of top-performing genres and countries
* Recommendations for Netflix’s future content acquisition & production

---

## 📌 Author

* **Rathan Deep CS**
* Internship Major Project – *Netflix Content Trends Analysis*
