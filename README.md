# ATS_GoldFuture_Predict

  This repository is for **Data Science Capstone Project: Gold Future Price Short-Term Prediction** (ITCS227: Introduction to Data Science, Faculty of ICT, Mahidol University, in the academic year 2024) by **Apes Together Strong** group (section 2).

<br>

## 🔍 Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

<br>

## 📖 About

  This project aims to forecast short-term gold futures prices based solely on historical market data, including previous closing prices, opening prices, highs, and lows. While these features may not capture all long-term influences, short-term trends in gold often display momentum and trend-following behavior. This behavior can make short-term forecasting more feasible and practically useful compared to long-term predictions.

<br>

## ✨ Features

- **Data Collection & Pre-processing:** Data was collected from historical gold futures prices, cleaned, and pre-processed to remove any inconsistencies.
- **Feature Engineering:** Lag features, rolling averages, and time-based features were created to capture important patterns in the data.
- **Modeling**
  - XGBoost: Chosen for its ability to handle non-linear relationships and provide high accuracy through boosting.
  - Random Forest: Selected for its robustness, simplicity, and ability to model complex feature interactions.
  - LSTM (Long Short-Term Memory): Ideal for capturing long-term dependencies in sequential data, making it well-suited for time series forecasting.
- **Evaluation Metrics:** Mean Absolute Error (MAE) and R² Score.

<br>

## ⚙️ Installation

```Installation
# Install the required packages before running.
pip install torch pandas scikit-learn matplotlib xgboost
```

<br>

## 🚀 Usage

```
# Download the ZIP file of the directory, unzip, and then from the terminal (e.g. Command Prompt) change directory to the folder.
cd [directory]\ATS_GoldFuture_Predict

# Choose the model to run, e.g.
python xgboost-ats.py
```

<br>

## 🗂️ Project Structure

```Structure
ATS_GoldFuture_Predict-main/
├── dataset/
│   └── future-gc00-daily-prices.csv
├── xgboost-ats.py          # XGBoost Model
├── randomforest-ats.py     # Random Forest Model
├── lstm-ats.py             # LSTM Model
└── README.md
```

<br>

## 🧪 Examples

### XGBoost Model
![Screenshot 2025-05-02 202808](https://github.com/user-attachments/assets/11be6341-5f54-45b9-bb13-b93c3147c2ad)
![Screenshot 2025-05-02 202607](https://github.com/user-attachments/assets/925c8f98-dc2b-4ffd-90ca-c340856ee465)

<br>

### Random Forest Model
![Screenshot 2025-05-02 202937](https://github.com/user-attachments/assets/4c23a59b-bfba-4e4e-afe4-795e667a46ff)
![Screenshot 2025-05-02 202922](https://github.com/user-attachments/assets/f7038f6a-a44b-4b8f-94a0-a2540e5071e8)

<br>

### LSTM Model
![Screenshot 2025-05-02 211301](https://github.com/user-attachments/assets/120e248f-d16e-467b-8d06-60faf84e043b)
![Screenshot 2025-05-02 211210](https://github.com/user-attachments/assets/7946b257-3b6f-4386-b0b8-6d8fbe6797a5)

<br>

## 🤝 Contributing

Apes Together Strong (section 2)
- 6688001 Pattareeya Achaiyaphoom
- 6688013 Korawit Chantavilaiying
- 6688021 Apinut Cotivongsa
- 6688032 Nipada Jadjaidee
- 6688157 Woraphol Meakapat

<br>

## 📄 License

This project is for academic purposes only (Mahidol University).
