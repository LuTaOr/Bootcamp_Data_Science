# **Laptop Price Prediction Challenge**

## **Overview**
This project was part of a Kaggle competition during my Data Science bootcamp. The goal was to develop a regression model to predict the price of laptops based on their specifications. The dataset included various features such as processor, RAM, storage, screen size, and brand.

---

## **Dataset**
The dataset provided included:

### **Features:**
- `Processor`: CPU brand and model.
- `RAM`: Memory size (in GB).
- `Storage`: Type and size of storage (HDD, SSD).
- `ScreenSize`: Display size (in inches).
- `Brand`: Manufacturer of the laptop.
- Other specifications like GPU, weight, and OS.

### **Target:**
- `Price`: The price of the laptop (in USD).

The data required preprocessing to handle missing values, categorical variables, and outliers.

---

## **Objective**
The objective was to build a regression model that could accurately predict the price of a laptop based on its features. The model was evaluated using **Root Mean Squared Error (RMSE)**.

---

## **Workflow**
### **1. Exploratory Data Analysis (EDA):**
- Identified trends, patterns, and correlations in the dataset.
- Visualized the distribution of prices and other features.
- Detected and handled missing values and outliers.

### **2. Feature Engineering:**
- Encoded categorical variables (e.g., `Processor`, `Brand`).
- Created new features, such as `Price_per_GB_RAM`.
- Normalized numerical features for better model performance.

### **3. Model Development:**
- Tried multiple regression models:
  - **Linear Regression**
  - **Random Forest Regressor**
  - **XGBoost Regressor**
  - **LightGBM Regressor**
- Tuned hyperparameters using cross-validation to minimize RMSE.

### **4. Evaluation:**
- Compared model performance on the validation set.
- Selected the model with the best RMSE score for submission.

---

## **Results**
- **Best Model:** [e.g., LightGBM Regressor]
- **Validation RMSE:** [Insert Score]
- **Kaggle Leaderboard Rank:** [Insert Rank if applicable]

---

## **Key Learnings**
- How to handle categorical and numerical features effectively.
- The importance of feature selection and engineering in predictive modeling.
- Practical experience with hyperparameter tuning and model comparison.

---

## **How to Run**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bootcamp_projects.git
