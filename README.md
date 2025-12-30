# 🛡️ AI-Based Network Intrusion Detection System (NIDS)

This project demonstrates a Machine Learning approach to Cyber Security. It uses the **Random Forest** algorithm to detect network anomalies and classify cyber attacks using the academic standard **NSL-KDD dataset**.

## 🚀 Project Overview
Traditional firewalls mostly rely on predefined rules. This project builds an intelligent system that learns from traffic patterns to identify malicious activities such as **DoS**, **Probe**, **U2R**, and **R2L** attacks.

## 📊 Dataset
* **Source:** [NSL-KDD Dataset](https://github.com/defcom17/NSL_KDD)
* **Preprocessing:** Mapping string protocols (TCP, UDP) to integers using Label Encoding.
* **Traffic Types:**
    * **Normal:** Clean traffic.
    * **DoS:** Denial of Service (e.g., Neptune, Smurf).
    * **Probe:** Port scanning (e.g., Satan, Nmap).
    * **R2L / U2R:** Unauthorized access attempts.

## 🧠 Model & Results
* **Algorithm:** Random Forest Classifier (n_estimators=100)
* **Performance:**
    * **Accuracy:** ~76% (on Test set)
    * **High Detection Rate:** Successfully classified 96% of DoS attacks and 97% of Normal traffic.

## 🛠️ Technologies Used
* Python 3
* Scikit-Learn
* Pandas & NumPy
* Matplotlib & Seaborn (for Confusion Matrix)
* Google Colab

---
*Developed by [hilal şahin]*
