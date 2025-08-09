
# 🌍 World Population Analysis (2022)

## 📌 Objective
Analyze the global population data by country, region, and income group for the year 2022. The goal is to clean the dataset, generate insights using visualizations, and understand global population distribution trends.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 📁 Dataset
- **Source:** [World Bank Open Data](https://data.worldbank.org/indicator/SP.POP.TOTL)
- **Files Used:**
  - `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`: Contains population data from 1960–2022
  - `Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`: Contains country-wise metadata like region and income group

---

## 🧹 Data Cleaning Steps
- Removed irrelevant columns (like indicators, empty rows)
- Merged population data with metadata using `Country Code`
- Filtered only the data for the year **2022**
- Handled missing values

---

## 📊 Visualizations
1. **Top 20 Most Populated Countries (2022)**  
   Bar chart showing the countries with the highest population.
2. **Population Distribution by Region**  
   Bar chart categorizing total population per region.
3. **Population Distribution by Income Group**  
   Insight into population spread across low, middle, and high-income countries.
4. **Histogram of Country Populations**  
   Shows how population values are spread globally (skewed distribution).

---

## 🔍 Key Insights
- The population is heavily concentrated in a few countries like India and China.
- South Asia and East Asia are the most densely populated regions.
- Low and middle-income countries hold the majority of the global population.
- There’s a huge disparity in population distribution — most countries have under 50 million people.

---

## 📚 What I Learned
- How to perform real-world data cleaning using Pandas
- Importance of merging and filtering datasets
- How to use Seaborn & Matplotlib for clear visual storytelling
- Creating structured, presentable data science notebooks

---

## 📁 Project Structure
```
├── World_Population_Analysis_2022.ipynb
├── README.md
├── API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv
├── Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv
├── charts/
│   ├── top_20_countries.png
│   ├── region_distribution.png
│   ├── income_group_distribution.png
│   └── population_histogram.png
```

---

## ✅ How to Run
1. Clone this repo
2. Open the notebook in Jupyter or VS Code
3. Run all cells to see the visualizations
4. Optional: Export the notebook as PDF using `File > Export As > PDF`
