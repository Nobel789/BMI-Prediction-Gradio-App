# BMI-Prediction-Gradio-App
End-to-End ML project deploying a Random Forest BMI classifier as an interactive web app using Gradio."*
# 🚀 End-to-End ML Deployment: Interactive BMI Predictor

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Gradio](https://img.shields.io/badge/UI-Gradio-ff69b4.svg)](https://gradio.app/)
[![scikit-learn](https://img.shields.io/badge/Model-Scikit--Learn-orange.svg)](https://scikit-learn.org/)

## 📌 Project Overview
This project demonstrates the complete Machine Learning lifecycle, bridging the gap between model training and user interaction. It features a **Random Forest Classifier** trained to predict BMI categories (Underweight, Normal Weight, Obese) based on clinical biometrics, which is then deployed as a live, interactive web application using **Gradio**. 

This simulates a real-world medical decision-support tool where healthcare professionals can input patient metrics and receive instant model predictions and confidence scores.

## ⚙️ Pipeline Breakdown
1. **Synthetic Data Generation:** Simulated a clinical dataset of 1,000 patients with realistic height and weight distributions (Normal distributions with noise handling).
2. **Feature Engineering:** Calculated BMI using the standard mathematical formula and mapped continuous values to categorical risk labels.
3. **Exploratory Data Analysis (EDA):** Visualized biometric distributions and class balances using Matplotlib and Seaborn.
4. **Model Training:** Built and evaluated a Random Forest Classifier to learn the non-linear boundaries between BMI categories.
5. **Interactive UI Deployment:** Wrapped the trained model in a Gradio web interface, allowing real-time user inputs via sliders and text boxes.

## 📊 Visuals & Application
*(Note: Take a screenshot of your working Gradio app and your scatter plot, upload them to the `images/` folder, and replace these placeholder links!)*

**1. The Deployed Gradio Web App**
<img src="images/gradio_app_screenshot.png" width="600" alt="Gradio Interface Screenshot">
> *The interactive user interface allowing real-time inference without requiring coding knowledge from the end-user.*

**2. Biometric Feature Distributions**
<img src="images/bmi_distribution.png" width="600" alt="Height vs Weight Scatter Plot">
> *Exploratory Data Analysis showing the clear decision boundaries between BMI categories based on height and weight.*

## 🛠️ Technology Stack
* **Data Manipulation:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Random Forest, Train/Test Split, Metrics)
* **Web Deployment:** `gradio`
* **Visualization:** `matplotlib`, `seaborn`

## 💻 How to Run Locally
Clone the repository, install dependencies, and run the notebook to launch the local web server:
```bash
git clone [https://github.com/YourUsername/BMI-Prediction-Gradio-App.git](https://github.com/YourUsername/BMI-Prediction-Gradio-App.git)
cd BMI-Prediction-Gradio-App
pip install -r requirements.txt
