**🚀 Project Overview**

The Sales Prediction project applies machine learning regression models to forecast product sales based on features such as store type, location, promotions, and time factors.
It is widely useful for:
Demand forecasting
Inventory management
Business decision-making

**📊 Dataset**
You can use:
Kaggle: Store Sales Dataset
Or a custom dataset with columns like:
Store_ID
Product_ID
Date
Promotion
Price
Units_Sold / Sales (Target Variable)
Place your dataset inside the data/ folder (e.g., data/sales.csv).

**🧠 Modeling Approach**

**Data Preprocessing**
Handle missing values
Encode categorical features (store type, product category)
Convert dates into useful features (day, month, year, season)
Scale/normalize numerical features
**Feature Engineering**
Lag features (previous week/month sales)
Rolling averages
Holiday/seasonality effects
**Model Training**
Linear Regression
RandomForestRegressor
XGBoost / Gradient Boosting
Hyperparameter tuning (GridSearchCV/RandomizedSearchCV)

**Install One by One**
pip install pandas<br>
pip install numpy<br>
pip install scikit-learn<br>
pip install xgboost<br>
pip install joblib<br>
pip install flask<br>
pip install matplotlib<br>
pip install seaborn<br>
pip install jupyter<br>

**Dataset Path**
https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input
