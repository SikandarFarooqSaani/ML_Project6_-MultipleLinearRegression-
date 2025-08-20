# 🔢 First Multiple Linear Regression Project

This project is about applying **Multiple Linear Regression (MLR)** on a synthetic dataset created using Scikit-Learn.  
The main goal was to understand how regression works with more than one feature, and to visualize the results in **3D**.  

---

## 🚀 Project Steps

### 1. Importing Libraries
- Imported necessary libraries for dataset creation, data handling, and visualization.  
- Used `sklearn.datasets`, `pandas`, and `plotly.express`.  

### 2. Creating the Dataset
- Generated synthetic data with `make_regression`:  
  - **Samples:** 100  
  - **Features:** 2 (feature1, feature2)  
  - **Target:** 1  
  - **Noise:** 50  
- Converted data into a DataFrame with columns:  
  - `feature1`  
  - `feature2`  
  - `target`  

### 3. Data Visualization
- Plotted the dataset in **3D** (feature1, feature2, target) using Plotly to see the hyperplane.  
- Also plotted:  
  - **Feature1 vs Target** (looked more linear)  
  - **Feature2 vs Target** (less linear)  

### 4. Splitting the Data
- Applied **train-test split (80:20)**.  

### 5. Training the Model
- Created a **Linear Regression** object from Scikit-Learn.  
- Fitted the model on training data.  

### 6. Model Evaluation
- **Mean Squared Error (MSE):** `1475.31`  
- **Mean Absolute Error (MAE):** `28.68`  
- **R² Score:** `0.78`  

### 7. Visualizing the Hyperplane
- Plotted the regression hyperplane in **3D** using code from an LLM.  
- Helped in illustrating how the regression plane fits the dataset.  

### 8. Coefficients & Intercept
- **Coefficients:** `97.73`  
- **Intercept:** `3.33`  

---

## 📈 Results

- The regression model explains **78% of the variance** in the target.  
- Error values are moderate due to added noise in the dataset.  
- Visualization gave a clear view of how both features influence the target.  

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas**  
- **NumPy**  
- **Plotly Express**  
- **Scikit-Learn**  

---

## 📌 Conclusion

This was the **first step into Multiple Linear Regression**.  
- We learned how multiple features together can predict a target.  
- Visualized regression in 3D to better understand hyperplanes.  
- Understood the meaning of **coefficients, intercept, and error metrics**.  

A simple but insightful project for learning the basics of MLR.  

---
