# ❤️ Heart Disease Prediction System

A Machine Learning project that predicts the likelihood of heart disease using patient health parameters. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment through a Streamlit interface.

---

## 🚀 Features

- Interactive Streamlit interface
- Real-time heart disease prediction
- Data preprocessing and cleaning
- One-Hot Encoding for categorical features
- Feature scaling using StandardScaler
- K-Nearest Neighbors (KNN) classification model

---

## 📊 Dataset Information

- Dataset Size: 918 Records
- Features: 11 Input Features + 1 Target Variable
- Target Variable: HeartDisease

### Input Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak (ST Depression)
- ST Slope

---

## 🔧 Data Preprocessing

- Checked missing values
- Checked duplicate records
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- One-Hot Encoding using `pd.get_dummies()`
- Feature Scaling using `StandardScaler`

---

## 🤖 Machine Learning Model

Algorithm Used:

- K-Nearest Neighbors (KNN)

Model Workflow:

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. One-Hot Encoding
5. Feature Scaling
6. Model Training
7. Model Evaluation
8. Streamlit Deployment

---

## 📈 Model Performance

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 86.41% |
| KNN | 85.33% |
| Naive Bayes | 85.33% |
| Decision Tree | 77.17% |
| SVM | 84.78% |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Streamlit

---

## 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── app.py
├── KNN_heart1.pkl
├── Scaler_heart1.pkl
├── Columns_heart1.pkl
├── requirements.txt
├── README.md
└── heart.csv
```

## ▶️ Run Locally

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git

cd Heart-Disease-Prediction

pip install -r requirements.txt

streamlit run app.py
```


---

## 🎯 Future Improvements

- Deploy on Streamlit Cloud
- Add prediction probability score
- Compare multiple machine learning models
- Improve UI/UX
- Add model performance dashboard

---

## 👨‍💻 Author

Vishal Gupta

B.Tech CSE Student  
Aspiring Data Scientist

GitHub: https://github.com/vishalkhairthal
