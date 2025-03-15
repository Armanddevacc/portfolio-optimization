# Porfolio Optimization methods

## Project Overview

### **Methodology**
- **Retrieve Market Data**: Fetch stock prices for selected assets over the last 50 days.
- **Compute Key Metrics**:
  - Expected returns (\(\mu\))
  - Standard deviations (\(\sigma\))
  - Covariance matrix (\(\Sigma\))
- **Optimize Portfolio Weights**:
  - Solve \( w^* = \frac{1}{\lambda} \Sigma^{-1} (\mu - r\mathbf{1}) \)
  - Include a **risk-free asset** for stability.
- **Analyze Portfolio Allocation**:
  - Compare **equal-weighted vs. optimized weights**.
  - Visualize portfolio weight changes using bar charts.

---
## Jupyter Notebook

You can view the Jupyter Notebook [here](https://raw.githubusercontent.com/Armanddevacc/portfolio-optimization/refs/heads/main/portofolio-optimization-methods.ipynb)

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


