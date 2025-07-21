````markdown
# Diabetes Prediction using Support Vector Machine (SVM)

This project is a machine learning application that predicts whether a person is diabetic or not using the **Pima Indians Diabetes Database** and a Support Vector Machine classifier.

## 📂 Project Overview
This model uses patient medical data (like glucose levels, BMI, age, etc.) to predict diabetes outcomes. The dataset is preprocessed, standardized, and split into training and testing sets before being used to train an SVM classifier with a linear kernel.

## 🛠 Features
- Loads and analyzes the diabetes dataset
- Data preprocessing and standardization
- Splits data into training and testing sets
- Trains a Support Vector Machine (SVM) model
- Evaluates accuracy on training and testing data
- Accepts new patient data for prediction

## 📊 Dataset
The dataset used is the **Pima Indians Diabetes Dataset**. It contains the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

## 🧑‍💻 Technologies Used
- Python 3
- NumPy
- Pandas
- scikit-learn

## 🚀 Getting Started

### Prerequisites
Make sure you have Python and the following libraries installed:
```bash
pip install numpy pandas scikit-learn
````

### Running the Project

1. Clone this repository or download the Python file.
2. Ensure `diabetes.csv` is in the same directory as the Python file.
3. Run the script:

```bash
python diabetes_prediction.py
```

### Predicting a New Sample

At the end of the script, you can modify the `input_data` tuple to test predictions on custom data:

```python
input_data = (1,189,60,23,846,30.1,0.398,59)
```

## 📈 Model Performance

* **Training Accuracy**: \~X%
* **Test Accuracy**: \~Y%
  (*Replace X and Y with your actual accuracy scores*)

## 📄 License

This project is for educational purposes.

---

✅ **Author**: Swastika Khatua

```
```
