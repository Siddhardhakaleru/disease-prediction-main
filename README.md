🏥 Disease Prediction System

📌 Overview
This machine learning-based application predicts the likelihood of Diabetes, Heart Disease, or Parkinson’s Disease based on user input. The system features a Streamlit frontend and pre-trained ML models for accurate predictions.
📁 Project Structure

Copy
Edit
disease_prediction/
│── datasets/
│   ├── diabetes.csv
│   ├── heart.csv
│   ├── parkinsons.csv
│── training_modules/
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   ├── parkinson.sav
│── web.py
│── README.md
│── requirements.txt
🛠️ Technologies Used
🔹 Python 🐍
🔹 Streamlit (UI framework)
🔹 Scikit-learn (ML model training)
🔹 Pandas & NumPy (Data processing)
🔹 Pickle (Model serialization)

⚡ Features
✅ Predicts Diabetes, Heart Disease, and Parkinson’s Disease
✅ Simple and interactive Streamlit UI
✅ Models trained on real-world datasets
✅ Fast and reliable results

 VIEW LIVE: https://siddhardhakaleru-disease-prediction-main-web-csmk4y.streamlit.app/
 
🚀 How to Run
1️⃣ Clone the repository:


git clone https://github.com/Siddhardhakaleru/disease-prediction-main
cd disease-prediction
2️⃣ Install dependencies:


pip install -r requirements.txt
3️⃣ Run the application:

streamlit run web.py
4️⃣ Enter health parameters and get an instant prediction!

📊 How It Works
🔹 User provides health data through the UI
🔹 The pre-trained ML models process the input
🔹 The prediction is displayed in real-time

🏗 Future Enhancements
🔸 Expand predictions to include more diseases
🔸 Improve model accuracy with advanced techniques
🔸 Deploy the system on cloud platforms for wider accessibility
