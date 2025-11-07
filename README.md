🏡 California Housing Price Prediction

This project uses **Machine Learning** to predict median house prices in California based on census and geographical data.  
The model applies data preprocessing, feature transformation, and a **Random Forest Regressor** to predict housing prices.


📊 Dataset
The dataset used is the **California Housing Dataset**, originally from the 1990 U.S. Census, available through Scikit-learn or other sources.  
It contains information such as:
- Median income
- Housing median age
- Average number of rooms
- Latitude and longitude
- Proximity to the ocean
- Median house value (target variable)

---

⚙️ Workflow

# 1. Data Preprocessing
- Handled missing values using `SimpleImputer`
- Scaled numerical features with `StandardScaler`
- Encoded categorical variables (`ocean_proximity`) using `OneHotEncoder`
- Created income categories for stratified sampling

# 2. Model Building
- Built a preprocessing pipeline using `ColumnTransformer` and `Pipeline`
- Trained a `RandomForestRegressor` model
- Evaluated model using RMSE and cross-validation

# 3. Model Deployment (Saved Artifacts)
- Saved the trained model as `housing_model.pkl`
- Saved preprocessing pipeline as `housing_pipeline.pkl`
- Both can be loaded later for inference on new data



 🧰 Tech Stack
- Python 
- NumPy
- Pandas
- Scikit-learn
- Joblib


🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/California-Housing-Price-Prediction.git
   cd California-Housing-Price-Prediction
