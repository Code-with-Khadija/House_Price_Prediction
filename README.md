# **House Price Prediction using Regression**

## **Overview**
This project aims to **predict house prices** using **regression techniques**. The dataset used is the **Boston Housing Dataset**, which contains various **features affecting house prices**. The model is built using **XGBoost Regressor**, a powerful machine learning algorithm for **regression tasks**.

## **Features Used**
The dataset includes **various attributes** such as:
- **CRIM**: Per capita **crime rate** by town
- **ZN**: Proportion of **residential land** zoned for large lots
- **INDUS**: Proportion of **non-retail business acres** per town
- **RM**: **Average number of rooms** per dwelling
- **AGE**: Proportion of **owner-occupied units** built before 1940
- **TAX**: **Property tax rate**
- **PTRATIO**: **Pupil-teacher ratio** by town
- **LSTAT**: % of **lower status population**
- **MEDV**: **Median value** of owner-occupied homes (**Target variable**)

## **Libraries Used**
The project is implemented in **Python** using the following **libraries**:
- **NumPy**: For **numerical operations**
- **Pandas**: For **data manipulation**
- **Matplotlib & Seaborn**: For **data visualization**
- **Scikit-learn**: For **machine learning utilities** (train-test split, metrics)
- **XGBoost**: **Powerful regression model**

## **Workflow**
1. **Data Loading**: Load the **Boston Housing dataset**.
2. **Data Preprocessing**: Handle **missing values** and perform **feature selection**.
3. **Exploratory Data Analysis (EDA)**: **Visualize relationships** between features using **graphs and heatmaps**.
4. **Model Training**: Train the **XGBoost Regressor** on the dataset.
5. **Model Evaluation**: Assess **model performance** using metrics like **RMSE and R² score**.

## **How to Run**
1. Install required libraries using:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```
2. **Run the Jupyter Notebook** or **Python script**.
3. View the **predictions and model performance metrics**.

## **Results**
- The model provides **accurate house price predictions** with **minimal error**.
- **XGBoost outperforms traditional regression techniques** due to its **boosting capabilities**.

## **Future Improvements**
- **Experiment with different regression models** to compare results.
- **Feature engineering** to enhance **predictive accuracy**.
- **Hyperparameter tuning** for **better performance**.
- **Deploying the model** using **Flask or FastAPI** for real-world usability.

## **Author**
**Khadija Ijaz**

