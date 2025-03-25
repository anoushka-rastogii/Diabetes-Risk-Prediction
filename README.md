# Early Stage Diabetes Risk Prediction  

This project predicts the risk of **early-stage diabetes** using machine learning models. The dataset consists of **520 records with 17 attributes**, capturing demographic, clinical, and symptom-based features. The goal is to classify individuals as **"Positive" or "Negative"** for diabetes risk.  

## Dataset Details  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/529/early+stage+diabetes+risk+prediction+dataset)  
- **Features**:  
  - **Demographic:** Age, Gender  
  - **Symptoms:** Polyuria, Polydipsia, Sudden Weight Loss, Weakness, Visual Blurring, Itching, etc.  
  - **Target Variable:** "Class" (Positive/Negative for diabetes risk)  

##  Techniques & Models Used  
- **Preprocessing**:  
  - Label Encoding for categorical variables  
  - Standard Scaling for numerical data  
  - Train-Test Split (80%-20%)  

- **Machine Learning Models**:  
  - **Logistic Regression**  
  - **Decision Tree Classifier**  
  - **Support Vector Machine (SVM)**  
  - **K-Nearest Neighbors (KNN)**  
  - **Random Forest Classifier**  

- **Evaluation Metrics**:  
  - Accuracy Score  
  - Precision, Recall, F1-Score  
  - Classification Report

 ## Results  
- **Best Model:** Support Vector Machine (SVM)  
- **Accuracy Achieved:** 98.08%  
- **Key Insights:**  
  - **Support Vector Machine (SVM)** achieved the highest accuracy (98.08%) and recall (99.02%), making it the best-performing model for early-stage diabetes risk prediction.  
  - **Decision Tree (97.44%)** also performed well, providing strong interpretability but with a risk of overfitting.  
  - **Logistic Regression (93.59%)** was a strong, interpretable baseline model but struggled with non-linearity.  
  - **k-Nearest Neighbors (90.38%)** had the lowest recall, meaning it missed positive cases more often.  

Overall, **SVM is the recommended model** for predicting early-stage diabetes risk due to its high accuracy and ability to correctly classify positive cases. However, **Decision Trees** remain a strong alternative with better interpretability.
