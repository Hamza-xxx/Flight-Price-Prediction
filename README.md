# ✈️ Flight Price Prediction using Machine Learning

A Machine Learning project that predicts flight ticket prices based on airline, class, duration, stops, departure time, arrival time, source city, and destination city.

---

## 📌 Project Overview

This project uses a Random Forest Regression model to predict flight ticket prices.

The dataset contains information about:
- Airline company
- Flight duration
- Number of stops
- Departure time
- Arrival time
- Source city
- Destination city
- Ticket class
- Days left before departure

The model was trained and evaluated using different regression metrics.

---

## 🧠 Machine Learning Workflow

1. Data Collection
2. Data Analysis (EDA)
3. Data Preprocessing
4. Feature Encoding
5. Train/Test Split
6. Model Training
7. Model Evaluation
8. Feature Importance Visualization

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🤖 Model Used

- Random Forest Regressor

---

## 📊 Evaluation Metrics

| Metric | Value |
|--------|--------|
| R² Score | 0.985 |
| MAE | 1061 |
| RMSE | 2708 |

---

## 📈 Feature Importance

The most important features affecting flight price were:
- Ticket Class
- Flight Duration
- Days Left

---

## 📷 Prediction Visualization

Actual vs Predicted Flight Prices:

![Prediction Graph](images/actual_vs_predicted.png)

---

## 🚀 How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Flight-Price-Prediction.git
```

### 2️⃣ Install Libraries

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

Open:

```text
flight_price_prediction.ipynb
```

using Jupyter Notebook or VS Code.

---

## 👨‍💻 Author

Hamza Adel

