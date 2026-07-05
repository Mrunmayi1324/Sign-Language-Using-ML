#  AI Sign Language Recognition System

An AI-powered Sign Language Recognition System that classifies American Sign Language (ASL) hand gestures using Machine Learning algorithms. The project compares multiple classification models and identifies the best-performing model for recognizing sign language alphabets.

---

##  Project Overview

This project aims to bridge the communication gap between hearing-impaired individuals and others by recognizing hand gestures from image data.

The system is trained on the **Sign Language MNIST Dataset** and evaluates multiple Machine Learning algorithms including:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- XGBoost
- K-Means (Clustering)

The project also performs model comparison, hyperparameter tuning, ROC-AUC analysis, feature importance visualization, and statistical evaluation.

---

##  Features

- Image Classification using Machine Learning
- Data Preprocessing and Normalization
- Multiple ML Model Training
- Model Performance Comparison
- Hyperparameter Tuning
- Cross Validation
- Confusion Matrix Visualization
- ROC Curve & AUC Score
- Feature Importance Analysis
- Final Model Evaluation on Test Dataset
- Model Export using Joblib

---

##  Machine Learning Algorithms Used

| Model | Purpose |
|--------|----------|
| Logistic Regression | Baseline Classification |
| Support Vector Machine (SVM) | High Accuracy Classification |
| Decision Tree | Tree-Based Classification |
| Random Forest | Ensemble Learning |
| XGBoost | Boosting Algorithm |
| K-Means | Unsupervised Clustering |

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

##  Dataset

**Dataset:** Sign Language MNIST

The dataset contains grayscale images of hand gestures representing American Sign Language (ASL) alphabets.

Each image consists of:

- 28 × 28 pixels
- 784 numerical features
- Label column representing gesture class

---
##  Project Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Feature Scaling
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
(Logistic Regression,
SVM,
Decision Tree,
Random Forest,
XGBoost)
   │
   ▼
Model Evaluation
   │
   ▼
Performance Comparison
   │
   ▼
Hyperparameter Tuning
   │
   ▼
ROC-AUC Analysis
   │
   ▼
Feature Importance
   │
   ▼
Final Prediction
```

---

##  Performance Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross Validation
- ROC Curve
- AUC Score

---

##  Visualizations Included

- Sample Sign Language Image
- Confusion Matrix
- Model Accuracy Comparison
- ROC Curve
- Model Improvement Graph
- Feature Importance Plot

---

##  Model Export

The trained Random Forest model is saved using Joblib.

```python
joblib.dump(rf, "sign_language_model.pkl")
```

---

##  Project Structure

```
AI-Sign-Language-Recognition/
│
├── Dataset/
│   ├── sign_mnist_train.csv
│   └── sign_mnist_test.csv
│
├── sign_language_recognition.py
│
├── sign_language_model.pkl
│
├── README.md
│
└── requirements.txt
```

---

##  Installation

Clone the repository

```bash
git clone https://github.com/yourusername/AI-Sign-Language-Recognition.git
```

Navigate to the project folder

```bash
cd AI-Sign-Language-Recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python sign_language_recognition.py
```

---

##  Requirements

```
Python 3.10+

pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
joblib
```

Install using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
```

---

##  Future Enhancements

- Real-time Sign Language Recognition
- Webcam Integration
- Deep Learning using CNN
- TensorFlow/Keras Implementation
- Sentence Formation from Gestures
- Flask/Django Web Application
- Mobile Deployment

---

##  Learning Outcomes

- Machine Learning Classification
- Image Data Processing
- Model Evaluation
- Ensemble Learning
- Hyperparameter Tuning
- Feature Engineering
- Performance Visualization
- AI-based Gesture Recognition

---

##  Contributing

Contributions are welcome!

Feel free to fork the repository, improve the project, and submit a pull request.

---

##  License

This project is developed for educational and portfolio purposes.

---

##  Author

**Mrunmayee Gholap**

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer



---

⭐ If you found this project useful, don't forget to **Star** the repository!
