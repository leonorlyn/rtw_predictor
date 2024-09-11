# Return to Work Recommendation Model
Overview
The "Return to Work Recommendation Model" is a machine learning project designed to predict the likelihood of an individual returning to work. It considers various demographic, socio-economic, and health-related factors and suggests interventions to increase the probability of re-employment.

# Project Demo
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/T_P2lZYNuNI/0.jpg)](https://www.youtube.com/watch?v=T_P2lZYNuNI)\
[Youtube Link](https://www.youtube.com/watch?v=T_P2lZYNuNI)

# Features
Predictive Modeling: Utilizes a Random Forest Classifier to predict a return to work likelihood.
Intervention Recommendations: Provides top 3 actionable interventions based on individual profiles.
Synthetic Data Generation: Includes a utility to generate synthetic datasets for model training and testing.
Dataset Generation
The dataset for training the model is synthetically generated to simulate real-world scenarios. The `generate_data.py` script creates this dataset with features such as age, gender, education level, immigration status, income, housing situation, and mental health status.

# Model Training and Evaluation
The model is trained using the scikit-learn library's Random Forest Classifier. It has been evaluated to achieve an accuracy of approximately [89]% on the test set.

# Getting Started
Prerequisites
Ensure you have Python installed on your machine (Python 3.8+ recommended). You will also need pip for installing Python packages.

# Installation
1. **Clone the repository:**
`git clone https://github.com/CaseManagementAI/team-neu-leonorlyn-zz39-stellawangengineer`
2. **Navigate to the repository folder:**
`cd path_to_repository`
3. **Install the required Python libraries:**
`pip install -r requirements.txt`

# Generate the datasets
Run to generate datasets
`python generate_data.py`
The dataset will be saved to /Spring6/dataset/

Train and evaluate the model:
`python /Spring6/model/rtw_model.py`


# Start the backend server:
1. **Navigate to the backend directory：**
`cd backend/model`
2. **Start the FastAPI server：**
`uvicorn main:app --reload`

# Run the frontend:
1. **Navigate to the frontend directory：**
`cd rtw-predictor`
2. **Install necessary packages:**
`npm install`
3. **Start the frontend:**
`npm start`


# rtw_predictor
