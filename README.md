# Car-Price-Prediction-Module-End-Project-ML-
Car Price prediction model using Regression techniques.( End to End)

## **Project Overview**  
This project aims to build a machine learning model to predict car prices based on various features. The objective is to analyze key factors influencing car prices, preprocess the data, apply feature engineering, train multiple models, and fine-tune the best model for optimal performance.  

## **Workflow**  

### **1. Data Loading and Exploration**  
- Imported the dataset and conducted an initial **Exploratory Data Analysis (EDA)**.  
- Identified key factors influencing car prices, such as **engine size, horsepower, fuel efficiency, and dimensions**.  
- Visualized relationships between features and price to gain insights.  

### **2. Data Preprocessing**  
- **Handled missing values** and corrected inconsistencies in the dataset.  
- **Addressed skewness** in numerical features to ensure a more normal distribution.  
- **Detected and removed outliers** to prevent extreme values from affecting model performance.  

### **3. Feature Engineering**  
- **Feature selection:** Identified and retained the most important variables impacting car prices.  
- **Feature scaling:** Applied standardization techniques to normalize numerical features for better model performance.  

### **4. Model Training and Evaluation**  
- Trained multiple **regression models** (e.g., **Linear Regression, Decision Tree, Random Forest, etc.**).  
- Evaluated models using appropriate metrics such as **R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE)**.  
- Selected the best-performing model based on accuracy and error metrics.  

### **5. Hyperparameter Tuning and Optimization**  
- Performed **hyperparameter tuning** on the best model using techniques like **Grid Search or Randomized Search**.  
- Retrained the model with optimized parameters and re-evaluated its performance.

## Model

The model used for predicting car prices is **GradientBoostingRegressor**, which provides accurate results for regression tasks by combining multiple decision trees to improve prediction accuracy.

## Evaluation Metrics

- **MAE (Mean Absolute Error):** 0.0893
- **MSE (Mean Squared Error):** 0.0145
- **RMSE (Root Mean Squared Error):** 0.1204
- **R² (Coefficient of Determination):** 0.9071

These metrics indicate an improved model after hyperparameter tuning, with the model explaining 90.71% of the variance in car prices.

## Results

After tuning, the model showed better performance than before:

- **Decreased MAE, MSE, and RMSE:** Indicating improved model accuracy.
- **Increased R²:** From 0.9002 to 0.9071, meaning the model explains more variance in the prices.


### **6. Final Model Prediction and Comparison**  
- Used the optimized model to predict car prices on the test dataset.  
- Compared predicted prices with actual values to assess the model’s reliability.  

## **Results and Conclusion**  
- The final model provides **improved accuracy** in predicting car prices after fine-tuning.  
- The analysis highlights **key price-determining factors** and the impact of preprocessing on model performance.  
- This approach demonstrates how machine learning can assist in **pricing strategies** for automobile businesses.  

## **Repository Contents**  
📂 `ML Module end Project (Car Price Prediction).ipynb` – Full Jupyter Notebook with code, analysis, and model training.  
📄 `README.md` – Overview of the project and workflow.  
📊 `Dataset` (if included) – The dataset used for training and testing the model.  

## **How to Use**  
1. Clone the repository:  
   ```bash
   git clone <repository-link>

