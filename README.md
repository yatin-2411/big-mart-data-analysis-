# big-mart-data-analysis
# 🛒 Big Mart Sales Data Analysis & Prediction

## 📌 Project Overview
This project analyzes **Big Mart sales data** to uncover key insights and predict sales for various products across multiple outlets.  
Using **Machine Learning algorithms** like **Random Forest** and **K-Nearest Neighbors (KNN)**, we aim to identify factors that significantly influence product sales and help optimize inventory management.

---

## 🎯 Objectives
- Perform **exploratory data analysis (EDA)** to understand sales patterns.
- Identify **key factors** affecting sales performance.
- Build and evaluate **predictive models** for sales forecasting.
- Provide actionable insights for **business decision-making**.

---

## 📂 Dataset
- **Source**: Big Mart Sales Dataset (Kaggle)
- **Size**: ~8.5k rows × 12 columns
- **Features**:
  - Item Identifier, Item Weight, Item Type
  - Outlet Identifier, Outlet Size, Outlet Location Type, Outlet Type
  - Item Visibility, Item MRP
  - Item Outlet Sales (Target Variable)

---

## 🔍 Data Analysis & Preprocessing
1. **Data Cleaning**:
   - Handling missing values in `Item_Weight` and `Outlet_Size`
   - Replacing zero values in `Item_Visibility`
2. **Feature Engineering**:
   - Encoding categorical variables (Label Encoding / One-Hot Encoding)
   - Creating new features (e.g., `Item_Category`)
3. **Exploratory Data Analysis (EDA)**:
   - Distribution plots for numeric features
   - Correlation analysis
   - Sales trends across outlets and items

---

## 🤖 Machine Learning Models
### 1. **Random Forest Regressor**
- Captures non-linear relationships and interactions between features.
- Works well for high-dimensional datasets.

### 2. **K-Nearest Neighbors (KNN)**
- Predicts sales based on similarity to nearby data points.
- Useful for capturing local sales patterns.

---

## 📊 Model Evaluation
- **Metrics Used**:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score
- Compared performance between Random Forest and KNN.

---

## 📈 Results & Insights
- **Random Forest** outperformed KNN in prediction accuracy.
- Sales are highly influenced by:
  - **Item MRP**
  - **Outlet Type**
  - **Item Type**
- Larger outlets tend to have higher average sales.
- Some items consistently underperform regardless of outlet.

---

## 🛠️ Tech Stack
- **Languages**: Python
- **Libraries**:
  - `pandas`, `numpy` → Data manipulation
  - `matplotlib`, `seaborn` → Visualization
  - `scikit-learn` → Machine Learning models
  - `jupyter` → Interactive notebook environment

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bigmart-sales-analysis.git
   cd bigmart-sales-analysis
