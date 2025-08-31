# 🛠️ Machine Failure Prediction using Sensor Data

Predicting failures in industrial machines before they happen using machine learning. This project leverages sensor data to classify whether a machine is likely to fail or not. 🚨🔧

## 📊 Overview

Industrial machines are equipped with sensors that collect data like temperature, vibration, pressure, etc. This project analyzes that data and builds predictive models to detect potential failures, helping industries reduce downtime and maintenance costs.

---

## 🧠 Technologies Used

- 🐍 Python
- 📦 Pandas, NumPy
- 📊 Scikit-learn, XGBoost
- 📈 Matplotlib, Seaborn
- 📓 Jupyter Notebook

---

## 🧹 Data Preprocessing

- Handled missing values and outliers
- Normalized sensor data for better model performance
- Performed feature selection using correlation heatmaps and variance thresholds

---

## 🤖 ML Models Used

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 83%      |
| Random Forest       | ✅ **91%** |
| XGBoost             | 89%      |

Random Forest outperformed other models and was chosen for deployment due to its robustness and interpretability. 🌲

---

## 📊 Evaluation Metrics

- ✔️ Accuracy
- ⚖️ Precision & Recall
- 📉 F1-Score
- 📈 ROC-AUC Curve

---

## 📌 Key Features

- Real-time failure prediction model
- Visualizations to understand feature relationships and performance
- Multiple model comparison
- Scalable and customizable for different sensor setups

---

# 🚀 How to Run

1. Clone the repository  
git clone https://github.com/sumit3162/Machine-Failure-Prediction.git
cd Machine-Failure-Prediction
Install dependencies

pip install -r requirements.txt
Launch the notebook

jupyter notebook
📌 Future Improvements
Integrate real-time sensor streaming with Kafka or MQTT

Deploy model using Flask or FastAPI

Build dashboard for live monitoring (using Dash or Streamlit)

🙌 Acknowledgements
Thanks to open datasets and the ML community for support and resources.

💡 Author
Sumit Patil
📧 shinganesumit80@gmail.com
🌐 GitHub | 📸 Instagram

Let me know if you'd like a version with real folder paths or to include a sample dataset to
