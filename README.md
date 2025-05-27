# Heart-Attack-Risk-Analysis-and-Prediction

 Overview
This project focuses on analyzing heart health data and predicting the likelihood of a heart attack using machine learning models. It involves exploratory data analysis (EDA), visualization, and a Random Forest classifier to build a reliable predictive system.

🧠 Motivation
Cardiovascular disease is a leading cause of death globally. Early prediction and preventive care can save lives. This project provides a data-driven approach to understand patterns in patient data and identify those at risk of a heart attack.

📂 Dataset
The dataset used is named: heart.csv
Contains medical records of patients, each with multiple health-related attributes.

✅ Features include:

- age: Age of the patient
- sex: Gender (1 = male; 0 = female)
- cp: Chest pain type (0–3)
- trestbps: Resting blood pressure
- chol: Serum cholesterol
- fbs: Fasting blood sugar > 120 mg/dl
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise-induced angina
- oldpeak: ST depression induced by exercise
- slope: Slope of peak exercise ST segment
- ca: Number of major vessels colored by fluoroscopy
- thal: Thalassemia type
- target: Presence (1) or absence (0) of heart disease

🔍 Exploratory Data Analysis (EDA)
EDA helped understand:

- Feature distributions using histograms and boxplots
- Correlation between features using heatmaps
- Class imbalance and data cleanliness
- Outlier detection and handling

⚙️ Technologies & Libraries
- Python 3
- Pandas, NumPy – data manipulation
- Matplotlib, Seaborn – visualization
- Scikit-learn – preprocessing, model building, evaluation
- Jupyter Notebook – development environment

🤖 Model Building
🧪 Preprocessing:
- Handled missing values
- Feature scaling using StandardScaler
- Train-test split (typically 80:20)

🧠 Classifier:
- Random Forest Classifier
- Optionally fine-tuned using GridSearchCV

📈 Evaluation Metrics:
- Accuracy Score
- ROC Curve
- Confusion Matrix
- Feature Importance
