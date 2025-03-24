# Heart Disease Prediction

## Overview
This project is an AI-powered system that predicts the likelihood of heart disease based on input medical data. It utilizes machine learning models such as Logistic Regression, SVM, and Random Forest to classify patient data and provide a probability score of having heart disease.

## Features
- Predicts the presence of heart disease based on user input.
- Uses multiple machine learning models for better accuracy.
- Interactive web-based interface using Streamlit.
- User-friendly UI for entering medical parameters.
- Provides visual representation of model performance and predictions.

## Dataset
The project uses the **Multiple Disease Prediction Dataset**, which includes features like:
- Age
- Sex
- Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression
- Slope of Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia Type

## Technologies Used
- **Frontend**: Streamlit
- **Backend**: Python, Flask
- **Machine Learning Models**: Logistic Regression, SVM, Random Forest
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/heart-disease-prediction.git
   cd heart-disease-prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the web app in your browser.
2. Enter the required medical parameters.
3. Click **Predict** to get the result.
4. View the predicted risk of heart disease and suggestions.

## Results
The system outputs a probability score and visualizes key data insights. Below are sample results:
- **Prediction Output:** Displays a percentage probability of heart disease.
- **Graphs & Charts:** Visualizes feature importance and model performance.

## Screenshots
![image](https://github.com/user-attachments/assets/0b1f9cd3-3bd2-4aa1-9489-8af1887a95e3)

![image](https://github.com/user-attachments/assets/3eb1e743-16c6-463f-a26f-6138f7767302)



## Future Enhancements
- Add more disease predictions.
- Improve model accuracy with deep learning.
- Deploy on cloud platforms for wider accessibility.


