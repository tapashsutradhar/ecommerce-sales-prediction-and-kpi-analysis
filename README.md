# ecommerce-sales-prediction-and-kpi-analysis
Ecommerce Sales Prediction &amp; Product Insights project using ML and data analysis. Includes sales forecasting, KPI extraction, product performance ranking, segmentation (old/new/offer zone), dashboards, API, Streamlit app, and automated HTML/PDF reporting.

📊 Amazon Sales Prediction & Product Performance Analysis

This project focuses on analyzing Amazon product sales data to uncover actionable insights and predict future sales trends. Using data-driven techniques, the project identifies key performance indicators (KPIs), evaluates product performance, and segments items to support strategic decision-making for e-commerce businesses.

🔍 Project Overview
The goal of this analysis is to:
  •  Predict future sales using machine learning models.
  •  Identify the most profitable and best-selling products.
  •  Detect underperforming and low-selling items.
  •  Analyze key KPIs that directly impact sales performance.
  •  Segment products into old vs. new, offer zone, and high-priority categories for targeted marketing and inventory decisions.

Project Objectives
  •   Predict future sales using machine learning models.
  •   Identify most profitable products and best-selling items.
  •   Highlight low-selling or non-moving stock for optimization.
  •   Extract key KPIs that significantly influence sales performance.
  •  Segment products into:
      •  Offer Zone
      •  Old Products
      •  New Products

📦 Provide actionable insights for pricing, promotions, and inventory planning.

📈 Key Features
  •  Sales Prediction Model:
  Implements regression-based or time-series ML models to forecast upcoming sales based on historical data.
  •  Profitability Analysis:
  Determines which products generate the highest revenue and profit margins.
  •  KPI Identification:
  Extracts and analyzes important metrics such as:
    •  Conversion rate
    •  Product rating & reviews
    •  Pricing trends
    •  Discount impact
    •  Inventory turnover
  •  Best & Worst Performing Products:
  Highlights products with:
    •  High sales volume
    •  Low performance or zero-movement stock
    •  Seasonal demand patterns
  •  Product Segmentation:
  Categorizes the catalog into:
    •  Offer Zone Products – items currently under discounts or promotions
    •  Old Products – long-listed items with declining sales
    •  New Products – recent listings requiring performance benchmarking

📁 Repository Structure

📦 Amazon-Sales-Analysis
├── 📊 data/                 # Raw and processed datasets
├── 📘 notebooks/            # Jupyter notebooks for analysis & modeling
├── 🧠 models/               # Saved ML models (optional)
├── 📈 visuals/              # Charts, plots, and graphs
├── 📄 README.md             # Project documentation
└── 🧩 src/                  # Python scripts for EDA, modeling, utilities


Key Features
🔍 Exploratory Data Analysis (EDA)
Sales trends over time
Category-wise and product-wise performance
Review and rating impact
Pricing and discount analysis
Correlation analysis of KPIs

🤖 Machine Learning: Sales Prediction
Implements ML models such as:
Linear Regression
Random Forest
XGBoost
Time-Series Forecasting
Used to forecast product sales based on historical patterns and KPIs.

💡 Profitability & Performance Insights
Top-performing and high-revenue products
Underperforming items with low or zero sales
Price sensitivity and discount effectiveness
Inventory and sales velocity trends

🏷️ Product Segmentation
New Products – recently listed, performance evaluation
Old Products – legacy listings with stagnating or dropping sales
Offer Zone – discounted items and promotional performance

🛠️ Tech Stack
Python (Pandas, NumPy, Scikit-Learn, Matplotlib/Seaborn)
Jupyter Notebook / Google Colab
Machine Learning: Regression, Time-series Forecasting
Data Visualization & Exploratory Data Analysis (EDA)

📚 Outcome
This repository helps businesses and data analysts:
  •  Make informed decisions on inventory planning.
  •  Optimize pricing and promotional strategies.
  •  Identify high-value products and remove low-selling items.
  •  Improve demand forecasting accuracy.

▶️ How to Run the Project

1. Clone the repository:
git clone https://github.com/yourusername/Amazon-Sales-Analysis.git

2. Navigate to the project folder:
cd Amazon-Sales-Analysis

3. Install required packages:
pip install -r requirements.txt

4. Open Jupyter Notebook:
jupyter notebook

5. Run the analysis workflow inside the notebooks/ folder.

📚 Results & Outcomes
This project enables businesses to:
Improve demand forecasting
Identify profitable products and eliminate poor performers
Optimize pricing and promotional strategies
Enhance inventory management
Track performance using well-defined KPIs

🤝 Contributing
Contributions are welcome!
Please open an issue or submit a pull request for suggestions or improvements.

📜 License
This project is licensed under the MIT License.
