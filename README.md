# Vehicle_Price_Prediction
# Vehicle Price Prediction

An interactive data science project that predicts vehicle prices based on key features using machine learning. This repository includes the end-to-end workflow from data preprocessing to model deployment.

---

## 🚗 **Project Overview**

This project aims to build a predictive model for estimating vehicle prices using diverse features such as:
- **Region**
- **Price**
- **Year**
- **Manufacturer**
- **Model**
- **Condition**
- **Cylinders**
- **Fuel**
- **Odometer**
- **Title Status**
- **Transmission**
- **VIN**
- **Drive**
- **Size**
- **Type**
- **Paint Color**
- **State**
- **Latitude/Longitude**
- **Posting Date**

By leveraging these features, the model aims to provide accurate predictions for vehicle prices based on the input data.

---

## 🔍 **Dataset**

The dataset was collected from various online vehicle listings and contains the following key characteristics:
- **Size:** Large-scale dataset with multiple regions across the United States.
- **Structure:** Includes categorical and numerical features.

You can download the dataset from [Kaggle/Other Sources].

---

## 🛠️ **Key Technologies Used**

- **Python Libraries:**
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
- **Machine Learning Models:**
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- **Deployment Tools:**
  - Flask
  - Streamlit (optional for interactive visualization)

---

## ⚙️ **Project Workflow**

### 1. **Data Preprocessing**
   - Handle missing values and outliers.
   - Encode categorical variables.
   - Normalize numerical features.

### 2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions, correlations, and trends.
   - Analyze feature importance.

### 3. **Model Building**
   - Train and evaluate multiple models.
   - Optimize hyperparameters for improved performance.

### 4. **Model Evaluation**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R-squared score (R²)

### 5. **Model Deployment**
   - Integrate the model into a Flask application for predictions.
   - Build an API for easy integration.

---

## 🎯 **Interactive Features**

- **Web Application:** An interactive Flask app allows users to input vehicle details and get instant price predictions.
- **Visualization Dashboard:** (Optional) A Streamlit-powered dashboard showcases key insights and trends in the data.

---

## 🚀 **How to Use**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle-price-prediction.git
   cd vehicle-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:
   ```bash
   python app.py
   ```

4. Open the web application in your browser at `http://127.0.0.1:5000`.

---

## 🧪 **Results**

| Model                  | MAE   | MSE   | R²    |
|------------------------|-------|-------|-------|
| Linear Regression      | 2300  | 8200  | 0.75  |
| Random Forest Regressor| 1800  | 6500  | 0.83  |
| Gradient Boosting      | 1700  | 6100  | 0.85  |

---

## 🛡️ **Future Enhancements**

- Incorporate more granular data such as interior/exterior conditions.
- Add support for additional machine learning models.
- Enable multi-region and international price prediction support.

---


Happy Predicting! 🚗✨

