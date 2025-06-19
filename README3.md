# 🚗 Car Price Prediction using Machine Learning

This project focuses on predicting the **selling price of used cars** using machine learning techniques. It is a beginner-friendly regression-based data science project that demonstrates the full workflow of building a price prediction model — from data preprocessing to model evaluation and visualization.

---

## 📌 What This Project Does

This notebook performs the following steps:

- **Loads the Car Dataset**  
  Reads the `.csv` file containing car attributes such as brand, fuel type, kilometers driven, year, and more.

- **Explores the Data**  
  Uses visualizations (like `pairplot` and scatter plots) to analyze relationships between features and the target variable.

- **Preprocesses the Dataset**  
  - Checks and handles missing values  
  - Encodes categorical features like `Car_Name`, `Fuel_Type`, `Transmission`, and `Selling_type` using `LabelEncoder`

- **Splits Data into Train and Test Sets**  
  Uses 80% of the data for training and 20% for testing.

- **Trains a Machine Learning Model**  
  Applies a **Random Forest Regressor** to predict the selling price of cars based on input features.

- **Evaluates the Model**  
  Calculates regression evaluation metrics such as **R² Score**, **MAE**, **MSE**, and **RMSE**.

- **Visualizes Results**  
  - Plots actual vs. predicted prices  
  - Adds a perfect prediction reference line  
  - Visualizes Present Price vs. Selling Price relationship

- **Predicts New Samples**  
  Uses a custom input array to predict the selling price of a new car.

---

## 📁 Dataset Used

- **Dataset**: `car data.csv`

### Features:
- Car_Name  
- Year  
- Present_Price  
- Kms_Driven  
- Fuel_Type  
- Transmission  
- Selling_type  
- Owner  

### Target:
- **Selling_Price**

---

## 🧠 ML Techniques Used

- Supervised Learning  
- Regression (**Random Forest Regressor**)  
- Label Encoding  
- Train/Test Split  
- Model Evaluation Metrics (R², MAE, MSE, RMSE)

---

## 📊 Output Example

- **Model R² Score (Test Set)**: ~88–95%  
- **Predicted Price**: Given `[69, 2017, 12.50, 9000, 1, 0, 1, 0]`, the model predicts the car's selling price accurately.

---

## 📚 Learning Outcomes

- Complete implementation of a machine learning pipeline for regression tasks  
- Hands-on experience with **Scikit-learn**, **Seaborn**, **Pandas**, and **Matplotlib**  
- Understanding of real-world machine learning applications for price prediction  
- Exposure to encoding, training, testing, evaluating, and visualizing ML models  

---

## 👨‍💻 Author

**Zohaib Sattar**  
Data Scientist | Data Analyst | Machine Learning Enthusiast  

📧 Email: [zabizubi86@gmail.com]
🔗 GitHub: (https://github.com/ZohaibSattarDataAI)  
🔗 LinkedIn:(https://www.linkedin.com/in/zohaib-sattar-5680ab2a5/)

