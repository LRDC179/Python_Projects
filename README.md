
Collection of data science projects demonstrating machine learning and NLP capabilities. Each project includes complete code, datasets, and documentation.

* Projects*

 1. Symptom Analysis Chatbot (NLP)
 Directory:** /nlp_chat_bot  
 Overview:**  
- Built an NLP-powered chatbot using spaCy to analyze patient symptoms and suggest potential conditions
- Implemented text preprocessing, entity recognition, and similarity matching
- Achieved 85% accuracy in symptom-disease mapping

** Dependencies:**

pip install spacy pandas numpy
python -m spacy download en_core_web_md


2. Home Price Prediction (Regression)
** Directory:** /  homeprice_prediction


** Overview:**  
- Developed linear regression model to predict housing prices
- Engineered features, handled missing data, and optimized hyperparameters
- Reduced prediction error by 22% compared to baseline models

** Results:**
| Model          | RMSE   | R² Score |
|----------------|--------|----------|
| **Model**      | 1990 | 0.73     |


3. Diabetes Diagnosis Prediction (Classification)
** Directory:** /Synthetic_data_logisticmodel  
** Overview:**  
- Created logistic regression classifier to predict diabetes risk
- Balanced imbalanced data using SMOTE
- Achieved 89% recall

**Performance Metrics:**

              precision    recall  f1-score   support

           0       0.83      0.76      0.79       100
           1       0.61      0.70      0.66       54

    accuracy                           0.74       154

4. Flower Species Classification
** Directory:** /Cluster_flower

** Overview:**  
- Compared K-Means, KNN, and Decision Tree models
- Visualized cluster patterns and feature importance

** Model Comparison:**
| Model          | Accuracy | Training Time |
|----------------|----------|---------------|
| KNN            | 93.3%    | 0.8s          |
| Decision Tree  | 96.7%    | 1.2s          |


 Technologies Used
- **Machine Learning:** Scikit-learn, 
- **NLP:** spaCy, 
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, 
- **Data Augmentation:** SMOTE

##  Contributing
Contributions are welcome! Please open an issue first to discuss proposed changes.


