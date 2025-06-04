
# 🏠 Linear Regression on House Prices

This project uses **Linear Regression** to predict house prices based on area, number of bedrooms, and bathrooms.

---

## 📊 Dataset

The dataset contains the following columns:
- `area` — Area of the house (in sqft)
- `bedrooms` — Number of bedrooms
- `bathrooms` — Number of bathrooms
- `price` — House price in USD

It is stored in `house_prices.csv`.

---

## 📌 Technologies Used

- Python
- pandas
- NumPy
- scikit-learn

---

## 📈 Workflow

1. Load the dataset
2. Define input features (`area`, `bedrooms`, `bathrooms`) and target (`price`)
3. Split data into training and testing sets
4. Train a **Linear Regression model**
5. Predict house prices on the test set
6. Calculate **Root Mean Squared Error (RMSE)** to evaluate performance

---

## 🚀 How to Run

1. Clone this repository or download the project files.
2. Make sure you have Python installed with the required libraries:
```

pip install pandas numpy scikit-learn

```
3. Place your `house_prices.csv` in the same directory as your code.
4. Run the Python file:
```

python house\_price\_prediction.py

```

---

## 📊 Example Output

```

Root Mean Squared error:  50432.12

