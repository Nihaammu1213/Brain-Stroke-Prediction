This project is a Flask web application that predicts the risk of brain stroke using a Logistic Regression model trained on health-related data.  
It also provides a symptom-based stroke classification and suggests details & treatments for different stroke types.  

  Predicts whether a person is at risk of a brain stroke based on:
  Gender, Age, Hypertension, Heart Disease, Marriage status, Work type, Residence type, Glucose level, BMI, and Smoking status.  
  Symptom-based classification into different stroke types:
    Ischemic Stroke  
    Hemorrhagic Stroke  
    Transient Ischemic Attack (TIA)  
    Cryptogenic Stroke  
    Brain Stem Stroke  
    Cerebellar Stroke  
    Stroke due to Aneurysm  
  Provides medical details and treatment guidelines for each stroke type.  
  Simple web interface using Flask + HTML templates.  


  Backend:Python, Flask
  Frontend:HTML, Jinja2 Templates  
  ML Model: Logistic Regression (trained with `scikit-learn`)
  Storage: Pickle (`model.pkl`) for saving the trained model 
