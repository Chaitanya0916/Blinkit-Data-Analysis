# 📊 Blinkit Sales Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-lightgrey)

## 🚀 Overview
A comprehensive retail analytics solution analyzing Blinkit's sales data to uncover product performance, customer preferences, and outlet efficiency trends. This project transforms raw sales data into actionable business intelligence through Python-powered visualizations and strategic recommendations.

## 🔍 Key Insights
| Metric | Value | Business Impact |
|--------|-------|-----------------|
| Total Sales | $1.2M | Revenue benchmark |
| Low-Fat Dominance | 65.4% | Inventory adjustment needed |
| Tier 1 vs Tier 3 | 2.3x | Geographic strategy |
| New Outlet Boost | +18% | Expansion planning |
| Missing Weight Data | 17.2% | Data quality initiative |

## 📂 Repository Structure

blinkit-analytics/
├── data/ # CSV datasets (raw + processed)
│ ├── raw/ # Original blinkit_data.csv
│ └── processed/ # Cleaned analysis-ready data
├── notebooks/ # Jupyter notebooks
│ └── Blinkit_Analysis.ipynb # Main analysis notebook
├── reports/ # Business documents
│ └── requirements.pdf # Original project brief
├── visuals/ # Exported charts
│ ├── sales_by_fat.png # Donut chart
│ ├── outlet_performance.png # Bar chart
│ └── yearly_trends.png # Line chart
├── .gitignore
├── LICENSE
├── README.md # This document
└── requirements.txt # Python dependencies



## 🛠️ Installation & Usage
```bash
# Clone repository
git clone https://github.com/yourusername/blinkit-analytics.git
cd blinkit-analytics

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook notebooks/Blinkit_Analysis.ipynb



💡 Business Recommendations
Inventory Optimization: Increase low-fat product stock in Tier 3 locations by 15-20%

Outlet Expansion: Prioritize medium-sized outlets (47.3% revenue share)

Promotional Bundles: Pair high-visibility items with new products

Data Quality: Implement automated weight measurement for 1,463 missing values

Pricing Strategy: Capitalize on 4.0 average rating for premium positioning
