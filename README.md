# 📺 TV Sales Prediction using Simple Linear Regression

## 📌 Project Overview

This project demonstrates how **Simple Linear Regression (SLR)** can be used to predict product sales based on TV advertising expenditure.

The model is trained using machine learning techniques from **Scikit-Learn** and evaluates performance using metrics such as:

* R² Score
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

# 🚀 Features

✅ Data Preprocessing
✅ Train-Test Split
✅ Simple Linear Regression Model
✅ Prediction on Test Data
✅ Performance Evaluation
✅ Visualization using Matplotlib

---

# 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

# 📂 Dataset

The dataset contains advertising budgets and corresponding sales values.

### Input Feature

* TV Advertising Budget

### Output Target

* Sales

---

# 📊 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning & Exploration
4. Train-Test Split
5. Train Linear Regression Model
6. Predict Sales
7. Evaluate Model Performance
8. Visualize Results

---

# 🧠 Model Used

## Simple Linear Regression

Simple Linear Regression finds the relationship between:

* Independent Variable (TV Advertising Budget)
* Dependent Variable (Sales)

Mathematical Equation:

Where:

* `y` = Predicted Sales
* `m` = Slope
* `x` = TV Advertising Budget
* `c` = Intercept

---

# 📈 Evaluation Metrics

## 🔹 R² Score (Coefficient of Determination)

R² Score measures how well the regression model fits the data.

### Formula

```math
R^2 = 1 - \frac{SS_{res}}{SS_{tot}}
```

### Where

* (SS_{res}) = Sum of Squared Residuals

```math
SS_{res} = \sum_{i=1}^{n}(y_i - \hat{y}_i)^2
```

* (SS_{tot}) = Total Sum of Squares

```math
SS_{tot} = \sum_{i=1}^{n}(y_i - \bar{y})^2
```

### Interpretation

* (R^2 = 1) → Perfect Prediction
* (R^2 = 0) → Model performs poorly
* Higher R² Score indicates better model performance

---

# 🔹 Mean Squared Error (MSE)

MSE measures the average squared difference between actual and predicted values.

### Formula

```math
MSE = \frac{1}{n-1}\sum_{i=1}^{n}(y_i-\hat{y}_i)^2
```

### Where

* (y_i) = Actual Value
* (\hat{y}_i) = Predicted Value
* (n) = Number of Data Points

### Interpretation

* Lower MSE indicates better model accuracy.
* Penalizes larger errors more heavily.

---

# 🔹 Root Mean Squared Error (RMSE)

RMSE is the square root of Mean Squared Error.

### Formula

```math
RMSE = \sqrt{\frac{1}{n-1}\sum_{i=1}^{n}(y_i-\hat{y}_i)^2}
```

### Interpretation

* RMSE gives error in the same unit as the target variable.
* Lower RMSE indicates better predictions.
* Easier to interpret than MSE because it is in the original scale.

---


# 📉 Visualization

The project visualizes:

* Actual Sales
* Predicted Sales
* Regression Line

using Matplotlib graphs.

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone https://github.com/mohanapriya2107
```

---

## 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
TV_Sales.ipynb
```

---

# 📌 Sample Output

```python
Training Performance
---------------------
Accuracy of Training Data: 81.23
MSE Loss: 5.2341
RMSE Loss: 2.2880
```

---

# 📚 Learning Outcomes

Through this project, you will understand:

* Basics of Regression
* Model Training
* Prediction Techniques
* Error Metrics
* Data Visualization
* Scikit-Learn Workflow

---

# 🔮 Future Improvements

* Multiple Linear Regression
* Feature Scaling
* Hyperparameter Tuning
* Deployment using Flask
* Interactive Web Dashboard

---

# 👩‍💻 Author

**Mohana Priya Korukoppula**

AIML Student | Data Science Enthusiast | Agentic AI Learner

---

# ⭐ Acknowledgement

This project was built for learning and understanding the fundamentals of Machine Learning and Regression Analysis using Python.
