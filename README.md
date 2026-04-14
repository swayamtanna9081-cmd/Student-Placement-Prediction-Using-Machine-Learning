
# 📊 Student Placement Prediction Using Machine Learning

This project presents a machine learning-based approach to predict the placement outcomes of engineering students. It combines both classification and clustering techniques to analyze student data and identify patterns that influence placement success.

## 🚀 Project Overview

Campus placement is a crucial milestone for engineering students. This project aims to automate the prediction process using machine learning models instead of traditional manual evaluation.

The system predicts whether a student will be **Placed (1)** or **Not Placed (0)** based on various academic, skill-based, and socio-economic factors.

## 🧠 Models Implemented

- **K-Nearest Neighbours (KNN)** – Classification based on similarity
- **Decision Tree** – Rule-based classification model
- **K-Means Clustering** – Unsupervised learning for pattern discovery

## ⚙️ Workflow
Load Dataset → Merge → Preprocess → Scale → Train-Test Split → Train Models → Evaluate


## 📊 Results

- **KNN Accuracy:** ~86%
- **Decision Tree Accuracy:** ~85%
- **K-Means Accuracy:** ~86%

### 🔍 Key Insights:
- CGPA and backlogs are the most important factors affecting placement
- KNN achieved the best recall performance
- K-Means showed strong clustering even without labels

## 📁 Dataset

The dataset contains information of **5,000 engineering students**, including:
- Academic performance (CGPA, marks, backlogs)
- Skills (coding, aptitude, communication)
- Internships and projects
- Socio-economic factors

## 📈 Visualizations

The project generates:
- Accuracy comparison graphs
- Precision, Recall, F1-score charts
- Confusion matrices
- Feature importance graph
- Class distribution
- Radar chart comparison

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 🎯 Conclusion

This project demonstrates that machine learning can effectively predict student placement outcomes. It can help colleges identify at-risk students early and provide targeted support to improve placement rates.

## 🔮 Future Scope

- Hyperparameter tuning
- Ensemble models (Random Forest, XGBoost)
- Real-world dataset validation
- Web-based prediction system

## 👨‍💻 Authors

- Parth Solanki  
- Swayam Tanna  
- Jay Thakkar  

