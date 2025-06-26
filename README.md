# 🧠 AI & ML Internship – Task 3: Linear Regression

## 🎯 Objective
Implement and understand **Simple & Multiple Linear Regression** using `Scikit-learn`, `Pandas`, and `Matplotlib`.

---

## 📁 Dataset
The dataset used is a simple house price dataset with the following columns:
- `area`: Size of the house (in square feet)
- `price`: Price of the house (in INR)

If the file `house_price_dataset.csv` is not available, a manually created dataset is used in the script.

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ✅ Task Steps

1. **Data Preprocessing**  
   - Loaded dataset  
   - Checked for null values  
   - Selected relevant features

2. **Train-Test Split**  
   - Split dataset into training and testing sets using `train_test_split`

3. **Model Training**  
   - Used `LinearRegression()` from `sklearn.linear_model`

4. **Prediction & Evaluation**  
   - Made predictions on test data  
   - Calculated **MAE**, **MSE**, and **R² Score**

5. **Visualization**  
   - Plotted regression line on test data using `matplotlib`

---

## 📊 Results

| Metric | Value |
|--------|-------|
| MAE    | *(Your Output)* |
| MSE    | *(Your Output)* |
| R² Score | *(Your Output — or mention `nan` if test data < 2 samples)* |

> Note: R² score was `nan` due to having only one sample in the test set. R² requires at least 2 samples to compute variance.

## 📷 Screenshot
*(Include a screenshot of your regression plot here, optional)*
![image](https://github.com/user-attachments/assets/71bce41f-56a8-489d-bca4-21a112d55cea)

