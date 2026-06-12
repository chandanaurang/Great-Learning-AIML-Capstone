# Great-Learning-AIML-Capstone
# Industrial Safety NLP-Based Chatbot Interface
**Great Learning AI/ML Capstone Project**

## 📌 Project Overview & Context
This capstone project focuses on **Industrial Safety** using accident records from 12 manufacturing plants across 3 countries. The primary objective is to analyze detailed text descriptions of accidents to predict potential safety levels and identify key risks. 

By building an end-to-end Machine Learning and Deep Learning pipeline, this project introduces an interactive, utility-driven **NLP Chatbot Interface** designed to help safety professionals highlight operational risks automatically based on incident reports.

---

## 📊 Dataset Description
The model processes structured and unstructured data, leveraging features such as:
* **Accident Level / Potential Accident Level:** Severity metrics tracking actual vs. high-risk scenarios.
* **Critical Risk:** Categorized description of the risks involved (e.g., electrical, fall from heights).
* **Description (Text Data):** Unstructured text documenting exactly how the incident occurred.

* **Dataset Source:** [Kaggle Industrial Safety and Health Analytics Database](https://www.kaggle.com/ihmstefanini/industrial-safety-and-health-analytics-database)

---

## 🚀 Project Architecture & Milestones

### 🔹 Milestone 1: Data Preprocessing & Cleansing
* Imported, cleaned, and structured the raw data records.
* Performed exploratory data analysis (EDA) and handled text irregularities.
* Exported clean features for model consumption.

### 🔹 Milestone 2: NLP Modeling & Classifiers
* Designed and executed text preprocessing routines (tokenization, lemmatization, stop-word elimination).
* Built and validated baseline **Machine Learning Classifiers**.
* Implemented **Deep Learning Feedforward Neural Networks**.
* Engineered sequential **Recurrent Neural Networks (RNN) and LSTM** structures to process contextual strings.
* Selected the highest-performing architecture and successfully saved the compiled weights as a pickled file.

### 🔹 Milestone 3: Clickable UI Chatbot Deployment
* Programmed an integrated user interface (UI) automating data pipeline tasks.
* Developed a responsive chatbot interface that accepts real-time incident descriptions as input and delivers instant risk evaluation responses.

---

## 🛠️ Tech Stack & Libraries
* **Core Language:** Python
* **NLP & Text Mining:** NLTK, Spacy, Regex
* **Modeling & Deep Learning:** Scikit-Learn, TensorFlow, Keras (LSTMs/RNNs)
* **GUI / Deployment:** Tkinter / Flask / Django
