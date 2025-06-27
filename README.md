
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
| Baseline       | 145000 | 0.62     |
| **Final Model**| 113000 | 0.83     |

3. Diabetes Diagnosis Prediction (Classification)
** Directory:** /diabetes-prediction  
** Overview:**  
- Created logistic regression classifier to predict diabetes risk
- Balanced imbalanced data using SMOTE
- Achieved 89% recall

**Performance Metrics:**

              precision    recall  f1-score   support

           0       0.92      0.86      0.89       500
           1       0.78      0.89      0.83       268

    accuracy                           0.87       768

4. Flower Species Classification
** Directory:** /flower-classification 

** Overview:**  
- Compared K-Means, KNN, and Decision Tree models
- Visualized cluster patterns and feature importance

** Model Comparison:**
| Model          | Accuracy | Training Time |
|----------------|----------|---------------|
| K-Means        | 89.3%    | 0.4s          |
| KNN            | 95.7%    | 0.8s          |
| Decision Tree  | 97.1%    | 1.2s          |


 Technologies Used
- **Machine Learning:** Scikit-learn, 
- **NLP:** spaCy, 
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, 
- **Data Augmentation:** SMOTE

##  Contributing
Contributions are welcome! Please open an issue first to discuss proposed changes.


