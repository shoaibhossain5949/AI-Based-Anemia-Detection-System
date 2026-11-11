# 🩺 XAI-Driven Clinical Decision Support System
## Interpretable Anemia Classification Using Raw Hematological Parameters

### 📌 Overview

This project presents an Explainable Artificial Intelligence (XAI)-powered Clinical Decision Support System (CDSS) for accurate and interpretable anemia classification using raw hematological parameters.

Unlike traditional black-box machine learning systems, our framework integrates **SHAP (SHapley Additive exPlanations)** to provide transparent, feature-level explanations for individual predictions. This enables healthcare professionals to understand the factors influencing a patient's classification as Anemic or Normal.

### 🎯 Research Motivation

Anemia affects billions of people worldwide and remains one of the most common blood-related health conditions.

Although Machine Learning models can achieve high prediction accuracy, many traditional approaches have a major limitation: they cannot clearly explain why a particular prediction was made.

In healthcare, transparency and interpretability are essential alongside predictive performance.

Our research aims to bridge this gap by integrating:

- High Prediction Accuracy
- Explainable Artificial Intelligence (XAI)
- Clinical Decision Support
- Real-Time Prediction Dashboard
- Potential for Healthcare Deployment

### 🚀 Key Features

- ✅ Explainable Artificial Intelligence (XAI)
- ✅ Clinical Decision Support System (CDSS)
- ✅ Random Forest Classifier
- ✅ SHAP-Based Explainability
- ✅ Hb–MCV Ratio Feature Engineering
- ✅ Real-Time Prediction Dashboard
- ✅ Prediction Confidence Score
- ✅ Interactive Prediction Visualization
- ✅ Lightweight Deployment
- ✅ No Additional Hardware Requirements

### 🏥 Dataset Information

| Property | Description |
|---|---|
| Data Source | Medical Centre Hospital, Chattogram |
| Total Patients | 1,004 |
| Features | 9 Hematological Parameters |
| Classification Classes | Normal / Anemia |
| Problem Type | Binary Classification |

### 📊 Methodology

The proposed framework follows a structured machine learning pipeline:

```text
Raw CBC Data
     │
     ▼
Data Cleaning
     │
     ▼
Data Preprocessing
     │
     ▼
Feature Engineering
   (Hb–MCV Ratio)
     │
     ▼
Model Training
     │
     ▼
Random Forest Classifier
     │
     ▼
Anemia Classification
     │
     ▼
SHAP Explainability
     │
     ▼
Clinical Decision Support Dashboard
```

### ⚙️ Machine Learning Models

We evaluated multiple machine learning algorithms to identify the best-performing classification model.

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 97.50% |
| Gradient Boosting | 98.80% |
| XGBoost | 97.50% |
| ⭐ Random Forest | **98.98%** |

**Best Performing Model:** Random Forest Classifier with 98.98% accuracy.

### 🧠 Explainable Artificial Intelligence (XAI)

Our system goes beyond conventional prediction by providing interpretable explanations for every individual classification.

Using SHAP, the framework provides:

- ✔ Identification of the most influential hematological parameters
- ✔ Explanation of factors contributing to Anemia classification
- ✔ Individual Feature Importance Analysis
- ✔ Prediction Confidence Score
- ✔ SHAP Waterfall Visualization
- ✔ Transparent Model Interpretation

### 💻 Clinical Dashboard Features

The interactive dashboard provides the following functionalities:

- 📈 Real-Time Anemia Prediction
- 📊 Interactive Data Visualization
- 📋 CBC Parameter Input Form
- 🎯 Prediction Confidence Score
- 🔍 SHAP-Based Explainability
- 📑 Clinical Decision Support Information
- 📂 Patient Report Generation
- 📥 Export Prediction Results

### 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Explainable AI | SHAP |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Frontend | HTML, CSS, JavaScript |
| Backend | Flask |
| Deployment | GitHub, Render |

### 📈 Model Performance

The proposed Random Forest model achieved an accuracy of **98.98%**.

Key evaluation metrics include:

- ✅ Accuracy
- ✅ Precision
- ✅ Recall
- ✅ ROC-AUC
- ✅ Model Interpretability

*Note: Detailed evaluation metrics and validation results should be reported alongside the accuracy score.*

### 🌍 Potential Business and Healthcare Impact

This project explores the potential of an AI-powered HealthTech solution that could support healthcare professionals in interpreting hematological data.

**Potential Application Areas:**

- 🏥 Hospitals
- 🧪 Diagnostic Centers
- 🏥 Rural Healthcare Clinics
- 💊 Telemedicine Platforms

**Potential Revenue Models:**

- SaaS Subscription
- API Integration
- Enterprise Licensing
- Clinical Dashboard Solutions

### 📸 Project Preview

Add project screenshots below:

| Dashboard | Prediction |
|---|---|
| `dashboard.png` | `prediction.png` |

| SHAP Explanation | ROC Curve |
|---|---|
| `shap.png` | `roc_curve.png` |

### 📂 Project Structure

```text
XAI-Anemia-CDSS/
│
├── dataset/
├── models/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
├── app.py
├── requirements.txt
├── model.pkl
├── README.md
└── LICENSE
```

### 🚀 Installation and Setup

**1. Clone the Repository**

```bash
git clone https://github.com/yourusername/XAI-Anemia-CDSS.git
```

**2. Navigate to the Project Directory**

```bash
cd XAI-Anemia-CDSS
```

**3. Install Dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the Application**

```bash
python app.py
```

### 📚 Research Contributions

The major contributions of this research include:

1. Development of an Explainable AI-Based Anemia Classification Framework.
2. Integration of the Hb–MCV Ratio as an Engineered Feature.
3. Comparative Evaluation of Multiple Machine Learning Algorithms.
4. Implementation of SHAP-Based Individual Prediction Explanations.
5. Development of an Interactive Clinical Decision Support Dashboard.
6. Exploration of Potential HealthTech Commercialization.

### 👨‍💻 Authors

**Md. Bilayet Hossain**  
Department of Computer Science and Engineering  
Daffodil International University

**Shoaib Hossain**  
Department of Computer Science and Engineering  
Daffodil International University

**Sadaf M. Anis**  
Department of Computer Science and Engineering  
Daffodil International University

### 📜 License

This project is licensed under the MIT License.

---

⭐ If you find this project useful, please consider giving this repository a Star!

**Disclaimer:** This project is intended for research and educational purposes. It is not a substitute for professional medical diagnosis or clinical judgment.
