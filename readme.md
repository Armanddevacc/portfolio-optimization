# 📊 Portfolio Optimization using Mean-Variance Analysis

Welcome to the **Portfolio Optimization** project! This repository implements **Mean-Variance Optimization** based on **Markowitz’s Modern Portfolio Theory (MPT)** to determine optimal asset allocation for a portfolio.

🔗 **Live Notebook (GitHub Pages)**:  
 [View Portfolio Optimization Methods](https://armanddevacc.github.io/portfolio-optimization/portfolio-optimization-methods.html)

---

## 📌 Project Overview

### **🔹 What is Mean-Variance Optimization?**
- Mean-Variance Optimization (MVO) helps investors **maximize expected return** while **minimizing risk**.
- It is based on the **expected return (μ)**, **volatility (σ)**, and **correlation** between assets.

### **🔹 Key Features Implemented**
✅ **Market Data Retrieval**: Fetching stock price data over a recent period.  
✅ **Expected Return & Risk Estimation**: Computing **μ and σ** for each stock.  
✅ **Covariance Matrix Calculation**: Estimating risk relationships between assets.  
✅ **Optimization Using MVO**: Mean-Variance Optimization.  
✅ **Comparison of Equal vs. Optimized Weights** with **Visualizations**.  
✅ **GitHub Pages Integration** to display the notebook online.  

---

---

## Steps to set up the environment and install the required libraries
1. Installing uv                            
    `pip install uv`

2. Create a virtual environment with Python 3.10 
    Note: Use a virtual environment with Python 3.10 for this program.
    `uv venv --python 3.10`

3. Activate the virtual environment
    `source .venv/bin/activate`
    `.venv\Scripts\activate` for Windows

4. Specify required python libraries in requirements.txt

5. Install required python libraries 
    `uv pip install -r requirements.txt`


