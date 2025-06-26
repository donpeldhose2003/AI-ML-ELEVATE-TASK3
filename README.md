# 🏠 Task 3: Linear Regression – Housing Price Prediction

## 📌 Objective
To build a **Linear Regression model** to predict **house prices** based on multiple property-related features like area, number of bedrooms, bathrooms, furnishing status, etc.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** – Data handling
- **Scikit-learn** – Linear regression and evaluation
- **Matplotlib** – Visualizing predictions

---

## 📂 Dataset Info
**File**: `Housing.csv`

The dataset contains the following columns:
- `price` (target variable)
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking` (numerical features)
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus` (categorical features)

---

## 🔍 Key Steps

### 1️⃣ Import & Load Data
- Load dataset using `pandas.read_csv`
- Preview the data with `.head()`

### 2️⃣ Encode Categorical Variables
- Used `pd.get_dummies` to convert categorical variables into numerical format.
- `drop_first=True` to avoid multicollinearity.

### 3️⃣ Train-Test Split
- Split data using `train_test_split()` (80% train, 20% test).

### 4️⃣ Train Linear Regression Model
- Fit the model using `LinearRegression()` from scikit-learn.

### 5️⃣ Evaluate the Model
- Metrics:
  - **MAE** (Mean Absolute Error)
  - **MSE** (Mean Squared Error)
  - **R² Score** (Goodness of fit)

### 6️⃣ Visualize Results
- Scatter plot showing **Actual vs Predicted** prices.
- Ideal predictions lie along the red dashed diagonal line.

---

OUTPUT

![Screenshot 2025-06-26 121929](https://github.com/user-attachments/assets/082d01df-fd2b-42a8-885b-39561e54d5d2)


![Screenshot 2025-06-26 121940](https://github.com/user-attachments/assets/bf7c3418-b70c-44cc-bd9b-74bb4577beb4)

