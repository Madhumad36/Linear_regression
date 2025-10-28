
# 🧠 Task 1: Build a Linear Regression Model

## 📌 Objective
Predict **housing prices** using a **simple Linear Regression model** with one or two input features.

---

## 🧰 Tools & Libraries
- **Python**
- **pandas** – for data handling  
- **scikit-learn** – for building and evaluating the regression model  
- **matplotlib** – for data visualization  
- **numpy** – for numerical operations  

---

## 📂 Dataset
We use the **California Housing dataset** from `sklearn.datasets`.  
It contains various features such as:
- `MedInc` — Median income in block group  
- `AveRooms` — Average number of rooms per household  
- `MedHouseVal` — Median house value (target variable)

---

## ⚙️ Steps to Run (Google Colab)
1. Open [Google Colab](https://colab.research.google.com/)
2. Create a **new notebook**
3. Copy the full code from the notebook section
4. Run each cell using **Shift + Enter**
5. View model output and graphs directly in Colab

---

## 🧮 Project Workflow

### 1️⃣ Import Libraries
Load Python libraries for data handling, visualization, and model building.

### 2️⃣ Load and Explore Data
Use `fetch_california_housing()` to import dataset and explore basic stats with:
```python
df.info(), df.describe(), df.head()
````

### 3️⃣ Feature Selection

Choose:

* Input features: `MedInc`, `AveRooms`
* Target variable: `MedHouseVal`

### 4️⃣ Model Building

Split data into train/test sets using `train_test_split()` and train a **LinearRegression()** model.

### 5️⃣ Model Evaluation

Evaluate model using:

* **Mean Squared Error (MSE)**
* **R² Score**

### 6️⃣ Visualization

Plot:

* Actual vs Predicted Prices
* Median Income vs Median House Value

---

## 📊 Sample Output

| Metric       | Description        | Example Value |
| ------------ | ------------------ | ------------- |
| **MSE**      | Mean Squared Error | ~0.53         |
| **R² Score** | Goodness of Fit    | ~0.60–0.70    |

---

## 📈 Results Summary

* Linear regression captures the trend between **income** and **housing prices** fairly well.
* Higher median income areas generally correlate with higher house prices.
* Performance can be improved using **multiple features** or **non-linear models**.

---

## 📦 Deliverables

* ✅ Jupyter / Colab Notebook
* ✅ Dataset (auto-loaded from `sklearn`)
* ✅ Visualizations
* ✅ Model Evaluation Metrics
* ✅ README file

---

## 👩‍💻 Author

**Madhavi**
📚 B.Tech CSE (Data Science) 
Project Domain: **AI/ML – Predictive Modeling**




