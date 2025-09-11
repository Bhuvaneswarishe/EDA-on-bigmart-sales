# 🛒 BigMart Sales Analysis – EDA & Prediction

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **BigMart Sales dataset** containing information on 1559 products across 10 outlets in different cities.  
The goal is to understand sales patterns, clean and preprocess the dataset, and build a predictive model for **Item Outlet Sales**.  

---

## 🎯 Objectives
- Perform **data cleaning and preprocessing** (handle missing values, encode categorical variables).  
- Explore data distribution, correlations, and relationships between features.  
- Visualize key insights using **Matplotlib & Seaborn**.  
- Build and evaluate a **Machine Learning model** to predict sales.  

---

## 📂 Dataset Information
- **Source:** BigMart Sales Data (2013)  
- **Rows:** 8523  
- **Columns:** 12  

### Key Features
- `Item_Identifier` → Unique product ID  
- `Item_Weight` → Weight of the product  
- `Item_Fat_Content` → Fat type (Low Fat / Regular)  
- `Item_Visibility` → Percentage visibility of the product in the store  
- `Item_Type` → Category of product  
- `Item_MRP` → Maximum Retail Price  
- `Outlet_Size` → Size of the store (Small/Medium/Large)  
- `Outlet_Location_Type` → Tier of the city  
- `Outlet_Type` → Type of outlet (Supermarket/Grocery)  
- `Item_Outlet_Sales` → Target variable (Sales of the product)  

---

## 🛠️ Steps Involved
1. **Data Preprocessing**  
   - Handled missing values (`Item_Weight`, `Outlet_Size`).  
   - Standardized `Item_Fat_Content` categories.  
   - Label encoded categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of items across fat content, categories, and outlet size.  
   - Correlation heatmap to analyze relationships between numerical features.  
   - Visualizations of sales trends across outlets.  

3. **Feature Engineering**  
   - Dropped irrelevant columns (`Item_Identifier`).  
   - Scaled numerical features for consistency.  

4. **Modeling**  
   - Used **Random Forest Regressor** for prediction.  
   - Achieved:  
     - **RMSE:** ~1085.09  
     - **R² Score:** ~0.56  

---

## 📊 Results & Insights
- **Outlet Type & Size** have a significant impact on sales.  
- **Item MRP** strongly correlates with `Item_Outlet_Sales`.  
- Random Forest performed well but further hyperparameter tuning could improve accuracy.  

---

## 💻 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **ML Model:** Random Forest Regressor  

---

## 🚀 Future Enhancements
- Hyperparameter tuning with **GridSearchCV** or **RandomizedSearchCV**.  
- Try other regression models (XGBoost, LightGBM, Linear Regression).  
- Deploy the model with **Flask/Streamlit** for interactive sales prediction.  

---

## 📌 Author
👩‍💻 **Bhuvaneswari S**  
- [GitHub](https://github.com/Bhuvaneswarishe)  
- [LinkedIn](https://linkedin.com/in/bhuvanas5)  

