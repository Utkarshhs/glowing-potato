# California Housing Price Prediction

An end-to-end machine learning project that predicts median house values in Californian districts based on the 1990 census data. 

## Overview
This project processes geographical and demographic data to build a predictive regression model. It includes data cleaning, feature engineering (handling categorical text attributes and missing values), and training a Random Forest Regressor using a Scikit-Learn Pipeline.

## Key Features
* **Data Pipeline:** Utilizes Scikit-Learn's `Pipeline` and `ColumnTransformer` to seamlessly handle both numerical scaling (`StandardScaler`) and categorical encoding (`OneHotEncoder`).
* **Model Training:** Implements a `RandomForestRegressor` to capture complex, non-linear relationships in the housing data.
* **Geographical Visualizations:** Includes geospatial scatter plots mapping population density and median house values.

## Installation & Setup

**Clone the repository:**
   ```bash
   git clone https://github.com/Utkarshhs/glowing-potato.git
   cd glowing-potato
  ```

**Install dependencies:**
   ```bash
   pip install -r requirements.txt
 ```

To train the model and generate predictions, run the main production script:
```bash
python final_production.py
```

Note: if you're using jupyter notebook then first run:
```bash
jupyter nbconvert --to script final_production.ipynb
```
Then run:
```bash
python final_production.py
```
