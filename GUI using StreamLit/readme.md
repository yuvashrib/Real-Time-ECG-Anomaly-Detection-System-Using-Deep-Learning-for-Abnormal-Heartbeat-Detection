## 🧠 Best Performing Model

- **Model Used:** Autoencoder
- **Reason:** It outperformed other models (DNN, CNN, LSTM) in anomaly detection accuracy.
- **Deployment:** The trained model is hosted on Google Cloud for inference.

## 🖥️ GUI Application (Streamlit)

We developed a real-time anomaly detection interface using **Streamlit**, which allows users to upload ECG signals and visualize predictions.

### 🔧 Features

- Upload ECG `.arff` file via GUI.
- Every 5 seconds, a new heartbeat is processed.
- Predictions: Normal or Anomalous signal.
- Graphical comparison of real-time ECG vs normal baseline.
- Threshold tuning to demonstrate a variety of outcomes.
- Notes section to guide users for a smooth experience.

### 🧪 Test File

We include a sample test `.arff` file specially prepared for testing the GUI behavior and model predictions. It ensures that both normal and anomalous outputs are displayed.


## 🎥 GUI Demo Video
👉 **Watch the demo:** [https://drive.google.com/file/d/1g-irkaOdu3m5LaBRxXfsaUOM16Ch-mEU/view?usp=sharing](#)  
