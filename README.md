# House Price Prediction 🏠

This project predicts house prices using Machine Learning with Scikit-learn.  
The model is trained on the California Housing dataset and predicts house prices based on various housing features.

---

## 📌 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Machine Learning Pipelines

---

## ⚙️ Project Workflow

Dataset → Data Preprocessing → Feature Scaling → Model Training → Prediction

Steps:

1. Load housing dataset
2. Handle missing values using `SimpleImputer`
3. Encode categorical features using `OneHotEncoder`
4. Standardize numerical features using `StandardScaler`
5. Train model using **Random Forest Regressor**
6. Predict house prices

---

## 🤖 Machine Learning Model

The following models were tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

The **Random Forest Regressor** was selected as the final model due to better performance.

Evaluation metric used:

- RMSE (Root Mean Squared Error)

---

## 📂 Project Structure

house-price-prediction  
│  
├── housing.csv        # Dataset  
├── input.csv          # Test input  
├── output.csv         # Prediction output  
├── main.py            # Training + prediction script  
├── README.md          # Project documentation  
└── .gitignore         # Ignored files  

---

## ▶️ How to Run the Project

Install dependencies:

pip install pandas numpy scikit-learn joblib

Run the project:

python main.py

The model will train and generate predictions.

---

## 👨‍💻 Author

Parth Kulkarni  
Computer Engineering Student  
Interested in Machine Learning, Data Science and AI.
