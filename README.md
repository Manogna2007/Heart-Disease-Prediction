❤️ Heart Disease Prediction using Machine Learning

 Project Overview : 

This project is a Machine Learning web application that predicts whether a person is at risk of heart disease based on various medical parameters. The model is trained using a heart disease dataset and is deployed as an interactive web application using Streamlit.
Users can enter their health-related information through a simple web interface and receive an instant prediction indicating whether they are likely to have heart disease.


 Features : 

- Interactive and user-friendly web interface built with Streamlit
- Predicts the likelihood of heart disease in real time
- Uses a trained Machine Learning model
- Loads the trained model using Joblib
- Fast and easy to use
- Can be deployed online for public access


🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- Numpy
- Scikit-learn
- Joblib
- Jupyter Notebook
- seaborn
- matplotlib
---

📂 Project Structure

HeartDiseasePrediction/
│── app.py                 # Streamlit application
│── project.ipynb          # Model training notebook
│── heart_model.pkl        # Trained machine learning model
│── requirements.txt       # Required Python packages
│── README.md 

# Project documentation

-
📊 Machine Learning Workflow

1. Load the heart disease dataset.
2. Perform data preprocessing and cleaning.
3. Split the dataset into training and testing sets.
4. Train the Machine Learning model.
5. Evaluate the model.
6. Save the trained model using Joblib.
7. Build a Streamlit web application.
8. Load the saved model and make predictions based on user input.


⚙️ Installation

Clone this repository:

git clone https://github.com/Manogna2007/HeartDiseasePrediction.git

Move into the project directory:

cd HeartDiseasePrediction

Install the required packages:

pip install -r requirements.txt

---

▶️ Running the Application

Start the Streamlit application:

streamlit run app.py

After running the command, Streamlit will automatically open the application in your default web browser.

---
##LIVE DEMO :

🔗 https://manogna2007-heart-disease-prediction-app-q7hoqo.streamlit.app/

📈 Input Features

The application accepts medical parameters such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression (Oldpeak)
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia

---

🎯 Output

The application predicts one of the following:

- Heart Disease Detected
- No Heart Disease Detected

---

💡 Future Improvements

- Improve model accuracy using hyperparameter tuning.
- Compare multiple Machine Learning algorithms.
- Deploy the application using Streamlit Community Cloud.
- Add data visualization dashboards.
- Improve the user interface.
- Add probability/confidence score for predictions.

---

Developed as a Machine Learning project using Python, Scikit-learn, Joblib, and Streamlit.
