[![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/Numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ff4088.svg?style=flat&logo=plotly&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-%231E90FF.svg?style=flat)](https://seaborn.pydata.org/)
[![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=flat&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=flat&logo=github&logoColor=white)](https://github.com/)



# Supply Chain Data Modelling Streamlit App

A comprehensive, interactive Streamlit app designed for **supply chain analytics and data modelling** in the pharmaceutical industry.

This tool enables **forecasting**, **inventory optimization**, **customer/product segmentation**, and **statistical analysis** — all in one place to support smarter, data-driven decision-making.

---

##  Features at a Glance

###  1. Forecast Future Demand (LSTM Model)
- **Purpose**: Predict future demand using historical sales.
- **Tech**: LSTM Neural Network (Keras)
- **Key Outputs**:
  - Forecast plot for selected SKU (1-year ahead)
  - Mean Absolute Percentage Error (MAPE)
  - Downloadable forecast data

### 📦 2. Inventory Optimisation & Simulation
- **Purpose**: Optimize stock levels with:
  - EOQ (Economic Order Quantity)
  - Safety Stock
  - Monte Carlo Simulation
- **Key Outputs**:
  - EOQ & Safety Stock tables
  - Simulated demand distributions
  - Visualizations for supply chain risk

###  3. Customer & Product Segmentation
- **Purpose**: Identify key products, customers, and supplier performance
- **Key Outputs**:
  - Sales by supplier/category
  - Top/bottom 20 products
  - Customer revenue rankings
  - Stock turnover ratios

### 📊 4. Statistical Hypothesis Testing
- **Purpose**: Validate business hypotheses using 5 statistical tests:
  - Pearson, Spearman, Kruskal-Wallis, Linear Regression, ANOVA
- **Key Outputs**:
  - P-value and hypothesis test results
  - Visuals with rejection zones and test statistics
