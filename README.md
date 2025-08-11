# ❤️ Heart Disease Prediction
# 📌 Overview

This project predicts the **likelihood of heart disease** based on various health-related attributes.
By applying Machine Learning techniques, the model analyzes patient medical data to assist in early diagnosis and preventive healthcare.

## 🛠 Tech Stack
**Language:** Python

**Libraries Used:**

* pandas, numpy → Data handling
* matplotlib, seaborn → Data visualization
* scikit-learn → Model training & evaluation
* Jupyter Notebook → Development environment

## 📂 Project Structure

```
📁 Heart-Disease-Prediction
│── 📄 heart.csv                       # Dataset
│── 📄 Heart_disease_prediction.ipynb  # Model training & evaluation
│── 📄 README.md                        # Project documentation
```

## 📊 Dataset

The dataset contains patient medical records such as:

* Age
* Sex
* Blood pressure
* Cholesterol level
* Fasting blood sugar
* ECG results
* Maximum heart rate achieved
* Exercise induced angina
* Oldpeak (ST depression)
* Number of major vessels
* Thalassemia type

**Target variable:**

* `1` → Heart disease present
* `0` → No heart disease

---

## 🚀 How to Run

**1️⃣ Clone the repository:**

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

**2️⃣ Install dependencies:**

```bash
pip install -r requirements.txt
```

**3️⃣ Open the Jupyter Notebook:**

```bash
jupyter notebook Heart_disease_prediction.ipynb
```

**4️⃣ Run all cells** to see the data analysis, training, and prediction results.

## 📈 Model & Evaluation

**Preprocessing:**

* Handling missing values
* Encoding categorical variables
* Feature scaling

**Models Tested:**

* Logistic Regression
* Random Forest
* Decision Tree
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix


## 📌 Features

✔ Data cleaning & preprocessing pipeline
✔ Exploratory Data Analysis (EDA) with visualizations
✔ Multiple ML models with performance comparison
✔ Prediction function for new patient data


## 📜 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute it.

