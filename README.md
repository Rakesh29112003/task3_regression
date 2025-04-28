# Task 3: Linear Regression on Housing Prices

## 📚 Objective
Implement and understand **Simple** and **Multiple Linear Regression** to predict house prices.

---

## 🛠 Tools Used
- **Python**
- **Pandas** — for data handling
- **Scikit-learn** — for model building and evaluation
- **Matplotlib** — for visualization

---

## 🗂 Dataset
- **Filename:** `Housing.csv`
- **Features Used:**
  - `area`
  - `bedrooms`
  - `bathrooms`
  - `stories`
  - `parking`
- **Target:** `price`

---

## 🧪 Steps Performed

1. **Import and preprocess dataset**  
   - Loaded CSV using Pandas
   - Selected important features and target

2. **Feature Scaling**  
   - Standardized features using `StandardScaler` for better performance

3. **Polynomial Feature Expansion**  
   - Added quadratic and interaction terms to capture non-linear relationships

4. **Split dataset into Train and Test sets**  
   - 80% Training, 20% Testing

5. **Model Training**  
   - Fitted a `LinearRegression` model using the expanded feature set

6. **Evaluation Metrics**  
   - **MAE (Mean Absolute Error)**
   - **MSE (Mean Squared Error)**
   - **R² (R-squared Score)**

7. **Visualization**  
   - Plotted **Actual vs Predicted Prices** for visual inspection

---

## 📊 Results

| Metric | Value |
|:---|:---|
| MAE | *Depends on your run (expected lower after scaling and polynomial features)* |
| MSE | *Lower than initial model* |
| R²  | *Expected around 0.85 - 0.90* |

✅ **Performance improved significantly** after using scaling + polynomial expansion.

---

## 📈 Visualization

The plot compares actual house prices with predicted values:

- **Perfect predictions** lie on the red dashed line.
- **Scatter** shows model performance — closer = better.

---

## 📌 How to Run

1. Install required libraries:

   ```bash
   pip install pandas scikit-learn matplotlib
