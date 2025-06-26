
---

# Ecommerce-Customer-Spending-Analysis

Data analysis and predictive modeling to help an Ecommerce company optimize its mobile app and website for increased customer spending.

## Overview

This repository contains a data analysis and predictive modeling project for an Ecommerce company that sells clothing online and offers in-store style advice sessions. The goal is to determine whether the company should focus on improving its mobile app experience or website to increase the Yearly Amount Spent per customer, or if another aspect (e.g., membership length) is more critical.

## Project Description

The project uses a dataset (Ecommerce_Customers.csv) with information about customers, including:
- Average session length of in-store style advice sessions
- Time spent on the mobile app
- Time spent on the website
- Length of membership
- Yearly amount spent (target variable)

The analysis includes exploratory data analysis (EDA) to understand data distributions and correlations, followed by two predictive models:
- **Simple Linear Regression:** Using Length of Membership as the primary predictor.
- **Multivariate Linear Regression:** Incorporating multiple features to assess their combined impact.

## Installation

To run the code, ensure you have the following dependencies installed:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Install the required libraries using pip:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:
```sh
git clone https://github.com/KaanDRoid/ecommerce-customer-analysis.git
```
2. Navigate to the project directory:
```sh
cd ecommerce-customer-analysis
```
3. Ensure the Ecommerce_Customers.csv file is in the directory (download it from the provided source or use the included dataset if available).
4. Run the Jupyter Notebook:
```sh
jupyter notebook Ecommerce_Customer_Analysis.ipynb
```
5. Follow the notebook cells to execute the analysis and view results.

## Results

- **Exploratory Data Analysis:** Identified key correlations (e.g., Length of Membership strongly correlates with Yearly Amount Spent).
- **Model Performance:** The multivariate model outperformed the simple model, with a lower MSE and higher R² score.
- **Recommendation:** The company should prioritize enhancing the mobile app experience and customer retention strategies to boost spending.

## Files

- `Ecommerce_Customer_Analysis.ipynb`: The main Jupyter Notebook containing the analysis and modeling code.
- `Ecommerce_Customers.csv`: The dataset used for analysis 
## Contributing

Feel free to fork this repository, submit issues, or create pull requests if you have suggestions or improvements.

## License

This is an academic project for educational purposes only.

## Acknowledgments

Inspired by data science exercises for predictive modeling.

---

