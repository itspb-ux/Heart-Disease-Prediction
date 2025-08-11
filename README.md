❤️ Heart Disease Prediction
📌 Overview
This project predicts the likelihood of heart disease based on various health-related attributes.
Using Machine Learning techniques, the model analyzes medical data to assist in early diagnosis and preventive healthcare.

🛠 Tech Stack
Language: Python

Libraries:

pandas, numpy – Data handling

matplotlib, seaborn – Data visualization

scikit-learn – Model training & evaluation

Jupyter Notebook – Development environment

📂 Project Structure
bash
Copy
Edit
📁 Heart-Disease-Prediction
│── 📄 heart.csv               # Dataset
│── 📄 Heart_disease_prediction.ipynb   # Model training & evaluation
│── 📄 README.md                # Project documentation
📊 Dataset
The dataset contains patient medical records such as:

Age

Sex

Blood pressure

Cholesterol level

Fasting blood sugar

ECG results

Maximum heart rate achieved

Exercise induced angina

Oldpeak (ST depression)

Number of major vessels

Thalassemia type

Target variable: 1 → Heart disease present, 0 → No heart disease.

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Heart_disease_prediction.ipynb
Run all cells to see data analysis, training, and prediction results.

📈 Model & Evaluation
Preprocessing: Missing value handling, encoding categorical variables, scaling.

Models used: Logistic Regression, Random Forest, Decision Tree, KNN, SVM (depending on notebook).

Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.

📌 Features
Data cleaning and preprocessing pipeline.

Exploratory Data Analysis (EDA) with visualizations.

Multiple ML models with comparison.

Prediction function for new patient data.

📜 License
This project is licensed under the MIT License – you are free to use, modify, and distribute it.
