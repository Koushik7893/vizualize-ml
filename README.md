# **Machine Learning & Deep Learning Web App**  

## 🌟 **Overview**  
This project is a **full-stack Machine Learning and Deep Learning web application** that allows users to:  
✅ Upload and train models on **classification, regression, time series, and image classification** tasks.  
✅ **Select and visualize** dataset properties and model performance.  
✅ **Test models with custom inputs** and compare different approaches.  
✅ **Interact with a chatbot** (powered by **ChatGroq API**).  
✅ **Track experiments and manage models** using **MLflow & Airflow**.  
✅ **Store and retrieve data** via **PostgreSQL & AWS S3**.  

---

## 🎯 **How It Works**  

### 🔹 **1. Interactive Model Training & Analysis**  
- Users can upload datasets and train **classification, regression, and time series models**.  
- The app supports various models, including **SVM, Random Forest, CNN, LSTM, and KNN**.  
- **Dimensionality Reduction techniques** (PCA, SVD, ICA, NMF, Factor Analysis) help analyze data patterns.  
- Users can visualize **model accuracy, feature importance, loss curves, and predictions**.  

### 🔹 **2. User Authentication & Session Management**  
- Users can **register and log in** with authentication stored in **PostgreSQL**.  
- **Session-based chat history** is maintained, similar to ChatGPT’s interface.  
- Each user’s interactions, dataset uploads, and model training history are stored securely.  

### 🔹 **3. AI Chatbot Integration**  
- The chatbot, powered by the **ChatGroq API**, assists users with ML concepts and application usage.  
- Users can ask questions related to dataset selection, model performance, or general AI topics.  
- Chat history is stored and accessible for each session.  

### 🔹 **4. MLOps & Experiment Tracking**  
- **MLflow is integrated** for model tracking and versioning.  
- **Airflow automates time series data ingestion and processing**, storing results in **AWS PostgreSQL**.  
- Users can **view experiment logs, compare models, and analyze trends**.  

### 🔹 **5. Data Storage & Management**  
- **AWS S3 stores datasets and trained models**, ensuring efficient storage and retrieval.  
- **PostgreSQL manages user authentication, chat history, and model metadata**.  

### 🔹 **6. Web App Frontend & Visualization**  
- The **Flask backend handles API requests, authentication, and chatbot interactions**.  
- The **Streamlit frontend provides an interactive interface** for dataset selection, model training, and result visualization.  
- Users can see **performance metrics, graphs comparing different models, and dataset statistics**.  

### 🔹 **7. Model Deployment & API Access**  
- Models are **stored and versioned**, allowing users to test different versions on new data.  
- A **custom API endpoint** enables real-time model inference.  
- Users can manually input feature values and get **instant predictions**.  

---

## 🚀 **Deployment & Cloud Integration**  

### **1️⃣ AWS PostgreSQL & S3**  
- **PostgreSQL stores user data, chat history, and experiment logs**.  
- **S3 stores trained models and datasets**, allowing efficient retrieval.  

### **2️⃣ Airflow for Time Series Processing**  
- **Fetches, cleans, and stores time series data daily** without interrupting the app.  

### **3️⃣ MLflow for Model Management**  
- Keeps track of **model versions, hyperparameters, and performance metrics**.  
- Users can compare **accuracy, precision, recall, and loss curves** over multiple training runs.  

---

## 📊 **Visualization & Insights**  
- **Graphical comparisons** of multiple models' performance.  
- **Feature importance analysis** for better model interpretability.  
- **Time series forecasting with performance metrics**.  

---

## 🛠 **Future Enhancements**  
✔ Add **Google/GitHub login support**.  
✔ Implement **multi-model comparison UI** in Streamlit.  
✔ Automate **Docker-based deployment**.  
✔ Enable **real-time ML model serving (FastAPI, Flask)**.  

This project **demonstrates full-stack ML/DL capabilities** with **Flask, Streamlit, PostgreSQL, AWS, Airflow, and MLflow**, making it an **impressive fresher portfolio project**. 🚀
