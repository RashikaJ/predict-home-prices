## 🏡 Predicting Home Prices using Python and Linear Regression

### 📌 Overview  
This project uses **simple linear regression** to predict housing prices based on square footage. It is a beginner-friendly machine learning model built with Python, following best practices in data preprocessing, model training, and evaluation.

---

### 📂 Project Structure
```
predict-home-prices/
├── Project1.py         # Python script with full code
├── home_dataset.csv    # Dataset containing house prices and square footage
└── README.md           # Project documentation
```
---

### 📊 Dataset  
The dataset used (`home_dataset.csv`) contains two columns:
- `area` – Size of the house in square feet
- `price` – Price of the house in INR (lakhs)

This is a small synthetic dataset, ideal for learning the basics of linear regression.

---

### 🔧 Tools and Technologies
- Python (3.x)
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (for Linear Regression)

---

### 🚀 How the Model Works

1. **Load the dataset** using Pandas  
2. **Visualize** the relationship between house area and price  
3. **Train a linear regression model** using scikit-learn  
4. **Predict price** for a house with a given area  
5. **Plot the regression line** over the scatterplot  
6. Export model using `joblib` (optional)

---

### 📈 Sample Output
**Raw Data Plot (House Prices vs. Size):**
Shows the actual distribution of the dataset before model fitting.

![Raw Scatter Plot](https://github.com/RashikaJ/predict-home-prices/blob/cc1ff56fb76de19710c399088cdb16664b07a39a/Figure_1.png?raw)

**Linear Regression Fit:**
Below is the linear regression output showing the relationship between house size (sq.ft) and price (millions $):
The red line shows the predicted house prices based on the linear model.

![Property Price Prediction](https://github.com/RashikaJ/predict-home-prices/blob/cc1ff56fb76de19710c399088cdb16664b07a39a/Figure_2.png?raw)

---

### 💡 Key Learnings

- Applied **Linear Regression** using `scikit-learn`
- Understood the **relationship between variables** (area vs. price)
- Practiced **data visualization** with Matplotlib
- Explored basic **model evaluation and prediction**

---

### 🛠 Future Improvements
- Use **multiple linear regression** with more features (e.g., number of bedrooms, location)
- Implement **model evaluation metrics** like R² score and RMSE
- Deploy the model using **Flask or Streamlit**

---

### 🧠 Credits
Based on the tutorial by [Codédex](https://www.codedex.io/projects/predict-home-prices-with-python-and-linear-regression)

