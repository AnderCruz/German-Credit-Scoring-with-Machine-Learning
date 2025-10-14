# German Credit Scoring with Machine Learning

This project was developed by **Nowa Analytics Consulting** and is part of my portfolio for showcasing skills in data science and machine learning for job applications in the analytics domain.

## Project Overview

This notebook aims to **predict the credit risk** of individuals using the **German Credit Data** dataset. The objective is to classify borrowers as either high-risk or low-risk based on various financial and demographic features.

Credit scoring models like this are essential for banks and financial institutions to manage lending risk, reduce defaults, and make data-driven decisions in loan approval processes.

## Dataset Description

The dataset includes information for 1000 individuals and features such as:

* `Age`: Age of the borrower
* `Sex`: Gender
* `Job`: Employment status/type
* `Housing`: Own / Rent / Free
* `Saving accounts` and `Checking account`: Account status
* `Credit amount`: Requested credit amount
* `Duration`: Duration of the loan in months
* `Purpose`: Purpose of the credit
* `Risk`: Target variable (Good or Bad credit risk)

**Source:**
[UCI Machine Learning Repository - German Credit Data](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data)

## Key Components

* **Data Preprocessing:**

  * Handling missing values
  * Encoding categorical variables
  * Feature scaling using `StandardScaler`

* **Exploratory Data Analysis:**

  * Visualizing distributions and correlations using `seaborn` and `matplotlib`
  * Understanding class balance and feature importance

* **Model Building:**

  * Splitting the dataset into training and testing sets
  * Using a `Random Forest Classifier` to predict credit risk

* **Model Evaluation:**

  * Accuracy Score
  * Confusion Matrix
  * Classification Report (Precision, Recall, F1-score)

## Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Seaborn, Matplotlib

## How to Use This Project

1.  Ensure you have all the required libraries installed (`pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`).
2.  Place the `clientes_restaurantes.csv` file in the same directory as the notebook.
3.  Open the `Stasmodel.ipynb` notebook and run the cells sequentially to reproduce the analysis, model training, and forecasting.
