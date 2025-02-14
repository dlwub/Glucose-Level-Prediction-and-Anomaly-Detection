# OhioT1DM Glucose Prediction and Anomaly Detection

📌 **Project Overview**

This project uses LSTM models and Autoencoders to analyze glucose levels in the OhioT1DM dataset. The goal is to:

Parse and extract glucose data from XML files.

Perform data visualization and feature engineering.

Convert glucose data into a time series format.

Train an LSTM model for glucose prediction.

Detect glucose anomalies using Autoencoders.

Deploy the model via FastAPI and Streamlit for real-time analysis.

📂 **Project Description**

This repository contains code and resources for developing a machine learning pipeline for glucose prediction and anomaly detection using the OhioT1DM dataset. It includes data preprocessing, feature engineering, time-series modeling, and deployment scripts for real-time analysis.

📂 **Dataset**

OhioT1DM Dataset (contains glucose level readings in XML format)

Features:

Glucose

Hour

DayOfWeek

Rolling_Mean

Rolling_Std

Glucose Scaled

⚙️ **Setup & Installation**

1️⃣ **Clone the Repository**

git clone https://github.com/your-username/ohiot1dm-glucose-prediction.git
cd ohiot1dm-glucose-prediction

2️⃣ **Create a Virtual Environment (Optional but Recommended)**

python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

3️⃣ **Install Dependencies**

pip install -r requirements.txt

🛠 Project Workflow

1️⃣ **Parsing XML & Extracting Data**

Reads glucose data from XML files.

Converts data into structured Pandas DataFrame.

Saves it as glucose_data.csv.

2️⃣ **Data Preprocessing & Feature Engineering**

Handling missing values.

Feature scaling (MinMaxScaler).

Creating rolling statistical features (Rolling Mean, Rolling Std).

3️⃣ **Time Series Conversion & LSTM Training**

Converts the glucose data into time series sequences.

Trains an LSTM model for glucose prediction.

Evaluates performance with loss curves & MAE.

4️⃣ **Anomaly Detection with Autoencoders**

Trains an Autoencoder model to detect anomalies.

Visualizes anomalous glucose readings.

🔥 **Future Improvements**

Integrate real-time glucose sensor data.

Deploy API & Web App on AWS/GCP.

Improve anomaly detection using Generative Models.

👨‍💻 **Author**

Desta Legesse Wubishet

Email: dlwubi@gmail.com

GitHub: dlwub

📜 **License**

This project is licensed under the MIT License.
