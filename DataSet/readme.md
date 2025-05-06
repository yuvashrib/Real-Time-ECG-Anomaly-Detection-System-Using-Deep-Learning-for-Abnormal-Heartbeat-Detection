
# 🩺 ECG5000 Dataset

This folder contains the preprocessed ECG5000 dataset used in our deep learning project for anomaly detection and classification.

---

## 📂 Dataset Overview

| Feature              | Value          |
|----------------------|----------------|
| **Dataset Name**     | ECG5000        |
| **Train Size**       | 500            |
| **Test Size**        | 4500           |
| **Length**           | 140 time steps |
| **Number of Classes**| 5              |
| **Dimensions**       | 1 (univariate) |
| **Type**             | ECG time series|

---

## 🔗 Data Source
 
- **Direct Dataset Link**: *[https://www.timeseriesclassification.com/description.php?Dataset=ECG5000]*

---

## 📜 Description

The original ECG5000 dataset is a 20-hour long ECG recording downloaded from **PhysioNet**, specifically from the **BIDMC Congestive Heart Failure Database (chfdb)**. The record used is **"chf07"**, which comes from a patient with severe congestive heart failure.

### 🧪 Preprocessing Steps:
1. **Heartbeat Extraction** – Individual heartbeats were extracted from the continuous ECG signal.
2. **Normalization** – Each heartbeat was resized to the same length (140 data points) using interpolation.

A total of **5,000 heartbeats** were randomly selected and annotated using an automated method.

---

## 👨‍🔬 Citation and Contributors

- **Donated by**: Y. Chen, E. Keogh  
- **Original Source Publication**:
  > Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE.  
  > *PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals.*  
  > Circulation 101(23).

- **Dataset Usage Reference**:
  > Dau H.A., et al.  
  > *A general framework for never-ending learning from time series streams.*  
  > Data Mining and Knowledge Discovery (DAMI), 29(6).

---

