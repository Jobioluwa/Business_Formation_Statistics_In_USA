# 📈 US Business Formation Trends: Forecasting the Future of Entrepreneurship

## 🎯 Project Motivation
The goal of this project is to analyze and Identify which state have the highest business growth.
Analyze the impact of economic events (COVID-19) on new business formation.
Predict future business formation trends across U.S. using data from the **US Census Bureau's Business Formation Statistics (BFS)**. 

By utilizing time-series forecasting, this project aims to provide:
* **Predictive Insights:** Anticipating surges in business intent before actual economic formation occurs.
* **Seasonal Analysis:** Identifying which months consistently see the highest entrepreneurial activity.
* **Economic Indicators:** Distinguishing between "High-Propensity" applications (likely to hire employees) and general business filings.

## 🛠️ Libraries Used
The analysis is built using the following Python libraries:
* **JupyterNotebook:** 
* **Pandas:** Essential for data cleaning, filtering by state, and date-time manipulation.
* **Matplotlib:** For visualizing historical trends alongside future confidence intervals.
* **NumPy:** Used for numerical operations during data preprocessing.
* **Scikit-Learn** Used for prediction (Linear Regression)

## 📂 Repository Structure
| File | Description |
| :--- | :--- |
| `data/` | Directory containing the raw and cleaned Census Bureau CSV datasets. |
| `analysis_notebook.ipynb` | A Jupyter Notebook containing exploratory data analysis (EDA) and model tuning. |
| `requirements.txt` | A list of necessary Python packages to run the project. |
| `results/` | Exported PNG charts and CSV forecast predictions for each state. |

## 📊 Summary of Results
The analysis yielded several key takeaways regarding business formation:
* **Model Accuracy:** The linear regression models struggle ($R^2 \approx 0.00$) to predict making the model perform very poorly.
* **Type of Business Application**: Corporation Business formations are the most stable business type.
* **Growth Trends:** (Washington DC state showed the highest average YoY growth 28% in Corporate Business applications over the years.)
* **Pre-COVID (before 2020)**: -0.13% growth -> Business formation was essentially flat/declining slightly.
* **During COVID (2020-2021)**: 12.02% growth -> HUGE jump! Business applications surged during COVID. People started businesses during lockdowns (e-commerce, remote services, side hustles)
* **Post-COVID (after 2021)**: 26.33% growth -> Growth accelerated even more after COVID. The entrepreneurship boom continued and strengthened.
* **A Change of**: +12.15% -> COVID caused a 12% increase in business formation growth rates._




## 🤝 Acknowledgments
* **U.S. Census Bureau:** For providing the public Business Formation Statistics (BFS) dataset.

---
### 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the main script: `python main_forecast.py`
