# End-to-End Data Analysis: Hockey League Betting Odds & Insights

This project demonstrates a complete data analytics pipeline—from web scraping and data processing to exploratory data analysis (EDA) and formulating data-driven business recommendations.

### 💼 Business Context
Imagine taking on the role of a Data Analyst at a newly established online sports betting (bookmaker) company. Since the company is new and lacks its own historical database, the goal is to acquire hockey league results from publicly available sources, clean them, analyze team performances, and establish baseline betting odds that can be dynamically updated.

---

## 🛠️ Project Structure & Workflow

The project is structured into 4 sequential stages, mapped to separate Jupyter Notebooks:

1. **`01_DataDownload.ipynb` (Data Acquisition)**
   * Scraping raw HTML match data from the *Scrape This Site* platform using Python (handling requests and pagination).
   * Storing raw web data safely to minimize server load and ensure reproducibility.

2. **`02_DataProcessing.ipynb` (Data Scraping & Parsing)**
   * Parsing HTML pages using text-processing libraries.
   * Extracting key metrics: Team Name, Year, Wins, Losses, OT Losses, Win %, Goals For (GF), Goals Against (GA), and Goal Differential (+/-).
   * Exporting structured data into an interim JSON format.

3. **`03_DataAnalysis.ipynb` (Exploratory Data Analysis - EDA)**
   * Comprehensive EDA using **Pandas** and data visualization with **Matplotlib** / **Seaborn**.
   * Examining team structures, identifying top performers, analyzing win trends, and calculating goal statistics.
   * Exporting the final clean dataset to a structured CSV format.

4. **`04_BusinessRecommendations.ipynb` (Business Intelligence & Risk Management)**
   * Transforming analytical insights into business logic.
   * Creating a framework for calculating baseline betting odds.
   * Segmenting teams into performance categories (A, B, C, D) to evaluate operational risks for a new bookmaker.

---

## 🚀 Key Technologies Used
* **Languages:** Python (3.x)
* **Data Libraries:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Data Formats:** HTML parsing, JSON, CSV
* **Environment:** Jupyter Notebooks

---
*Note: This project was developed as a comprehensive capstone workshop during the Data Analyst certification course at Coders Lab.*
