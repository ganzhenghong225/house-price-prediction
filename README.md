## House Price Prediction (King County)

### Overview  
This project analyzes residential housing data from King County, Washington, to identify key factors influencing house prices and to build predictive models.  

The analysis combines exploratory data analysis, feature engineering, and machine learning techniques to improve prediction accuracy.

---

### Problem  
Housing prices are influenced by various structural and location-based factors.  

This project aims to answer:  
- Which features most strongly predict house prices?  
- How accurately can different models estimate prices?  

---

### Approach  

- Data cleaning and preprocessing  
- Handling outliers and unrealistic values  
- Feature engineering (log transformation of price)  
- Exploratory data analysis (EDA)  
- Model building and comparison  

---

### Key Findings  

- House prices are strongly right-skewed, requiring log transformation  
- Living area (sqft_living) is one of the strongest predictors of price  
- Higher construction grade is associated with higher prices  
- Waterfront properties command significantly higher values  

---

### Visualizations  

- Distribution of price and log(price)  
- Relationship between living area and price  
- Price differences by construction grade  
- Correlation heatmap of key variables  

---

### Models Used  

- Ordinary Least Squares (OLS)  
- Ridge and Lasso Regression  
- Random Forest Regression  

---

### Evaluation  

Models were evaluated using:
- Root Mean Squared Error (RMSE)  
- R² score  
- Cross-validation  

---

### Key Insight  

Structural features such as living area, construction quality, and location have the strongest influence on house prices.

---

### Tools Used  

- Python (pandas, numpy)  
- matplotlib, seaborn  
- scikit-learn  

---

### My Contribution  

- Performed full data cleaning and preprocessing  
- Conducted exploratory data analysis and visualization  
- Implemented multiple regression and machine learning models  
- Evaluated model performance and interpreted results  

---

### Note  

Dataset sourced from public housing data (Kaggle).
