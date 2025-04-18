# 📈 Crypto Data Mining Project

## 🚀 Overview
The world of cryptocurrencies evolves at lightning speed — understanding trends in real time is essential for investors, analysts, and data scientists alike.  
This project provides a full **Data Mining pipeline** using crypto data from the **CoinGecko API**, covering:

- 🔍 Web Scraping & API calls  
- 🧹 Data Preprocessing  
- 📊 Exploratory Data Analysis (EDA)  
- 🤖 Machine Learning (Classification & Regression)  
- 📈 Performance Evaluation  

## 🧰 Tech Stack
| Tool / Library        | Usage                                     |
|-----------------------|-------------------------------------------|
| `Python`              | Core programming language                 |
| `Requests`            | API interaction with CoinGecko            |
| `Pandas` & `NumPy`    | Data manipulation and preprocessing       |
| `Matplotlib` & `Seaborn` | Visualizations for EDA and results     |
| `Scikit-learn`        | ML models (Logistic Regression, RF, GB)   |
| `JSON`                | Intermediate data format                  |

---

## 📥 Data Collection

Data is collected using the [CoinGecko API](https://www.coingecko.com/en/api), including:
- Current price
- Market cap
- Total volume
- 24h price change (%)

> 📂 Output: A preprocessed JSON file: `cryptos_preprocessed.json`

---

## 🧼 Data Preprocessing
Steps include:
- Handling missing & infinite values
- Standardization of numerical features
- Export to JSON format for reuse

---

## 📊 Exploratory Data Analysis (EDA)
Using `Matplotlib` and `Seaborn` for:
- Price variation distribution
- Correlation heatmaps
- Pairplots colored by price trends

---

## 🔍 Supervised Machine Learning

### ✅ Classification
**Goal**: Predict whether a crypto's price will rise in the next 24h (`price_up`)

Models tested:
- Logistic Regression
- Random Forest
- Gradient Boosting

**Metrics**:
- Accuracy, Precision, Recall
- Confusion Matrices
- Pairplots for visual understanding

### 📈 Regression
**Goal**: Predict the **current price** of a crypto

Models tested:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

**Metrics**:
- RMSE, MAE, R²

---

## 📌 Results Summary
All model performances are stored and compared using dataframes and bar plots.

---

## 🎯 Objective
This project offers a scalable and flexible analytical base for:
- Real-time trend detection
- Decision-support tools for investors
- Applications in DeFi, algorithmic trading, and finance education

---

## 🔗 References
- [CoinGecko API Docs](https://www.coingecko.com/en/api/documentation)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)

---

## 🤝 Let’s Connect!
Feel free to reach out for feedback or ideas on potential improvements or applications!

---
