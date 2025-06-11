# 💧 Water Potability Predictor

A Machine Learning project that predicts whether water is safe to drink based on key physicochemical parameters. Built using Python, Flask, and Scikit-learn, this project offers a simple web interface for real-time predictions.

---

## 🔍 Problem Statement

Access to clean and safe drinking water is crucial for human health. This project helps predict water potability using a supervised ML model trained on water quality data. The model classifies input water samples as either **Safe** or **Not Safe to Drink**.

---

## 📁 Project Structure

water-quality-predictor/
├── model/
│ ├── random_forest_water_quality.pkl
│ └── features.pkl
├── static/
│ └── style.css
├── templates/
│ └── index.html
├── app.py
├── requirements.txt
└── README.md

---

## 🧪 Features Used for Prediction

- pH (0 - 14)
- Hardness (mg/L)
- Solids (ppm)
- Chloramines (ppm)
- Sulfate (mg/L)
- Conductivity (μS/cm)
- Organic Carbon (ppm)
- Trihalomethanes (μg/L)
- Turbidity (NTU)

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **ML Models**: Random Forest, XGBoost (with and without SMOTE)
- **Frontend**: HTML, CSS
- **Data Handling**: Pandas, NumPy
- **Model Evaluation**: Accuracy, Precision, Recall, F1-score, ROC AUC

---

## 🚀 How to Run Locally

1. **Clone the repository**  
git clone https://github.com/adik0207/water-quality-predictor.git
cd water-quality-predictor

2. **Install dependencies**  
pip install -r requirements.txt

3. **Run the app**  
python app.py

4. **Open in browser**  
Visit `http://127.0.0.1:5000/`

---

## 🌐 Deployment

Due to GitHub’s file size limitation, the ML model files (`.pkl`) could not be pushed directly. The project is not yet deployed live, but you can run it locally by downloading the entire zip.

---

## 📦 Dataset Source

The dataset used is publicly available on [Kaggle: Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)

---

## 🧠 Model Performance (Example)

| Model                | Accuracy | Precision (1) | Recall (1) | F1-score (1) |
|---------------------|----------|---------------|------------|--------------|
| Logistic Regression | 61%      | 0.00          | 0.00       | 0.00         |
| Random Forest       | 66%      | 0.63          | 0.30       | 0.41         |
| XGBoost             | 64%      | 0.56          | 0.40       | 0.46         |
| RF + SMOTE          | 65%      | 0.56          | 0.50       | 0.53         |

---

## 👤 Author

**Aditya Khare**  
[GitHub](https://github.com/adik0207) • [Email](mailto:adikhare0207@gmail.com)

---

## 📌 Notes

- The project includes a dark mode toggle 🌙.
- Values entered into the form are now retained after submission.
- You can edit the model or UI easily via the `model/` and `templates/` directories.

---

## 🛑 Disclaimer

This is a project for educational purposes and should not be used for critical water safety decisions without expert validation.
