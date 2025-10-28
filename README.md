# TASK - 5 Advertising Sales Prediction using Machine Learning

## 📘 Objective
The goal of this project is to develop a machine learning model that predicts **sales revenue** based on advertising expenditure across various media channels such as **TV**, **Radio**, and **Newspaper**.  
This project demonstrates how data-driven decisions can optimize marketing budgets for maximum return on investment.

---

## 🧩 Steps Performed

### 1. **Data Loading**
- Imported the dataset using `pandas`.
- Inspected the structure, shape, and summary statistics.
- Checked for null values, data types, and distribution of each feature.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized the relationship between advertising budgets (TV, Radio, Newspaper) and sales.
- Created **pair plots**, **heatmaps**, and **scatter plots** using `matplotlib` and `seaborn`.
- Identified that **TV advertising** shows the strongest correlation with sales.

### 3. **Data Preprocessing**
- Split the dataset into **training** and **testing** sets using `train_test_split`.
- Applied **StandardScaler** to normalize numerical features.
- Created preprocessing pipelines using `make_pipeline` and `make_column_transformer` for modularity.

### 4. **Model Building**
- Implemented a **Random Forest Regressor** to predict sales.
- Trained the model using the training dataset.
- Tuned model parameters for optimal performance.

### 5. **Model Evaluation**
- Evaluated the model using:
  - **R² Score**
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
- Visualized predicted vs actual sales for better interpretability.

### 6. **Model Saving**
- Saved the trained model using `pickle` for future deployment.
- Enabled easy reusability without retraining.

---

## ⚙️ Tools & Libraries Used
| Category | Tools/Libraries |
|-----------|----------------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine Learning | `scikit-learn` (`RandomForestRegressor`, `Pipeline`, `StandardScaler`, `train_test_split`) |
| Model Saving | `pickle` |

---

## 🏁 Outcome
- Successfully developed a regression model capable of predicting sales based on advertising budgets.
- The **Random Forest Regressor** achieved a high **R² score**, showing strong predictive capability.
- Provided insights into how different media channels contribute to sales performance.
- Demonstrated an end-to-end ML workflow — from EDA and preprocessing to training and saving the model.

---

