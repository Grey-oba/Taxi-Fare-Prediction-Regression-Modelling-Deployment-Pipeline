# Taxi Fare Prediction: Regression Modelling & Deployment Pipeline

## Objective

This project explores taxi fare prediction within modern urban mobility systems, where ride‑sharing platforms rely on dynamic pricing influenced by demand, traffic, weather, and time‑based patterns. Using a multivariate dataset containing trip details, temporal features, cab type, and environmental conditions, the goal was to build and compare several regression models to identify the most effective approach for predicting ride prices.

The workflow includes full preprocessing, model training, evaluation, and deployment through a lightweight Gradio GUI for single‑record fare prediction.



### Skills Learned

- Building modular regression pipelines using scikit‑learn.
- Applying preprocessing with ColumnTransformer (scaling + one‑hot encoding).
- Training and comparing multiple regression models.
- Evaluating performance using RMSE, MAE, and R².
- Handling real‑world data issues (noise, missing values, non‑linear relationships).
- Deploying a trained model through a Gradio interface.

### Tools Used

- *pandas* and *NumPy* for data cleaning, transformation, and preparation.
- *scikit‑learn* for preprocessing (ColumnTransformer), regression modelling, and performance evaluation.
- *Matplotlib* and *Seaborn* for visualising predictions, residuals, and model behaviour.
- *pickle* for saving and loading trained models within the pipeline.
- *Gradio* for deploying the best‑performing model through an interactive GUI for single‑record fare prediction.

## Steps
The analysis follows a structured workflow: 

1. 	Data preprocessing and wrangling, including cleaning, handling missing values, feature engineering (such as extracting time‑based features), and transforming categorical and numerical variables. 

2. 	Exploratory Data Analysis (EDA) to uncover patterns, distributions, correlations, and insights relevant to urban mobility behaviour.
<img width="384" height="252" alt="image" src="https://github.com/user-attachments/assets/e62895c9-5f69-4d8e-9622-50c87619f977" />
<img width="401" height="261" alt="image" src="https://github.com/user-attachments/assets/6c11b6bf-4a2b-4d77-be5d-da3cbab9faa4" />
<img width="307" height="200" alt="image" src="https://github.com/user-attachments/assets/2312a3c7-366c-4611-9871-e8a3583fcb82" />


3. 	Model development, where four machine learning algorithms (Linear Regression, Decision Tree Regressor, Random Forest Regressor, and K‑Nearest Neighbours(KNN) ) are trained and evaluated. 
<img width="340" height="251" alt="image" src="https://github.com/user-attachments/assets/adc1d106-fe8c-4306-a838-01216c1de52f" />


4. 	Comparative performance assessment using metrics such as RMSE, MAE, and R², supported by visualisations including residual plots and prediction‑error distributions. 
<img width="644" height="257" alt="image" src="https://github.com/user-attachments/assets/548cf367-365d-49fd-8489-fa59f849e636" />
<img width="469" height="273" alt="image" src="https://github.com/user-attachments/assets/3a0ec9a2-074b-4667-a48e-d5b10e29e7d0" />



5. 	Deployment, where the best‑performing model is integrated into a simple graphical user interface (GUI) to allow single‑record fare prediction. 
drag & drop screenshots here or use imgur and reference them using imgsrc
<img width="629" height="273" alt="image" src="https://github.com/user-attachments/assets/9b34d1db-3d50-40bb-95c4-e354af1dd326" />

