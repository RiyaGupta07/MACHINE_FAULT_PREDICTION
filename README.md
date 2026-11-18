# Machine Fault Prediction Using Machine Learning
Machine Fault Prediction using Random Forest Machine Learning with an interactive Streamlit web application.

<p align="center">
  <strong>Predictive Maintenance | Random Forest | Python | Streamlit</strong>
</p>

<p align="center">
  <a href="https://machinefaultprediction-cxnucd9yhvjedkezst4ffy.streamlit.app/">
    <strong>🚀 Live Project Prototype</strong>
  </a>
</p>

---

## 📌 Abstract

Machine Fault Prediction using Machine Learning is an academic project focused on demonstrating how machine operating conditions can be classified using data-driven techniques.

The system uses operating parameters such as temperature, vibration, rotational speed (RPM), and operating hours to predict machine conditions. A Random Forest Classifier is trained using a synthetic dataset, and a Streamlit-based web application provides an interactive interface for entering machine parameters and viewing predictions.

The project demonstrates the potential application of Machine Learning in predictive maintenance and mechanical engineering.

## 🎯 Objectives

- Develop a Machine Learning model for machine condition prediction.
- Study important operating parameters affecting machine health.
- Implement a Random Forest Classification algorithm.
- Develop an interactive Streamlit web application.
- Demonstrate the concept of predictive maintenance.

## ⚙️ Input Parameters

| Parameter | Description | Unit |
|---|---|---|
| Temperature | Machine operating temperature | °C |
| Vibration | Machine vibration level | mm/s |
| RPM | Rotational speed | RPM |
| Operating Hours | Operating duration | Hours |

## 🧠 Methodology

The project follows these major steps:

1. Synthetic machine dataset generation.
2. Machine condition labelling.
3. Feature and target preparation.
4. Training and testing dataset split.
5. Random Forest model training.
6. Model evaluation.
7. Trained model integration with Streamlit.
8. Machine condition prediction through the web interface.

## 🤖 Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to perform classification.

The notebook uses a synthetic dataset of 3,000 records and trains a Random Forest Classifier with 100 estimators.

The reported test accuracy is **99.83%**.

*Note: This accuracy is obtained using synthetic data and predefined threshold-based labels. It demonstrates learning of the generated patterns and should not be interpreted as validated industrial fault-detection accuracy.*

## 📊 Prediction Categories

The application displays three machine condition categories:

- 🟢 Normal
- 🟡 Warning
- 🔴 Fault

## 🏗️ System Architecture

```text
       Machine Operating Parameters
                    |
                    v
          Dataset Generation
                    |
                    v
          Data Preparation
                    |
                    v
         Train-Test Splitting
                    |
                    v
       Random Forest Classifier
                    |
                    v
          Model Evaluation
                    |
                    v
           Saved ML Model
                    |
                    v
          Streamlit Application
                    |
                    v
           User Input Parameters
                    |
                    v
          Machine Status Prediction
                    |
                    v
          Normal / Warning / Fault
```

## 💻 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Random Forest Classifier
- Streamlit
- Google Colab
- GitHub

## 🚀 Live Demonstration

**Try the application here:**

[Machine Fault Prediction – Streamlit Web App](https://machinefaultprediction-cxnucd9yhvjedkezst4ffy.streamlit.app/)

## 📂 Repository Structure

```text
MACHINE_FAULT_PREDICTION/
│
├── MACHINE_FAULT_PREDICTION.ipynb
├── app.py
├── machine_fault_model.pkl
├── requirements.txt
└── README.md
```

## 🔮 Future Scope

- Integration with real-time industrial sensors.
- IoT-based machine monitoring.
- Testing with real industrial datasets.
- Detection of specific machine fault types.
- Real-time maintenance alerts.
- Improved prediction models and dashboards.

## ⚠️ Limitations

The current implementation uses synthetic machine data rather than measurements collected from actual industrial machinery. Further validation using real-world sensor data is necessary before practical industrial deployment.

## 📚 Project Resources

| Resource | Link |
|---|---|
| Live Prototype | [Streamlit Application](https://machinefaultprediction-cxnucd9yhvjedkezst4ffy.streamlit.app/) |
| Source Code | [GitHub Repository](https://github.com/RiyaGupta07/MACHINE_FAULT_PREDICTION) |
| Original Notebook | [Google Colab](https://colab.research.google.com/drive/1kW24hRjOEV5wnc1Zqe97V7K68j0xrkTJ?usp=sharing) |

---

**Project Type:** B.Tech Mechanical Engineering Minor Project

**Institution:** National Institute of Technology Agartala

**Domain:** Machine Learning | Predictive Maintenance | Mechanical Engineering
