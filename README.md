# 🩺 Diabetes Prediction System — Machine Learning Model  

## 📘 Project Description  
The **Diabetes Prediction System** is a Machine Learning-based project that predicts whether a person is diabetic or not using key medical attributes such as **Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, and Age**.  
The model is built using the **Support Vector Machine (SVM)** algorithm with a **Linear kernel**, achieving an accuracy of **77%** on test data.  

---

## 🔍 About the Project  
This project demonstrates the application of **supervised learning** in healthcare analytics.  
It leverages clinical data to support **early detection** of diabetes, enabling preventive medical decisions and data-driven insights for patient health evaluation.  

---

## 🧠 Model Architecture  
The project uses a **Support Vector Machine (SVM)** with the following specifications:  
* **Algorithm:** SVM (Linear Kernel)  
* **Problem Type:** Binary Classification (Diabetic / Non-Diabetic)    
* **Evaluation Metric:** Accuracy Score  

---

## 🧾 Dataset Description  
The dataset consists of medical records from women aged 21 years and above, containing **8 input features** and **1 target variable**.  

| Column Name              | Description                                                  |
| :------------------------ | :----------------------------------------------------------- |
| `Pregnancies`             | Number of times pregnant                                     |
| `Glucose`                 | Plasma glucose concentration (mg/dL)                         |
| `BloodPressure`           | Diastolic blood pressure (mm Hg)                             |
| `SkinThickness`           | Triceps skinfold thickness (mm)                              |
| `Insulin`                 | 2-Hour serum insulin (mu U/ml)                               |
| `BMI`                     | Body Mass Index (weight in kg/(height in m)²)                |
| `DiabetesPedigreeFunction`| Likelihood of diabetes based on family history               |
| `Age`                     | Age of the individual                                        |
| `Outcome`                 | 1 → Diabetic, 0 → Non-Diabetic                               |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and analysis  
* **Scikit-learn** – Model training, SVM, and evaluation  
* **Matplotlib / Seaborn** – Data visualization  

---

## 🚀 Features  
* Predicts diabetes status from clinical inputs  
* Performs data preprocessing and normalization  
* Supports accurate binary classification using SVM  
* Generates visual insights through EDA  
* Achieves reliable model performance (77% accuracy)  

---

## 📊 Results  
The trained **Support Vector Machine (Linear Kernel)** model achieved an accuracy of **~77%**, effectively classifying diabetic and non-diabetic patients.  

---

## 📁 Repository Structure  

```

📦 ML_Project_Diabetes_Prediction
│
├── diabetes_prediction_model.ipynb  # Jupyter Notebook with full code
├── diabetes.csv  # Dataset used for training
└── README.md  # Project documentation
```

---

## 🧪 How to Run  

1. **Clone the repository:** 
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Project-Diabetes-Prediction.git
   cd ML-Project-Diabetes-Prediction
   ```

2. **Install dependencies:**
    ```bash
   pip install -r requirements.txt
    ```

3. **Run the notebook:**
  ```bash
   jupyter notebook diabetes_prediction_model.ipynb
  ```
  
4. **Execute all cells to train, test, and evaluate the model.**
 
---

## 📈 Future Improvements  

* Integrate a web interface using Flask or Streamlit

* Apply other ML algorithms (Random Forest, XGBoost) for comparison

* Enhance interpretability with SHAP or LIME visualization

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
