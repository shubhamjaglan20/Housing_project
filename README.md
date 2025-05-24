# 🏠 California Housing Price Prediction

This is a step-by-step guided machine learning project based on the book **"Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron**. The goal is to build a model that predicts California housing prices using various data features.

## 📌 Objective

To create a complete ML pipeline—from loading data to training and evaluating models—on the California housing dataset.

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-Learn

## 📊 Dataset Features

- Longitude, Latitude
- Housing Median Age
- Total Rooms, Total Bedrooms
- Population, Households
- Median Income
- Ocean Proximity (categorical)
- Median House Value (target)

## ⚙️ Workflow

1. **Data Loading and Exploration**  
   - Understanding data structure  
   - Identifying missing values  
   - Visualizing distributions and correlations

2. **Data Cleaning & Preparation**  
   - Handling missing values (median imputation)  
   - Dropping/transforming non-numeric attributes  
   - Creating new features (e.g., `bedrooms_per_room`)  
   - Encoding categorical data using OneHotEncoder  

3. **Pipeline Construction**  
   - Use of `Pipeline` and `ColumnTransformer`  
   - Scaling features using `StandardScaler`  
   - Combining numerical and categorical transformers

4. **Model Training & Evaluation**  
   - Models used: Linear Regression, Decision Tree, Random Forest  
   - Evaluation using RMSE and cross-validation  
   - Discussion of underfitting and overfitting

5. **Model Comparison**  
   - Random Forest performed best but showed signs of overfitting  
   - Cross-validation provided better insight into model generalization  

## ✅ Results

- **Linear Regression**: Underfit the data  
- **Decision Tree**: Overfit with high training accuracy  
- **Random Forest**: Best performance but still some overfitting  

## 📈 Metrics

Evaluation done using Root Mean Squared Error (RMSE) and k-fold cross-validation for reliable performance estimation.

## 🔮 Future Improvements

- Hyperparameter tuning (e.g., GridSearchCV)  
- Adding more derived features  
- Trying different ML models (e.g., SVM, neural networks)

## 🙌 Acknowledgment

Inspired by the book **"Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron**.

## 🔗 GitHub Repo

👉 [View the project on GitHub](https://github.com/shubhamjaglan20/Housing_project)

---

