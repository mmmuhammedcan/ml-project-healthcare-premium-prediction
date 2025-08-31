# 🏥 Health Insurance Cost Predictor  

This project is a **Machine Learning web app** built with **Streamlit** that predicts health insurance premiums based on personal, lifestyle, and medical factors.  

🔗 **Live Demo**: [Open the App](https://ml-project-healthcare-premium-prediction-iwn8eit7kp4brxl3j8gdf.streamlit.app)  

---

## 🚀 Features  
- Collects user input on:  
  - Age, Dependants, Income  
  - Gender, Marital Status, BMI Category  
  - Smoking & Medical History  
  - Employment & Region  
  - Insurance Plan  
- Predicts **health insurance cost** instantly.  
- Simple, clean UI powered by **Streamlit**.  

---

## 🛠️ Tech Stack  
- **Python 3.x**  
- **Streamlit** for the web interface  
- **Scikit-learn** (ML model)  
- **Pandas / NumPy** for preprocessing  

---

## 📂 Project Structure
```text
.
├── app.py                 # Main Streamlit app
├── prediction_helper.py   # Prediction logic (ML model helper)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

---

## ⚡ Run Locally  

Clone this repository and set up the environment:  

```bash
# Clone the repo
git clone https://github.com/your-username/healthcare-premium-prediction.git
cd healthcare-premium-prediction

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
