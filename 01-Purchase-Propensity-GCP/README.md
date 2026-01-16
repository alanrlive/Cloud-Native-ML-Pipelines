**The Business Objective**
In high-volume e-commerce, the cost of customer acquisition is high. This project demonstrates a Propensity Model designed to predict the likelihood of a purchase in real-time. By identifying "High Intent" users, businesses can automate personalized discount triggers, optimize ad-spend, and improve conversion ROI.

**Tech Stack & Architecture**
Data Warehouse: Google BigQuery (Clickstream & User Data)
ML Infrastructure: Vertex AI (Model Registry & Prediction Endpoints)
Environment: Google Colab / Python 3.12
Core Libraries: Scikit-Learn (Random Forest), Pandas, NumPy

**Key Features of this Implementation**
End-to-End Automation: Seamlessly transitions from SQL-based data extraction to live REST API deployment.
Production-Grade Preprocessing: Handles a 250+ feature high-dimensional space with robust Schema Alignment to prevent inference errors.
Dynamic Environment Parity: Implemented logic to match training dependencies with Vertex AI pre-built serving containers (Sklearn 1.5).
Interpretability: Utilizes Random Forest feature importance to identify that Session Intensity and Traffic Source are the primary drivers of purchase intent.