# 👋 Hi, I'm Minoli Perera

**AI/ML Engineer | Machine Learning Developer**  
Python · Machine Learning · Deep Learning · NLP · Data Science · scikit-learn · FastAPI · Azure AI  

🔗 [**Portfolio**](https://minoliperera021126.github.io/portfolio-minoli-perera/) <br>
📧 [**Email**](mnnetmi@gmail.com) <br>
💼 [**LinkedIn**](https://linkedin.com/in/minoliperera)  

---

## 👩‍💻 About Me

I am an undergraduate in **Business Information Systems** with a passionate focus on **AI/ML engineering and data science**.  
I specialize in building **machine learning pipelines, predictive models, and intelligent systems** with emphasis on data preprocessing, model optimization, and production deployment.

I have hands-on experience developing end-to-end ML projects using **Python, scikit-learn, and FastAPI**, and a solid foundation in **AI principles** through Microsoft Azure AI-900.  
Currently seeking **internship or entry-level roles** in AI/ML engineering where I can contribute to real-world intelligent systems and continue advancing my machine learning expertise.

---

## 🚀 Featured ML Projects

### 🔹 Car Price Prediction System (Regression ML Model)
**Technologies:** Python · scikit-learn · Jupyter Notebook · Pandas · NumPy · Matplotlib · Tensorflow <br>
**Repository:** https://github.com/MinoliPerera021126/car-price-prediction-ml-system <br>
**Live Demo:** https://car-price-prediction-ml-system-minoliperera021126.streamlit.app/ <br>
**Created:** April 2026

Regression-based machine learning system for predicting automobile prices using historical market data.

**Model Development & Implementation**
- Developed supervised learning regression pipeline for continuous price prediction.
- Implemented feature engineering and exploratory data analysis (EDA) on automotive dataset.
- Trained and evaluated multiple regression models (Linear Regression, Random Forest, MLP/Dense Neural Network).
- Performed hyperparameter optimization and model comparison using cross-validation metrics.
- Analyzed feature importance and model interpretability to understand price drivers.

**Key Outcomes**
- Achieved robust regression performance with comprehensive evaluation metrics (R², RMSE, MAE).
- Documented model selection process and performance trade-offs.
- Provided actionable insights on key factors influencing car prices.

---

### 🔹 Fake News Detection System (NLP & Classification)
**Technologies:** Python · scikit-learn · TensorFlow/Keras · NLTK · XGBoost · Flask · Pandas <br>
**Repository:** https://github.com/MinoliPerera021126/fake-news-detection-ml-system <br>
**Created:** April 2026 <br>
**Team:** Minoli Perera · Sandagomi Kodikara · Savindi Dissanayake <br>
**Institution:** University of Sri Jayewardenepura

University group project building a machine learning system to classify fake vs. real news articles using the ISOT dataset (~44,900 articles from Reuters and informal blogs).

**Data Preprocessing & Feature Engineering**
- Implemented Reuters dateline stripping to fix critical data leakage issues
- Applied text preprocessing: lemmatization, contraction expansion, and tokenization
- Engineered TF-IDF vectorization with 50,000 features for optimal feature representation
- Conducted rigorous ablation study across 4 different feature configurations

**Model Development & Comparative Analysis**
- Trained and evaluated 6 machine learning models:
  - Logistic Regression
  - Naive Bayes
  - Linear SVM
  - Random Forest
  - XGBoost
  - 1D Convolutional Neural Network (TensorFlow/Keras)
- Performed 80/10/10 stratified train-validation-test split
- Applied 5-fold cross-validation for robust performance estimation
- Generated ROC curves and confusion matrices for comprehensive evaluation

**Key Achievements**
- Achieved **99%+ F1-Score and ROC-AUC** with Linear SVM as the optimal model
- Deployed production-ready Flask REST API with **sub-5ms CPU inference time**
- Identified critical dataset bias: model learned Reuters writing style rather than truthfulness
  - Real news uniformly from Reuters (formal style, datelines, statistics)
  - Fake news from informal blogs (casual language patterns)
  - Successfully detected formal-style fabricated news as 100% real

**Critical Insights & Future Directions**
- Discovered that high accuracy (99%) is meaningless without understanding model behavior
- Documented the importance of dataset diversity and balanced training sources
- Identified need for BERT/RoBERTa transformer models for style-agnostic detection
- Recommended multi-dataset training as solution to avoid shortcut learning
- This limitation analysis became the most academically valuable contribution of the project

**Key Takeaway:** A well-documented model limitation and the ability to interrogate model decisions proved more valuable than achieving 99% accuracy.

---

### 🔹 Loan Approval Prediction System (End-to-End ML Deployment)
**Technologies:** Python · scikit-learn · FastAPI · Streamlit · REST API · Data Science <br>
**Repository:** https://github.com/MinoliPerera021126/loan-approval-ml-system <br>
**Created:** March 2026

Production-oriented machine learning system demonstrating a complete ML lifecycle from data preprocessing to model deployment.

**ML Pipeline & Model Development**
- Designed and implemented structured preprocessing pipeline using `ColumnTransformer` to handle missing values, categorical encoding, and feature scaling.
- Developed binary classification model using Random Forest with precision-focused hyperparameter tuning.
- Performed 5-fold cross-validation and evaluated model with metrics: ~84% accuracy, 0.85 precision, 0.94 recall for approved class.
- Conducted feature importance analysis and model interpretability assessment.

**Deployment & API Integration**
- Deployed trained model via FastAPI backend with RESTful API endpoints for real-time inference.
- Integrated Streamlit frontend for interactive prediction interface and data visualization.
- Implemented proper model versioning and inference pipeline for production use.

---

### 🔹 University Facility Management System — University of Sri Jayewardenepura  
**Technologies:** Django · Python · MySQL · Backend Development · Full-Stack <br>
**Repository:** https://github.com/Department-of-IT-FMSC-USJ/final-project-byte-mop <br>
**Created:** February 2026

Full-stack web application for institutional task management developed for **ITC3380 – Programming Applications & Frameworks** module.

**System Architecture & Features**
- University cleaning task management platform with role-based workflows
- Staff scheduling and intelligent duty assignment system
- Administrative dashboard with real-time task monitoring and reporting

**Backend Implementation**
- Designed and implemented Django backend with complex business logic.
- Structured relational database schema for efficient data management.
- Developed secure authentication and authorization mechanisms.
- Created responsive admin interfaces for stakeholder management.

---

### 🔹 BlueCradle — Infant Health Monitoring System (v2)
**Technologies:** Django · Python · MySQL · Healthcare Data Management <br>
**Repository:** https://github.com/MinoliPerera021126/bluecradle-infant-and-child-health-monitoring-system-v2 <br>
**Created:** February 2026 - In Progress

Comprehensive web application for managing infant healthcare data and monitoring health metrics.

**System Design & Features**
- Child registration and comprehensive medical record management  
- Vaccination tracking with automated scheduling
- Health metrics monitoring and clinic appointment management  
- Role-based access control for healthcare providers and parents  

**Technical Implementation**
- Relational database schema design optimized for healthcare data integrity and HIPAA considerations.
- Backend business logic implementation using Django framework.
- Modular system design ensuring scalability and maintainability.
- Secure data handling with appropriate access controls.

> ⚠️ *All data used in this project is synthetic and created for academic purposes only.*

---

## 🛠️ Tech Stack

**Programming Languages** 
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Python-Dark.svg" width="30" style="margin:8px;" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/CS.svg" width="30" style="margin:8px;" alt="C#" />
  <img src="https://skillicons.dev/icons?i=java" width="30" style="margin:8px;" alt="Java" />
</p>

<br>

**Machine Learning & Data Science** 
- scikit-learn · TensorFlow · PyTorch  
- Data Preprocessing & Feature Engineering  
- Model Evaluation & Hyperparameter Tuning  
- Statistical Analysis & Data Visualization  
- Natural Language Processing (NLP)  

<br>

**ML Deployment & Frameworks**  
<p style="margin-left:1em;">
  <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Django.svg" width="30" style="margin:8px;" alt="Django" />
  <img src="https://github.com/campusMVP/dotnetLogoPack/raw/main/.samples/asp-dotnet-mvc-white.png" width="30" style="margin:8px;" alt="ASP.NET" />
  <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/DotNet.svg" width="30" style="margin:8px;" alt=".NET" />
</p>

<br> 

**Data & Infrastructure**  
<p align="left"> 
  <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/MySQL-Dark.svg" width="30" style="margin:8px;" alt="MySQL" />
</p>

<br>

**AI & ML Foundations** 
- Azure AI & Machine Learning concepts  
- Supervised & Unsupervised Learning  
- Regression & Classification algorithms  
- Natural Language Processing techniques  
- Model deployment and inference  
- Responsible AI and ethical data practices  

<br>

**Development Tools**  
- Git & GitHub  
- Jupyter Notebook  
- VS Code  
- Streamlit & FastAPI  
- Pandas, NumPy, Matplotlib, Scikit-learn  
- RapidMiner  

---

## ✅ What I Prioritize in ML Projects

- **Data Quality:** Rigorous preprocessing, cleaning, and exploratory data analysis  
- **Model Reliability:** Robust evaluation metrics, cross-validation, and performance benchmarking  
- **Reproducibility:** Clear documentation, version control, and experimental tracking  
- **Production-Ready Code:** Clean architecture, modular design, and maintainability  
- **Performance Optimization:** Hyperparameter tuning, feature selection, and model ensemble techniques  
- **Interpretability:** Feature importance analysis and model explainability  
- **Ethical AI:** Responsible data handling, bias detection, and fairness assessment  
- **Practical Solutions:** Real-world problem-solving over theoretical complexity  

---

## 📌 What to Expect in Each Repository

- Clear `README.md` documentation with project objectives  
- Comprehensive data exploration and preprocessing steps  
- Model development with detailed algorithm comparisons  
- Performance evaluation with visualizations and metrics  
- Technical implementation details and code comments  
- Jupyter notebooks demonstrating complete ML workflows  
- Academic-safe or synthetic datasets only  

---

## 🏆 Achievements

- 🎖️ **Semi-Finalist — DHack'24 (UI/UX Competition)**  
- ⭐ **Most Popular Team — CyberZee'23**
- 🥈 **1st Runner-Up — Infinity 4.0**  

---

## 📌 How You Can Explore My Work

- 🌐 **Portfolio Website:** https://minoliperera021126.github.io/portfolio-minoli-perera/    
- 💻 **GitHub Projects:** Browse repositories for detailed ML implementations  
- 📊 **ML Projects:** Check featured repositories for end-to-end machine learning pipelines  
- 🔍 **Jupyter Notebooks:** Dive into data analysis and model training workflows  

Feel free to reach out for walkthroughs, demos, or technical discussions about any project.

---

## 🌍 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/hk-minoli-perera)  
[![Email](https://img.shields.io/badge/Email-me-red?style=for-the-badge&logo=gmail)](mailto:mnnetmi@gmail.com)

---

✨ *"Machine learning is the art of teaching machines to learn from data and make intelligent decisions."* ✨
