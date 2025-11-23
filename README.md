🟧 End-to-End MLOps Project on Databricks (Telco Customer Churn)

This project implements a complete production-style MLOps workflow using Databricks Community Edition, covering:

       Data ingestion (Bronze)

       Data cleaning & transformations (Silver)

       Feature engineering tables

       ML model training with MLflow tracking

       Batch inference with Delta Gold table

       GitHub-integrated development workflow

       Automated pipeline orchestration using Databricks Jobs

🏗️ Architecture
Raw CSV → Bronze Table
       → Silver Clean Table
       → Feature Table
       → ML Training (MLflow)
       → Batch Inference (Gold Predictions)

📂 Repository Structure
/notebooks
    01_bronze_ingestion
    02_silver_transform
    03_feature_engineering
    04_train_mlflow
    05_batch_inference

🔧 Technologies Used

       Databricks Community Edition

       Spark / PySpark

       MLflow Tracking

       Delta Lake (Bronze/Silver/Gold)

       GitHub Repos Integration

       Scikit-learn

       Databricks Jobs (orchestration)

📊 Model Performance

       Best model: RandomForestClassifier

       Accuracy: ~0.80

       ROC AUC: ~0.84

       Tracked under MLflow Run ID:cd36fb2b675e4cef86a1e0f1d26fb76c

🧪 Batch Inference Output (Gold Table)

       Gold table: churn_mlo_mdb.gold_predictions

       Includes: All engineered features

       Predicted churn probability

       Predicted label

       run_id (for lineage)

       scoring_timestamp
Screen shots for proof of work 
Creation of Mlflow pipeline :<img width="1910" height="903" alt="image" src="https://github.com/user-attachments/assets/53d54132-284c-49df-a47e-6dcbb3fb8d98" />
Link of github repo and creation of notebooks <img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/c6477fe4-2be0-4091-996e-bef62617000c" />
