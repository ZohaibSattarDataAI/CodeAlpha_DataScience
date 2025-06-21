
# 📈 Sales Prediction using Machine Learning (Random Forest Regressor)

This project focuses on predicting **product sales** using advertising data from TV, Radio, and Newspaper campaigns. It showcases a complete regression pipeline using **Random Forest Regressor**, demonstrating data preprocessing, model training, performance evaluation, and business insights generation.

---

## 📌 What This Project Does

This notebook performs the following tasks:

- **Loads the Advertising Dataset**  
  Reads a `.csv` file containing advertising budgets across TV, Radio, and Newspaper, along with actual sales.

- **Explores and Visualizes the Data**  
  - Displays basic statistics and structure of the dataset  
  - Creates correlation heatmaps, scatter plots, and line plots to understand relationships

- **Preprocesses the Dataset**  
  - Removes unnecessary columns and handles missing values  
  - Selects relevant features using correlation analysis

- **Splits Data into Training and Test Sets**  
  Uses an 80/20 train-test split for robust model evaluation.

- **Trains the Random Forest Regressor**  
  Fits a `RandomForestRegressor` model to learn the relationship between advertising spend and sales.

- **Evaluates the Model**  
  Measures performance using **R² Score**, **MAE**, **MSE**, and **RMSE** on test data.

- **Visualizes Predictions and Trends**  
  - Actual vs. Predicted Sales scatter plot  
  - Prediction lines over TV, Radio, and Newspaper with average values  
  - Bar chart showing feature importance from the trained Random Forest model

- **Generates Business Insights**  
  - Highlights which advertising platforms have the most impact  
  - Recommends marketing strategies based on feature importance

---

## 📁 Dataset Used

- **File**: `Advertising.csv`

### Features:
- `TV`  
- `Radio`  
- `Newspaper`  

### Target:
- `Sales`

---

## 🧠 ML Techniques Used

- Supervised Learning  
- Regression (**Random Forest Regressor only**)  
- Feature Importance Analysis  
- Data Visualization  
- Model Evaluation (R², MAE, MSE, RMSE)

---

## 📊 Output Example

- **Model R² Score (Test Set)**: ~90%–95%  
- **Feature Importance**:  
  - `TV` has the highest influence on Sales  
  - `Radio` shows moderate impact  
  - `Newspaper` contributes the least to predictions

---

## 📚 Learning Outcomes

- End-to-end implementation of a machine learning regression model  
- Practical understanding of feature importance in ensemble models  
- Effective communication of model results and business insights using visuals  
- Real-world experience with **RandomForestRegressor**, **Seaborn**, **Pandas**, and **Matplotlib**

---

## 👨‍💻 Author

**Zohaib Sattar**  
_Data Scientist | Data Analyst | Machine Learning Enthusiast_

📧 Email: [zabizubi86@gmail.com]  
🔗 GitHub: (https://github.com/ZohaibSattarDataAI)  
🔗 LinkedIn:(https://www.linkedin.com/in/zohaib-sattar-5680ab2a5/)

---
