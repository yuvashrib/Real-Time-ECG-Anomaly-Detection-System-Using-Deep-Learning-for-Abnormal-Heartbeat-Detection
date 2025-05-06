# ECG Anomaly Detection and Classification Using Deep Learning

A deep learning-based project for real-time anomaly detection and classification in ECG (electrocardiogram) signals. This system uses the ECG5000 time series dataset and explores multiple neural network architectures—DNN, LSTM, CNN, and Autoencoder—to detect irregular heart rhythms and classify patterns accurately. The final solution is deployed via an interactive Streamlit web app with REST API integration for real-time predictions.

---

## 🚀 Project Goals

- Detect and classify anomalies in ECG time series data using deep learning.
- Evaluate and compare the performance of four different neural network models.
- Develop a responsive, easy-to-use interface for real-time ECG signal analysis.
- Integrate backend models with a REST API to serve predictions through the frontend.

---

## 📊 Dataset

- **Name:** ECG5000  
- **Source:** [UCR Time Series Classification Archive](https://www.timeseriesclassification.com/description.php?Dataset=ECG5000)  
- **Description:** Contains 5,000 univariate ECG records, each 140 time steps long. Data is labeled into 5 distinct classes, representing both normal and abnormal heartbeats.

---

## 🧠 Models Used

### 1. Dense Neural Network (DNN)
A simple fully connected feed-forward neural network used as a baseline for classification.

### 2. Long Short-Term Memory (LSTM)
A recurrent neural network suited for sequential time-series data, capturing temporal dependencies in ECG signals.

### 3. Convolutional Neural Network (CNN)
Applies 1D convolution to learn local signal patterns in ECGs, ideal for capturing morphological abnormalities.

### 4. Autoencoder
An unsupervised model trained to reconstruct normal signals. Anomalies are detected using reconstruction error thresholds.

---

## 📈 Model Evaluation Metrics

- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1 Score**  
- **Confusion Matrix**

Each model was tested on a common validation set to ensure fair performance comparison.

---

## 💻 Application Features

Built using **Streamlit**, the web interface offers:
- Easy upload of ECG samples or selection from test data.
- Signal visualization using plots.
- Real-time anomaly prediction and class identification.
- Backend powered by REST API for fast and secure model inference.

---

## 🔍 Key Learnings

- Practical experience working with time-series data and imbalanced classes.
- Implementation of diverse neural architectures for the same problem space.
- Building full-stack ML apps with Python, Streamlit, and REST APIs.
- Importance of performance metrics in healthcare-sensitive predictions.

---

## 👨‍💻 Contributors

- **Aiswarrya Kannan**  
- **Ancita Caroline Dsouza**  
- **Veda M Kowale**  
- **Yuvashri Bhanuprakash**

---

## 📌 Future Work

- Incorporate attention-based models (e.g., Transformer for time series).
- Expand the app for multi-lead ECG input.
- Explore model interpretability for clinical adoption.

---

## 🏥 Real-World Relevance

Automated ECG interpretation can support early detection of cardiac issues, helping clinicians prioritize urgent cases and improve healthcare outcomes.
