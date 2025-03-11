# Air Quality Index (AQI) Prediction

## 📌 Project Overview
This project aims to predict the **Air Quality Index (AQI)** using various machine learning models. The dataset used was obtained from online sources containing air pollutant data. The workflow involved:

✅ Data Collection and Preprocessing  
✅ Data Cleaning and Feature Engineering  
✅ Exploratory Data Analysis (EDA)  
✅ Model Building and Evaluation  
✅ Model Deployment for Real-Time Predictions  

## 🚀 Technologies Used
- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy** (Data Processing)
- **Matplotlib**, **Seaborn** (Data Visualization)
- **scikit-learn**, **XGBoost** (Machine Learning Models)
- **Flask/Streamlit** (Deployment)

## 📂 Dataset Information
The dataset includes the following features:
- **Input Features:** `PM2.5`, `PM10`, `NO`, `NO2`, `NOx`, `NH3`, `CO`, `SO2`, `O3`, `Benzene`, `Toluene`, `Xylene`
- **Output Feature:** `AQI` (Target Variable)

## 🔍 Data Preprocessing
1. **Handling Missing Values** – Imputed missing values using appropriate strategies.
2. **Outlier Treatment** – Identified and handled extreme values.
3. **Feature Scaling** – Applied standardization for better model performance.
4. **Feature Engineering** – Derived meaningful insights from existing features.

## 📊 Exploratory Data Analysis (EDA)
- Visualized pollutant distributions using histograms, boxplots, and scatter plots.
- Analyzed correlations between features to identify key contributors to AQI.

## 🤖 Model Building and Evaluation
The following models were implemented and evaluated:

| **Model**             | **R² Score** | **MAE**      |
|-----------------------|---------------|----------------|
| Random Forest          | 0.845         | 21.53           |
| XGBoost                | 0.837         | 22.49           |
| Decision Tree          | 0.693         | 29.02           |
| Linear Regression      | 0.656         | 35.35           |
| Support Vector Machine | 0.637         | 32.28           |

**Best Model:** Random Forest Regressor (Highest R² score and lowest MAE)

## 🖥️ Deployment
- Deployed the best-performing model using **Flask** for web-based interaction.
- The user can input pollutant values, and the model predicts the corresponding AQI value.

## 📋 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train and evaluate models.
4. To deploy the model using Flask, run:
   ```bash
   python app.py
   ```
5. Open the provided **localhost link** in your browser.

## 📈 Future Improvements
✅ Integrate real-time data from APIs for live AQI predictions.  
✅ Experiment with deep learning models for improved accuracy.  
✅ Implement automated hyperparameter tuning techniques.

## 🧑‍💻 Contributing
Contributions are welcome! Feel free to raise issues or submit pull requests.

## 📞 Contact
For questions or collaboration, reach out at: **your.email@example.com**

# My-Projects
I keep my value added projets here
