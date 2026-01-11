# 📈 US Business Formation Trends: Forecasting the Future of Entrepreneurship

## 🎯 Project Motivation
📖 **Project Overview**
    This project analyzes the fundamental shift in American entrepreneurship triggered by the COVID-19 pandemic, Identify which state have the highest business growth,Predict future business formation trends across U.S. using data from the **US Census Bureau's Business Formation Statistics (BFS)**. By examining U.S. Census Bureau data, I explored whether traditional linear models could predict the surge in business formation.

By utilizing time-series forecasting, this project aims to provide:
* Identify which state have the highest business growth
* Analyze the impact of economic events (COVID-19) on new business formation. Trends before, during, and after the COVID-19 pandemic.
* State variations in business formation.

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

 
 📝 Read the Full Story on Medium I have published a comprehensive deep-dive into these findings:
 👉 The COVID Catalyst: How the Pandemic Transformed American Entrepreneurship
 
 📊 **Key Findings 1.** 
 1. The Failure of Linear Prediction 
    Traditional Linear Regression models achieved an $R^2$ of near zero (0.012). This "failure" reveals that entrepreneurship is a reactive human phenomenon, not a steady mathematical trend.
 
 2. **The Three Eras of Growth** 
    Our analysis identifies three distinct phases of the American business landscape:
 Pre-2020: Stagnation (-0.13% Growth)
 2020-2021: The Awakening (+12.02% Growth)
 Post-2021: The New Normal (+26.33% Growth)
 
 3. **Corporate Stability**
    Despite the chaos of the pandemic, Corporations demonstrated a remarkable stability index of 0.8, proving that long-term, scalable ventures remained the bedrock of the economy while other sectors fluctuated.
 
 🛠️ **Tech Stack & Methodology**
 Data Source: U.S. Census Bureau Business Formation Statistics (BFS).
 Analysis: Python (Pandas, NumPy).Visualization: Matplotlib, Seaborn.
 Forecasting: Linear regression (Prediction model).
 

💡 **Conclusion**
The pandemic did not just cause a temporary spike; it initiated a fundamental restructuring of the American economy. From D.C.'s corporate surge to the rise of the digital entrepreneur, the data proves that America is more entrepreneurial today than at any point in modern history.

## 🤝 Acknowledgments
* **U.S. Census Bureau:** For providing the public Business Formation Statistics (BFS) dataset.

### 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the main script: `python main_forecast.py`
