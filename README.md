# Diabetes Prediction using Pima Indians Dataset

## 📌 Project Description
This project predicts the **onset of diabetes** in patients based on medical diagnostic measurements using the **Pima Indians Diabetes dataset**.  
The objective is to build a **Neural Network model (Keras)** to classify whether a patient is likely to develop diabetes, helping in early diagnosis and preventive healthcare.  

---

## 📊 Dataset Details
The dataset used is the **Pima Indians Diabetes Database**, available from the **UCI Machine Learning Repository** and also included in `sklearn.datasets`.  
It contains **768 records** with the following **8 input features** and 1 output label:

- **Pregnancies** – Number of times pregnant  
- **Glucose** – Plasma glucose concentration  
- **BloodPressure** – Diastolic blood pressure (mm Hg)  
- **SkinThickness** – Triceps skinfold thickness (mm)  
- **Insulin** – 2-Hour serum insulin (mu U/ml)  
- **BMI** – Body mass index (weight in kg/(height in m)^2)  
- **DiabetesPedigreeFunction** – Diabetes pedigree function (family history)  
- **Age** – Age in years  
- **Outcome** – Target variable (0 = No Diabetes, 1 = Diabetes)  

---

## 🛠️ Activities Performed
1. **Read and Process Data**  
   - Load dataset into Pandas DataFrame  
   - Handle missing values and perform basic preprocessing  
   - Normalize/scale input features  

2. **Define the Keras Neural Network Model**  
   - Build a sequential neural network with input, hidden, and output layers  
   - Compile the model using optimizer (`adam`) and loss function (`binary_crossentropy`)  
   - Train the model on training data and evaluate on test data  

3. **Model Evaluation**  
   - Assess model accuracy, precision, recall  
   - Generate predictions on test set  

---

✅ This project demonstrates how neural networks can be applied to healthcare datasets for **early diabetes detection**.  

