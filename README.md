# 🚗 Auctioned Car Risk Prediction

## 🧠 Project Overview

This project tackles the financial risk faced by auto dealerships when buying used vehicles at auctions. Some of these vehicles, often dubbed as "kicks," are problematic and lead to losses. Our goal was to build a machine learning model to predict whether a car is a *bad buy*, helping dealerships make informed decisions.

---

## 📊 Problem Statement

Given historical auction data of used cars, predict whether a car is a **bad buy** (`IsBadBuy = 1`) or **safe purchase** (`IsBadBuy = 0`). Early identification of risky purchases can help reduce dealership losses and improve inventory quality.

---

## 🗃️ Dataset

- **Source**: Kaggle
- **Size**: ~150,000 records
- **Features**: 
  - Vehicle characteristics (Make, Model, Year, Odometer, etc.)
  - Purchase details (Auction name, Buyer number, Warranty cost, etc.)
  - Target variable: `IsBadBuy` (1 = bad, 0 = good)

---

## 🧪 Approach

1. **Exploratory Data Analysis (EDA)**:
   - Uncovered class imbalance
   - Visualized relationships between features
   - Identified missing data and outliers

2. **Data Cleaning & Feature Engineering**:
   - Imputed missing values
   - Encoded categorical features
   - Removed irrelevant columns

3. **Model Building**:
   - Baseline Dummy Classifier
   - Trained a Random Forest Classifier
   - Evaluated using accuracy, precision, recall, and ROC AUC

4. **Hyperparameter Tuning**:
   - Used GridSearchCV for optimal Random Forest parameters
   - Final model chosen based on best cross-validated ROC AUC score

---

## ✅ Results

- **Final Model**: Tuned Random Forest Classifier
- **Best ROC AUC Score**: *XX.XX%*
- **Precision/Recall**: Balanced with emphasis on minimizing False Negatives (i.e., missed bad buys)
- **Confusion Matrix**: Demonstrated reduced misclassifications

---

## 🚀 Future Work

- Add more real-world features like inspection results or dealer reviews
- Try ensemble models like XGBoost or LightGBM
- Build an interactive web dashboard for dealerships to use in real-time
- Deploy model as an API or web app (using Flask or FastAPI)

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (modeling, tuning, evaluation)
- Jupyter Notebooks
- VS Code
- Git & GitHub

---

## 📁 Folder Structure

Auctioned-Car-Prediction/
├── data/
│ └── auction_cars.csv
├── notebooks/
│ └── AuctionedCar_Prediction.ipynb
├── README.md

---

## 👩‍💻 Author

**Shaik Jasmin**  
Computer Science Undergrad | Aspiring Data Scientist  
🔗 [Portfolio](https://jasmin-shaik-portfolio.onrender.com/)  
📧 shaikjasmin100@gmail.com  
🌍 Gudur, Andhra Pradesh, India

---

## 🙌 Acknowledgments

- [Kaggle Dataset](https://www.kaggle.com/competitions/DontGetKicked/data)
- Auto dealerships and analysts working to reduce risk in car trading

---

## ⭐ Star This Repo

If you found this project helpful or insightful, feel free to give it a ⭐ and follow for more real-world ML applications!


