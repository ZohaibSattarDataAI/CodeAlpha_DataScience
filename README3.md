🚗 Car Price Prediction using Machine Learning
This project aims to predict the selling price of used cars using machine learning techniques. It’s a practical and beginner-friendly regression project that demonstrates the complete data science workflow — from preprocessing and feature engineering to model training, evaluation, and visualization.

📌 What This Project Does
This notebook performs the following key steps:

Loads the Car Dataset
Reads the .csv file containing car features such as brand, mileage, fuel type, transmission, etc.

Explores the Data
Uses visual tools (like pairplot, scatterplots) to understand feature relationships and patterns.

Preprocesses the Dataset

Checks for null values

Encodes categorical variables (Fuel_Type, Car_Name, etc.) using LabelEncoder

Splits Data into Train and Test Sets
Uses an 80/20 split for training and testing the model using train_test_split.

Trains a Machine Learning Model
Applies RandomForestRegressor to learn from the features and predict selling prices.

Evaluates the Model
Calculates R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

Visualizes Results

Actual vs. Predicted Selling Price Scatter Plot

Selling Price vs. Present Price Analysis

Red Perfect Prediction Line for performance clarity

Predicts New Samples
Takes custom input (e.g., car features) and predicts the expected price using the trained model.

📁 Dataset Used
Dataset: car data.csv

Features:
Car_Name

Year

Present_Price

Kms_Driven

Fuel_Type

Transmission

Selling_type

Owner

Target:
Selling_Price

🧠 ML Techniques Used
Supervised Learning

Regression (Random Forest Regressor)

Label Encoding

Train/Test Split

Model Evaluation Metrics (MAE, MSE, RMSE, R²)

📊 Output Example
Model R² Score (Test Set): ~88–95% depending on random state

Predicted Price: For custom input [69, 2017, 12.50, 9000, 1, 0, 1, 0], the model returns the predicted selling price.

📚 Learning Outcomes
Full understanding of a regression-based ML pipeline

Real-world application of machine learning in price prediction

Hands-on with Scikit-learn, Seaborn, Pandas, and Matplotlib

Experience with data visualization, feature encoding, and performance evaluation

👨‍💻 Author
Zohaib Sattar
Data Scientist | Data Analyst | Machine Learning Enthusiast

📧 Email: zabizubi86@gmail.com
🔗 GitHub: github.com/ZohaibSattarDataAI
🔗 LinkedIn: LinkedIn Profile


