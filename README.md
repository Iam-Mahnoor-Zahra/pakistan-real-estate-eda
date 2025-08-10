# pakistan-real-estate-eda
Exploratory data analysis of Pakistan's real estate listings to uncover price drivers and investment opportunities.

## 📌 Project Overview
This project analyzes property listings from [Zameen.com](https://www.zameen.com) to uncover key trends in the Pakistani real estate market.  
The analysis focuses on **price drivers, city-wise performance, property types, and investment opportunities** for stakeholders such as real estate investors, developers, and policy makers.

The study is implemented in a **Google Colab notebook** and is fully reproducible using the provided dataset.

---

## 📂 Repository Structure
pakistan-real-estate-eda/
│
├── README.md          # Project summary
├── report.pdf         # Full detailed EDA report
├── notebook.ipynb     # EDA code
├── data.csv           # Dataset 
└── requirements.txt   # Python dependencies


---

## 🚀 Features
- **Data Cleaning & Preprocessing** – Handling missing values, removing anomalies, and preparing the dataset for analysis.
- **Feature Engineering** – Creating derived metrics such as `Property Age` and `Luxury Indicator`.
- **Univariate & Bivariate Analysis** – Using histograms, boxplots, scatter plots, and correlation heatmaps.
- **Investment Insights** – Identifying trends in pricing, property demand, and high-return locations.
- **Recommendations** – Actionable suggestions for investors.

---

## 📊 Technologies Used
- **Python** – Data analysis and visualization
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Visual analytics
- **FuzzyWuzzy** – String matching for inconsistent entries
- **Google Colab** – Cloud-based execution

---

## 🔍 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<Iam-Mahnoor-Zahra>/<pakistan-real-estate-eda>.git
   
2. Open the notebook in Google Colab or Jupyter.
3. Ensure the dataset (zameen_property_listings.csv) is in the correct path.
4. Run all cells to reproduce the analysis.
   

📌 Insights & Recommendations
    Karachi & Lahore show the highest property price growth potential in urban areas.
    Luxury properties have a disproportionate impact on average prices; median prices are a better indicator.
    Apartments are becoming more popular in densely populated cities due to land scarcity.
    Investors should monitor area-wise demand before finalizing purchases.

📅 Future Work
    Incorporate time-series analysis to track price changes over years.
    Extend the study with rental yield analysis.
    Build a dashboard for interactive exploration.

📜 License
    This project is licensed under the MIT License.

💡 For questions or collaboration, feel free to open an issue or contact me directly.

