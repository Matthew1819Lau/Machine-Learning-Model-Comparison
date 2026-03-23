## What is the project about :question:
Project name: [Machine Learning Model Comparison for Student Exam Performance](https://github.com/Matthew1819Lau/Machine-Learning-Model-Comparison/blob/main/A1_Poster_Matthew%20Lau_250060300.pdf)

- Conducted a machine learning study to evaluate and compare model performance in predicting student exam outcomes and supporting data-driven decision-making in education.
- Implemented two machine learning models: (i) Logistic Regression and (ii) Naive Bayes using MATLAB to evaluate prediction accuracy.

## How were the problems addressed :interrobang:
  - Performed initial data analysis, including correlation analysis, to identify relationships between variables and select relevant features for model training.
  - Split the dataset into training and testing sets, applying 5-fold cross-validation to reduce overfitting and improve generalisation.
  - Compared both models using evaluation metrics such as Recall and ROC-AUC to ensure a fair assessment and stability.<img width="434" height="308" alt="Screenshot 2026-03-22 at 11 47 17 PM" src="https://github.com/user-attachments/assets/08bc7b90-5477-450b-b42e-a8f90870935b" />

## Results
- Logistic Regression correctly classified 424 true positives and 1521 true negatives, with only 13 false positives and 24 false negatives, a high number of True Positives and True Negatives demonstrating highly accurate predictions.
- Naïve Bayes correctly classified 254 true positives and 1524 true negatives, with only 10 false positives and 194 false negatives, that also suggest strong predictive accuracy and reliability.

<img width="481" height="461" alt="Screenshot 2026-03-22 at 11 48 12 PM" src="https://github.com/user-attachments/assets/a2132710-1480-4fc8-b066-2e869ac4b0b1" /><img width="466" height="336" alt="Screenshot 2026-03-22 at 11 48 20 PM" src="https://github.com/user-attachments/assets/12b82886-c5d7-428e-ac76-98bde5ad4a69" />

-  Logistic Regression achieved an ROC-AUC score of 0.996, indicating excellent predictive performance.
-  Naïve Bayes achieved an ROC-AUC score of 0.978, also demonstrating strong classification capability.
  <img width="451" height="466" alt="Screenshot 2026-03-22 at 11 48 00 PM" src="https://github.com/user-attachments/assets/802b509c-828e-4d39-adb1-33274174c2f4" />

-  Overall, Logistic Regression outperformed Naïve Bayes, making it the better-performing model for this task. However, the models may be benefiting from class imbalance, where one class dominates the dataset.
  
## What I have learnt :heavy_exclamation_mark:
- Highlighted the importance of proper data preprocessing, cross-validation, and the use of multiple evaluation metrics when comparing machine learning models.
- Found that the ROC curve and AUC are effective for threshold-independent model evaluation.
- Recognised the need to further improve model generalisation and robustness.
  
## Future Improvements :chart_with_upwards_trend:
- To address the extremely high performance scores (>95%) observed in both models, I will focus on handling potential class imbalance before model training in future work.
- In addition, further improvements will include incorporating additional features and exploring more advanced classifiers, such as Random Forest and Support Vector Machine (SVM), to enhance model robustness and generalisation.







