# doctor-engagement-prediction
This project predicts doctor engagement levels to optimize survey targeting. Using machine learning, it identifies the best time and doctors to send surveys based on login patterns, region, and specialty. The model is deployed with Gradio for easy user interaction.

Features

Predicts doctor engagement probability.

Uses Gradient Boosting Classifier for predictions.

Allows users to input a time and receive the top engaged doctors.

Deployed with Gradio for a user-friendly interface.


How It Works

The dataset is preprocessed to extract login hours and encode categorical variables.

A Gradient Boosting Classifier is trained to predict engagement levels.

Users enter a time (HH:MM), and the model suggests the top doctors to target.

The results are displayed and available for download in XLXS format.

Python

Pandas & NumPy (Data processing)

Scikit-learn (Machine Learning)

Gradio (Web UI)

