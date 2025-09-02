# 🍷 Wine Quality Prediction  

This project predicts wine quality (score/classification) using the **UCI Wine Quality Dataset**.  
It applies **Linear Regression** for predicting quality scores and **Logistic Regression** for classifying wines into good/bad categories.  

---

## 📊 Dataset
- Source: [UCI Machine Learning Repository – Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- Two datasets: Red Wine and White Wine  
- Features: 11 chemical properties (e.g., acidity, alcohol, sulfur dioxide, density)  
- Target: Wine quality score (0–10 scale)  

---

## ⚙️ Approach
1. **Data Preprocessing**
   - Merged red & white wine datasets
   - Handled missing values, data types
   - Feature scaling using StandardScaler  

2. **Feature Engineering**
   - Created new feature: `density_sulfur_dioxide_ratio`  
   - Converted categorical `type` (red/white) to numeric  

3. **Visualization**
   - Histograms of wine quality  
   - Correlation heatmap of features vs. quality  
   - Scatter plots for feature relationships  

4. **ML Models**
   - **Linear Regression** → Predicts wine quality score  
   - **Logistic Regression** → Classifies wine as *good* (≥7) or *bad* (<7)  

---

## 🚀 Results
- **Linear Regression**: Evaluated with Mean Squared Error (MSE)  
- **Logistic Regression**: Evaluated with Accuracy & Confusion Matrix  

---

## 📂 Project Structure
