🫁 Lung Cancer Risk Potential Prediction using AQI and Pollutant Data

📌 Project Overview
This project predicts the risk potential of lung cancer based on Air Quality Index (AQI) and major air pollutants such as PM2.5, PM10, NO₂, SO₂, CO, and O₃. The aim is to help identify pollution-driven lung cancer vulnerabilities across geographical regions using Machine Learning. It combines environmental data and health risk analysis to assist policymakers, healthcare professionals, and researchers in understanding the correlation between air pollution and lung cancer.

🎯 Objectives
✅ Collect and preprocess AQI and pollutant datasets
✅ Combine pollution data with lung cancer incidence statistics
✅ Analyze pollutant-wise correlation with lung cancer cases
✅ Develop a machine learning model to predict lung cancer risk potential
✅ Visualize trends, key factors, and predictive insights
✅ Provide an explainable and actionable conclusion for public health

🛠️ Technologies Used
| Category         | Tools                                                   |
| ---------------- | ------------------------------------------------------- |
| Programming      | Python                                                  |
| Data Processing  | Pandas, NumPy                                           |
| Visualization    | Matplotlib, Seaborn                                     |
| Machine Learning | Scikit-learn (Random Forest, Logistic Regression, etc.) |
| Notebook         | Jupyter Notebook                                        |
| Version Control  | Git & GitHub                                            |


🔍 Exploratory Data Analysis (EDA)
✔ Distribution of pollutants
✔ Correlation heatmap (pollutants vs lung cancer)
✔ AQI category-wise lung cancer occurrence
✔ Trend analysis over cities/regions

🤖 Machine Learning Workflow
1. Data Cleaning & Preprocessing
2. Label Encoding / Risk Categorization
3. Train-Test Split
4. Model Training (Random Forest, Logistic Regression, SVM, etc.)
5. Performance Evaluation – Accuracy, Precision, Recall, F1-Score
6. Feature Importance Analysis

📊 Results
| Model               | Accuracy | Best Features   |
| ------------------- | -------- | --------------- |
| Random Forest       | ~XX%     | PM2.5, AQI, NO₂ |
| Logistic Regression | ~XX%     | AQI, PM10       |
| SVM                 | ~XX%     | PM2.5, SO₂      |
PM2.5 and AQI showed the strongest correlation with increased lung cancer risk potential.

💡 Key Insights
1. Higher PM2.5 and PM10 concentrations strongly correlate with lung cancer cases.
2. Cities with AQI > 200 fall in a high-risk zone.
3. Air pollution can be used as a predictive indicator for long-term health risks.
4. ML models can assist in early warning systems and preventive healthcare planning.

🚀 How to Run the Project
# Clone the repository
git clone https://github.com/oyyPoodles/Lung-Cancer-Risk-Potential-Prediction-using-AQI-and-Pollutants-Data.git

# Navigate into the project folder
cd Lung-Cancer-Risk-Potential-Prediction-using-AQI-and-Pollutants-Data

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook


✅ Future Improvements
1. Integrate real-time AQI APIs (OpenWeather, WAQI)
2. Deploy as a web app using Flask/Streamlit
3. Include demographic and smoking data for higher accuracy
4. Use Deep Learning models (LSTM, XGBoost, etc.)

👨‍💻 Authors
1. Ujjwal Chaudhary
🔗 GitHub: @oyyPoodles
2. Gautam yadav
🔗 GitHub: @oyyPoodles
3. Mayank Shah
🔗 GitHub: @
