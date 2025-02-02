# Crew AI Project: Gym Workout Prediction with Machine Learning

Welcome to the **Crew AI Project** repository! This project leverages **machine learning** techniques to predict and recommend gym workout types based on user input data such as age, weight, height, heart rate, workout frequency, and more.

## 📝 Project Description

This project aims to predict the best workout type for an individual using machine learning algorithms. The model takes in various features like:

- **Age**
- **Gender**
- **Weight (kg)**
- **Height (m)**
- **Max BPM** (Maximum heart rate)
- **Resting BPM** (Resting heart rate)
- **Session Duration (hours)**
- **Calories Burned**
- **Fat Percentage**
- **Water Intake (liters)**
- **Workout Frequency (days/week)**
- **Experience Level**
- **BMI** (Body Mass Index)

The model classifies these features to predict a personalized workout type, such as:

- **Yoga**
- **HIIT**
- **Cardio**
- **Strength**

## 📚 Dataset

The dataset contains **973 records** with the above features. The data is preprocessed using scaling and encoding to prepare it for machine learning. We also handle missing data and perform feature engineering as part of the preprocessing pipeline.

### Features:
- **Age**: User’s age
- **Gender**: User’s gender (encoded to numerical values)
- **Weight (kg)**: User's weight
- **Height (m)**: User's height
- **Max BPM**: Maximum heart rate during the workout
- **Avg BPM**: Average heart rate during the workout
- **Resting BPM**: Resting heart rate
- **Session Duration (hours)**: Duration of the workout
- **Calories Burned**: Calories burned during the workout
- **Fat Percentage**: Percentage of body fat
- **Water Intake (liters)**: Water intake during the workout
- **Workout Frequency (days/week)**: Frequency of workout in a week
- **Experience Level**: User’s experience level (Beginner, Intermediate, Advanced)
- **BMI**: Body Mass Index

## 💡 Key Features

- **Machine Learning Model**: A neural network model is used to predict workout types based on user input features.
- **Data Preprocessing**: The data undergoes preprocessing steps like handling missing values, encoding categorical variables (like gender and workout type), scaling numerical features, and splitting the dataset into training and testing sets.
- **Model Evaluation**: The model's performance is evaluated using various classification metrics, including accuracy, precision, recall, and F1-score.
- **Streamlit Application**: A web application built with Streamlit allows users to input their data and get personalized workout recommendations from the trained model.

## ⚙️ Installation

To run this project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/crew-ai-project.git
cd crew-ai-project
