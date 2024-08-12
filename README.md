# Medical Prediction Web App

This web application is just a test app to see how to deploy my apps in streamlit cloud. 

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on user input.
- **Calorie Burn Prediction**: Estimates the calories burned based on physical activity details.
- **Heart Disease Prediction**: Predicts the risk of heart disease.

## Live Demo

You can access the live version of the app [here](https://medical-prediction-web-app.streamlit.app).

## Installation

To run the app locally, follow these steps:

### Prerequisites

- Python 3.8+
- pip (Python package installer)

### Step 1: Clone the Repository

```
git clone https://github.com/your-username/medical-prediction-web-app.git
```

```
cd medical-prediction-web-app
```

### Step 2: Install Dependencies

Install the required Python packages using the following command:
```
pip install -r requirements.txt

```

### Step 3: Run the App
Once the dependencies are installed, you can run the Streamlit app with the following command:
```
streamlit run Medical_Predictive_Web_App.py
```
### Step 4: Access the App

After running the command, the app will be available in your browser at `http://localhost:8501`.

## File Structure

- **Medical_Predictive_Web_App.py**: The main Python script that runs the Streamlit app.
- **requirements.txt**: Lists all the Python dependencies required for the app.
- **trained_calorie_burn_model.sav**: Pre-trained model for calorie burn prediction.
- **trained_diabetes_model.sav**: Pre-trained model for diabetes prediction.
- **trained_heart_disease_model.sav**: Pre-trained model for heart disease prediction.

## Deployment

The app is deployed on Streamlit Cloud. To redeploy or update the app:

1. Push your changes to the GitHub repository.
2. Streamlit Cloud will automatically detect the changes and redeploy the app.

## Contributing

If you'd like to contribute to the project, feel free to open a pull request or submit an issue. We welcome all contributions!

## Contact

For any inquiries, please contact **Arefin Amin** at [arefinamin994@gmail.com](mailto:arefinamin994@gmail.com).
