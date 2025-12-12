<html>
  <head>
    <h1><b><i>CHRONIC KIDNEY DISEASE ANALYSIS</i></b></h1>
  </head>
  <body>
    <p>A chronic kidney disease (CKD) analysis provides a comprehensive summary of patient data, key clinical metrics, and predictive insights derived from relevant datasets. The analysis highlights the influence of critical features such as creatinine, eGFR on CKD status and progression.</p>
    <h2> <b>Problem Statement</b></h2>
    <p>To develop a machine learning model that predicts the presence or absence of Chronic Kidney Disease (CKD) using clinical and laboratory features, enabling early detection and risk stratification for timely intervention. This invovles:
    <ul>
      <li>Identifying key predictors of CKD (e.g., creatinine, GFR, BUN, age, diabetes, hypertension).</li>
      <li>Building and evaluating a Random Forest classifier to accurately predict CKD status.</li>
      <li>Interpreting the model to highlight the most influential features for clinical relevance and decision-making.</li></ul>   
        </p>
    <h2><b>Work Flow</b></h2>
    <img src = "https://github.com/user-attachments/assets/70aa59ee-67ec-4a5a-a1ee-61414de6b121" alt = "Workflow">
    <h2>Insights</h2>
    <p><b>1. Feature Importance:</b><br>The most important predictors of CKD are typically creatinine, GFR, BUN, age, diabetes, and hypertension. These features consistently show high importance in the Random Forest model, indicating their strong association with CKD status.</p>
    <p><b>2. Data Quality and cleaning:</b><br>The dataset required minimal cleaning, with few missing values and duplicates. This suggests the data is reliable and suitable for modeling.</p>
    <p><b>3. Model Performance:</b><br>The Random Forest model achieved high accuracy, precision, recall, and ROC-AUC, indicating it is effective in predicting CKD. This demonstrates the model's ability to distinguish between CKD and non-CKD cases.</p>
    <p><b>4. Clinical Relevance:</b><br>The insights from feature importance and model interpretation can guide clinicians in identifying high-risk patients and focusing on key risk factors for early intervention.</p>
    <p><b>5. Outlier Detection:</b><br>Box plots revealed the presence of outliers in key features, which were handled during preprocessing. This ensures the model is not unduly influenced by extreme values.</p>
    <p><b>6. Scalability and Deployment:</b><br>The workflow is scalable and can be deployed in clinical settings, enabling real-time predictions and risk stratification for CKD.</p>
    <h2><b>Model Training</b></h2>
    <p><b> Algorithm Used:</b><br>Random Forest Classifier, which is robust and effective for classification tasks.</p>
    <p><b> Training Process:</b><br>The model was trained on the preprocessed and feature-selected training dataset. The Random Forest algorithm builds multiple decision trees and aggregates their predictions to improve accuracy and reduce overfitting.</p>
    <p><b> Key Parameters:</b><br> The model was initialized with parameters like n_estimators (number of trees), max_depth (maximum depth of trees), and others to optimize performance.</p>
    <img src = "https://github.com/user-attachments/assets/1c1f8a44-fe42-4b92-bec3-f1e97febee99" >
    <img src = "https://github.com/user-attachments/assets/639661ec-b1be-4677-978e-f970526760da">
    <h2><b>Result</b></h2>
    <ol>
      <li>The Random Forest model achieved high accuracy, precision, recall, and ROC-AUC, demonstrating its effectiveness in predicting CKD.</li>
      <li>The model was evaluated using cross-validation to ensure robustness and avoid overfitting.</li>
    </ol>
    <img src="https://github.com/user-attachments/assets/14ae8a10-266f-4632-833b-350552a5db55">

  </body>
</html>

