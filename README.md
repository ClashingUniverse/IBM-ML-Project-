# IBM-ML-Project 
# Edunet Foundation
# ⚡ Power System Fault Detection and Classification using Machine Learning

## 🔎 Introduction

In modern electrical grids, detecting and classifying power system faults accurately is critical to ensure reliable and uninterrupted electricity supply. This project, **Power System Fault Detection and Classification using Machine Learning**, aims to automate fault identification in power distribution systems using advanced machine learning techniques.

By leveraging **IBM Watsonx.ai**, scalable cloud infrastructure, and real-time electrical data, this system distinguishes between normal and fault conditions (like line-to-ground, line-to-line, and three-phase faults) — enabling faster, smarter grid maintenance and improved stability.

---

## ❗ Problem Statement

In complex power distribution networks, detecting faults manually is time-consuming and prone to error. Operators need a system that can:

* Automatically detect and classify various fault types,
* Use real-time data (voltage, current, etc.),
* Respond quickly to prevent blackouts,
* Reduce downtime, improve reliability, and maintain grid safety.

---

## ✅ Proposed Solution

This project introduces a **machine learning-based fault classification system** that:

* Uses a dataset from **Kaggle** containing electrical measurement data.
* Trains ML models like **Random Forest**, **SVM**, and **Logistic Regression** to detect and classify faults.
* Deploys the model using **IBM Watsonx.ai Studio** and **IBM Cloud Object Storage** for real-time predictions.
* Evaluates model performance using metrics such as **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

---

## 🧠 Technologies Used

**1. IBM Watsonx.ai Studio**
Used to build, train, and deploy the machine learning models with trust and transparency.

**2. IBM Cloud Object Storage**
Handles all training data and documents required for analysis and prediction.

**3. Machine Learning Algorithms**
Random Forest Classifier, SVM, and Logistic Regression are used for classification tasks.

**4. Python & Jupyter Notebooks**
Used for model development, training, testing, and visualization.

---

## 🌐 IBM Cloud Services Used

* **IBM Watsonx.ai Studio** – AI model training and deployment.
* **IBM Cloud Object Storage** – Data input and retrieval.
* **IBM IAM (Identity and Access Management)** – Secure authentication and access.
* **IBM Cloud Lite Account** – Enables development and deployment at zero cost for initial testing.

---

## ✨ WOW Factors

* **Real-Time Fault Prediction** using cloud APIs.
* **Fully deployed on IBM Cloud** – Reliable and Scalable.
* **Supervised Learning** with labeled fault types.
* **Rapid Classification** – Helps in reducing recovery time and downtime.
* **Adaptable Architecture** – Easily extendable with IoT or smart meter data in the future.

---

## 👥 Target Users

* **Power System Engineers**
* **Electric Utility Companies**
* **Smart Grid Planners**
* **Research Labs & Universities**
* **IoT & Automation Developers**

---

## 🔑 Key Features

* **Accurate Fault Detection** – Classifies fault type using real-time electrical data.
* **ML-Based Learning** – Improves prediction as more fault data becomes available.
* **Cloud-Ready** – Deployed and tested using IBM’s trusted cloud infrastructure.
* **Result Monitoring** – Output results accessible via API or UI.
* **Dataset-Based Insights** – Powered by real-world fault dataset from Kaggle.

---

## ⚙️ How It Works

1. **Input** – Real-time data: voltage, current, temperature, component health, etc.
2. **Preprocessing** – Cleans, normalizes, and structures the input dataset.
3. **Model Training** – Uses supervised learning to classify fault types.
4. **Evaluation** – Measures Accuracy, Precision, Recall, and F1-Score.
5. **Deployment** – Hosted on IBM Watsonx.ai Studio for cloud-based predictions.
6. **Prediction** – Real-time classification using API endpoints.

---

## 📊 Results

The model successfully predicts different types of power system faults with high accuracy using Random Forest Classifier and can be enhanced with SVM depending on performance needs.

## 🔹 Progress Map 1
<img width="1898" height="906" alt="Screenshot 2025-07-25 165843" src="https://github.com/user-attachments/assets/8ae1d339-05c8-49ad-8f41-6bb4033bcfcb" />


## 🔹 Progress Map 2
<img width="1899" height="907" alt="Screenshot 2025-07-25 165905" src="https://github.com/user-attachments/assets/24e51d73-1aeb-4044-af4a-c50e8089beb5" />


## 🔹 Metric Chart
<img width="1893" height="904" alt="Screenshot 2025-07-25 165921" src="https://github.com/user-attachments/assets/5ef3b6d4-b7af-49b1-a20b-d3d7d755e5a2" />


## 🔹 Testing and Predicting
<img width="1915" height="906" alt="Screenshot 2025-07-26 194908" src="https://github.com/user-attachments/assets/9800fe91-8684-4a33-9f93-e9c4d91d1c02" />


## 🔹 Results
<img width="1890" height="910" alt="Screenshot 2025-07-26 194844" src="https://github.com/user-attachments/assets/1c1d4494-a332-46a2-8994-ef8da3e0c4a0" />

---


## 📌 Deployment Overview

1. Log into [IBM Cloud](https://cloud.ibm.com)
2. Use Watsonx.ai Studio for training your model.
3. Upload Kaggle fault dataset to IBM Cloud Object Storage.
4. Choose Random Forest / SVM model depending on dataset.
5. Test accuracy and optimize.
6. Deploy using API or Web UI for real-time predictions.

---

## 🌟 Future Scope

* **Real-Time IoT Data Integration**
  Connect the model with smart meters or IoT sensors for instant fault alerts.

* **Predictive Maintenance**
  Evolve the system to predict future faults and prevent failures before they happen.

* **Advanced Deep Learning Models**
  Integrate **LSTM** or **Graph Neural Networks** for higher temporal and topological accuracy.

* **Mobile Dashboard Interface**
  Launch a mobile app for engineers to monitor grid health remotely.

* **Continuous Learning Pipelines**
  Enable the model to self-improve as more data is collected over time.

---

## 📌 Conclusion

The power system fault detection model demonstrates how **machine learning** can automate complex processes and reduce human error in critical infrastructure. Using **Random Forest**, **real-world electrical data**, and **IBM Watsonx.ai**, the model accurately classifies fault types and enables proactive power grid management.

This project shows great potential for real-world deployment in **smart grids**, **utilities**, and **urban electrical systems** where response time and reliability are vital.

---

## 🔗 Resources & References

* **Dataset:** [Kaggle Fault Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
* **IBM Cloud:** [IBM Cloud Platform](https://www.ibm.com/cloud)
* **IEEE Research:** [IEEExplore Paper](https://ieeexplore.ieee.org/document/10306740)
* **ScienceDirect Paper:** [Article Link](https://www.sciencedirect.com/science/article/pii/S2352484724007807)
* **GitHub Repository:** [Project Code](https://github.com/ClashingUniverse/IBM-ML-Project-)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> Created by **Srinivas Vajja** during the IBM SkillsBuild for Academia Internship 2025 provided by **Edunet Foundation** and **AICTE (All India Council for Technical Education)**
> Department of Computer Science and Engineering
> Sagi Rama Krishnam Raju Engineering College
