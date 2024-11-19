# Ethereum_Fraud_Detection_project
A machine learning project to detect fraudulent Ethereum transactions using supervised learning, with a focus on feature engineering, model evaluation, and an interactive Streamlit app for real-time fraud detection."

### **1. Project Overview**
This project aims to classify Ethereum blockchain transactions as **fraudulent (illicit)** or **legitimate (licit)**. The dataset contains transaction details, such as average transaction times, Ether balances, and unique contract interactions. Using machine learning techniques, the project analyzes patterns to identify fraudulent behavior.

---

### **2. Features**
- **Data Preprocessing**:
  - Cleaned and handled missing values.
  - Applied oversampling (SMOTE) to address class imbalance.
- **Exploratory Data Analysis (EDA)**:
  - Analyzed key features to identify patterns.
  - Visualized distributions and correlations.
- **Model Building**:
  - Applied multiple classifiers, including Logistic Regression and Random Forest.
  - Achieved high accuracy using feature engineering.
- **Deployment**:
  - Developed an interactive Streamlit application for real-time fraud detection.

---

### **3. Tech Stack**
- **Programming Language**: Python  
- **Libraries**:
  - Data Processing: `Pandas`, `NumPy`
  - Machine Learning: `Scikit-learn`, `Imbalanced-learn`
  - Visualization: `Matplotlib`, `Seaborn`
  - App Deployment: `Streamlit`

---

### **4. Dataset**
The dataset is publicly available on Kaggle: **Ethereum Fraud Detection Dataset**.  
It contains transaction details, with columns such as:
- `Time Difference Between Transactions`
- `Total Ether Sent/Received`
- `Unique Contract Interactions`
- `Transaction Flags (Illicit or Legitimate)`

---

### **5. Installation**
Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/your-username/Ethereum_Fraud_Detection_project.git
cd Ethereum_Fraud_Detection_project
pip install -r requirements.txt
```

---

### **6. Usage**
Run the Streamlit app for real-time transaction analysis:

```bash
streamlit run app.py
```

---

### **7. Results**
- Achieved an accuracy of **95%** with the Random Forest model.
- Evaluated using metrics like **Precision, Recall, F1-Score**, and **Confusion Matrix**.
- The model effectively detected fraudulent patterns in Ethereum transactions.

---

### **8. Future Scope**
- Integrate real-time Ethereum transaction data using blockchain APIs.
- Improve detection capabilities with advanced techniques like **Deep Learning**.
- Expand to multi-class fraud detection for different fraud types.

---

### **10. License**
This project is licensed under the MIT License. See `LICENSE` for more details.

---
