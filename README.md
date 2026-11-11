 XAI-Driven Clinical Decision Support System
Interpretable Anemia Classification Using Raw Hematological Parameters

    

📌 Overview
This project presents an Explainable Artificial Intelligence (XAI) powered Clinical Decision Support System (CDSS) for accurate and interpretable Anemia Classification using raw hematological parameters.

Unlike traditional black-box AI systems, our framework integrates SHAP (SHapley Additive Explanations) to provide transparent, feature-level explanations for every prediction, enabling clinicians to understand why a patient is classified as Anemic or Normal.

🎯 Research Motivation
Anemia affects billions of people worldwide and remains one of the most common blood disorders.

Although Machine Learning models can achieve high prediction accuracy, most existing approaches suffer from one critical limitation:

❌ They cannot explain why the prediction was made.

In healthcare, trust is just as important as accuracy.

Our research bridges this gap by combining:

High Prediction Accuracy
Explainable AI
Clinical Decision Support
Real-Time Dashboard
Commercial Deployment Potential
🚀 Key Features
✅ Explainable AI (XAI)

✅ Clinical Decision Support System

✅ Random Forest Classifier

✅ SHAP Explainability

✅ Hb–MCV Ratio Feature Engineering

✅ Real-Time Prediction Dashboard

✅ Confidence Score

✅ Interactive Prediction Visualization

✅ Lightweight Deployment

✅ Zero Additional Hardware Cost

🏥 Dataset
Property	Value
Source	Medical Centre Hospital, Chattogram
Patients	1004
Features	9 Hematological Parameters
Classes	Normal / Anemia
Problem Type	Binary Classification
📊 Methodology
Raw CBC Data
      │
      ▼
Data Cleaning
      │
      ▼
Preprocessing
      │
      ▼
Feature Engineering
(Hb–MCV Ratio)
      │
      ▼
Model Training
      │
      ▼
Random Forest
      │
      ▼
Prediction
      │
      ▼
SHAP Explainability
      │
      ▼
Clinical Dashboard
⚙️ Machine Learning Models
Model	Accuracy
Logistic Regression	97.50%
Gradient Boosting	98.80%
XGBoost	97.50%
⭐ Random Forest	98.98%
🧠 Explainable AI
Instead of only predicting the disease,

our system also explains:

✔ Which feature contributed the most

✔ Why the patient is predicted as Anemic

✔ Individual Feature Importance

✔ Confidence Score

✔ SHAP Waterfall Explanation

💻 Dashboard Features
📈 Real-Time Prediction
📊 Interactive Visualization
📋 CBC Input Form
🎯 Prediction Confidence
🔍 SHAP Explainability
📑 Clinical Recommendation
📂 Patient Report
📥 Export Results
🛠 Tech Stack
Category	Technology
Language	Python
ML	Scikit-Learn
Explainability	SHAP
Data Processing	Pandas, NumPy
Visualization	Matplotlib
Dashboard	HTML, CSS, JavaScript
Backend	Flask
Deployment	GitHub + Render
📈 Performance
✅ Accuracy : 98.98%

✅ High Precision

✅ High Recall

✅ High ROC-AUC

✅ Clinically Explainable

🌍 Business Impact
This project is designed as a future-ready HealthTech Startup.

Potential deployment:

🏥 Hospitals

🧪 Diagnostic Centers

🏥 Rural Clinics

💊 Telemedicine Platforms

Revenue Model

SaaS Subscription
API Integration
Enterprise License
Clinical Dashboard
📸 Project Preview
Add screenshots here

dashboard.png
prediction.png
shap.png
roc_curve.png
📂 Project Structure
├── dataset/
├── models/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
├── app.py
├── requirements.txt
├── model.pkl
├── README.md
└── LICENSE
🚀 Installation
git clone https://github.com/yourusername/XAI-Anemia-CDSS.git

cd XAI-Anemia-CDSS

pip install -r requirements.txt

python app.py
📚 Research Contributions
✔ Explainable AI Framework

✔ Novel Hb–MCV Ratio Feature

✔ High Prediction Accuracy

✔ Clinical Decision Support

✔ Real-Time Dashboard

✔ HealthTech Commercialization

👨‍💻 Authors
Md. Bilayet Hossain

Department of CSE

Daffodil International University

Shoaib Hossain

Department of CSE

Daffodil International University

Sadaf M. Anis

Department of CSE

Daffodil International University

📜 License
This project is licensed under the MIT License.

⭐ If you find this project useful, please consider giving it a Star ⭐

