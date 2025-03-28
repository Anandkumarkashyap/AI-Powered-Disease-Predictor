
# 🤷‍♂️ **AI-Powered Disease Predictor System **
"An innovative, prognostic web platform, leveraging sophisticated machine learning algorithms, delivers probabilistic disease risk assessments across a spectrum of pathologies. This cutting-edge system aims to augment clinical decision-making and empower individuals with preliminary diagnostic insights derived from user-submitted physiological and medical data. It facilitates early detection and triage, potentially streamlining healthcare workflows and enhancing patient outcomes."

---

## ⚕️ **Project Description**
The **AI-Powered Disease Predictor System** uses pre-trained machine learning models to predict the probability of various diseases based on user inputs such as age, glucose level, blood pressure, cholesterol, and more. It offers an interactive and intuitive interface powered by **Streamlit**. The system aims to enhance early disease detection and empower users with predictive insights.

### **Key Objectives:**
- Provide **fast and reliable disease predictions** using AI models.
- Ensure **data accuracy and precision** by leveraging real-world datasets.
- Offer an easy-to-use, responsive, and interactive interface.

---

## ⚙️ **Tech Stack**
The project utilizes the following technologies and libraries:
- **Backend:** Python (ML models with `scikit-learn`)
- **Frontend:** Streamlit (for the web interface)
- **Data Processing:** `pandas`, `numpy`
- **Machine Learning:** `scikit-learn`
- **Model Persistence:** `joblib`
- **Deployment:** Localhost (can be extended to cloud platforms)

---

## 🛠️ **Installation Guide**
Follow these steps to set up the project locally:

1. **Clone the repository:**
```
git clone https://github.com/anandkumarkashyap/AI-Powered-Disease-Predictor.git
```

2. **Navigate to the project directory:**
```
cd AI-Powered-Medical-Prediction
```

3. **Install dependencies:**
```
pip install -r requirements.txt
```

4. **Run the application:**
```
streamlit run app.py
```

✔️ The app will launch in your browser at `http://localhost:8501`.

---

## 🤔 **How to Use**
1. **Select the Disease:** Choose from the dropdown menu (Diabetes, Heart Disease, Lung Cancer, etc.).  
2. **Enter Medical Data:** Fill in the relevant medical parameters (age, glucose level, blood pressure, etc.).  
3. **Predict the Result:** Click the **"Predict"** button to get the AI-generated prediction.  
4. **View the Outcome:** The model will display the disease likelihood and confidence score.  

---

## 📅 **Datasets Used**
The project uses disease-specific datasets stored in the `datasets/` folder:

- **`breast_cancer.csv`** – Breast Cancer Dataset
- **`diabetes.csv`** – Diabetes Patient Data
- **`heart_disease_uci.csv`** – Heart Disease Dataset
- **`indian_liver_patient.csv`** – Liver Disease Dataset
- **`kidney_disease.csv`** – Kidney Disease Data
- **`survey_lung_cancer.csv`** – Lung Cancer Survey Data

---

## 🧠 **Model Training and Evaluation**
The project contains individual training scripts for each disease in the `model_train/` folder.  
You can retrain the models by running the corresponding Python scripts:

**Example: Retraining the Diabetes Model**
```
python model_train/train_diabetes_model.py
```

### ✔️ **Trained Models**
The `.pkl` files in the `models/` folder contain the pre-trained models:
- `diabetes_model.pkl`
- `heart_disease_model.pkl`
- `lung_cancer_model.pkl`
- `kidney_disease_model.pkl`
- `liver_disease_model.pkl`
- `breast_cancer_model.pkl`

---

## 🔥 **Features and Benefits**
- ⚕️ **Multi-Disease Prediction:** Supports predictions for 7 major diseases.  
- 📅 **Real-Time Results:** Fast and accurate disease prediction.  
- 🌐 **User-Friendly Interface:** Simple, intuitive, and responsive UI.  
- 🔥 **Pre-Trained Models:** Improves efficiency and reduces processing time.  
- 📈 **Expandable:** Modular structure makes it easy to add more diseases.  

---

## 🚀 **Future Scope**
- ✔️ **Enhanced Model Accuracy:** Incorporate deep learning models (e.g., neural networks) for better predictions.  
- 📅 **Cloud Integration:** Deploy on cloud platforms for wider accessibility.  
- 🔥 **Additional Diseases:** Expand the model portfolio by including more diseases.  
- 📉 **Visualization:** Add detailed graphs and visualization features.  

---

## 🤝 **Contributing**
Contributions are welcome!  
- Fork the repository  
- Create a new branch (`git checkout -b feature-branch`)  
- Commit your changes (`git commit -m 'Add new feature'`)  
- Push to the branch (`git push origin feature-branch`)  
- Open a Pull Request  

---

## 📲 **Contact**
For queries or collaboration:  
- **GitHub:** [Anand Kumar](https://github.com/anandkumarkashyap)  
- **Email:** anandkashyap6048@gmail.com  
# AI-Powered-Disease-Predictor
