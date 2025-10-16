# ANN Classification - Customer Churn Prediction

This project predicts **customer churn** using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras.  
A simple **Streamlit web app** allows users to input customer details and get real-time churn predictions.

---

## 🧠 Features
- Deep learning model trained on customer data  
- Encodes categorical features using LabelEncoder & OneHotEncoder  
- Scales input data using StandardScaler  
- Streamlit-based interactive prediction interface  
- Saved model and preprocessing pipelines for deployment  

---

## 📁 Files in this Repository
- `app.py` → Streamlit app for prediction  
- `model.h5` → Trained ANN model  
- `label_encoder_gender.pkl`, `onehot_encoder_geo.pkl`, `scaler.pkl` → Encoders and scaler  
- `experiments.ipynb` → Model training notebook  
- `prediction.ipynb` → Prediction testing notebook  

---

## 🚀 How to Run
```bash
# 1. Clone the repository
git clone https://github.com/veeravallisarathkumar/ANN-Classification-churn.git
cd ANN-Classification-churn

# 2. Create a virtual environment
python -m venv venv
venv\Scripts\activate   # For Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run Streamlit app
streamlit run app.py
🧩 Tech Stack

Python

TensorFlow / Keras

scikit-learn

Streamlit

pandas, numpy

📊 Output

The app predicts whether a customer is likely to:

Stay with the bank

Leave the bank (churn)

👨‍💻 Author

Veeravalli Sarath Kumar
🔗 GitHub Profile


---

### 💬 GitHub Description (for the “About” section):
> Streamlit app for customer churn prediction using an Artificial Neural Network (ANN) built with TensorFlow and Keras.
