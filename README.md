# Heart Disease Prediction

This repository contains a machine learning model for predicting heart disease based on clinical data. The dataset used for training and evaluation is `heart.csv`, and the implementation is provided in the Jupyter Notebook `Model Code.ipynb`.

## 📂 Repository Structure

```
📁 Heart-Disease-Prediction
│── 📄 README.md  # Project documentation
│── 📄 heart.csv  # Dataset used for training and evaluation
│── 📄 Model Code.ipynb  # Jupyter Notebook implementing the model
```

## 📊 Dataset

The `heart.csv` dataset contains medical attributes used to predict the likelihood of heart disease. The dataset includes features such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate
- Exercise-Induced Angina
- ST Depression
- ST Slope
- Number of Major Vessels
- Thalassemia

## 🏗 Model Implementation

The `Model Code.ipynb` notebook includes:

- Data Preprocessing (handling missing values, feature scaling, etc.)
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Training (Logistic Regression, Decision Trees, Random Forest, etc.)
- Model Evaluation (Accuracy, Precision, Recall, F1-Score)
- Predictions on New Data

## 🔧 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Heart-Disease-Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Model Code.ipynb"
   ```
4. Run the notebook cells to train and evaluate the model.

## 📌 Future Improvements

- Implement Deep Learning models for better accuracy.
- Deploy the model as a web application using Flask or FastAPI.
- Improve feature selection using advanced techniques.

## 📜 License

This project is licensed under the MIT License.
