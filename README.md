IPL Score Prediction using Deep Learning

This project predicts the final innings score of an IPL match using a neural network trained on ball-by-ball data.
It combines sports analytics, feature engineering, and deep learning to estimate how many runs a team will score by the end of the innings.
---------------------------------------------------------------------------

Features

-Clean and modern data visualizations
-Top batsmen and bowlers performance analysis
-Label encoding and feature scaling
-Deep learning model using TensorFlow/Keras
-Metrics: MAE, MSE, and loss curves
-Optimized neural network architecture with Batch Normalization and Dropout

---------------------------------------------------------------------------


Project Structure
IPL-Score-Prediction/
│
├── data/
│   └── ipl_data.csv
│
├── notebooks/
│   └── IPL_Score_Prediction_using_Deep_Learning.ipynb
│
├── visuals/
│   └── Matches Played at Each Venue.png
│   └── Top 10 Batsmen by Total Runs.png
│   └── Top 10 Bowlers by Total Wickets.png
│   └── Top Bowlers: Wickets vs Economy.png
│   └── Feature Correlation Heatmap.png
│   └── loss.png
│
├── requirements.txt
│
└── README.md

---------------------------------------------------------------------------

Installation

pip install -r requirements.txt
Running the Project
Open the notebook:
notebooks/IPL_Score_Prediction_using_Deep_Learning.ipynb
Run all cells to:

-Clean and explore the IPL dataset
-Visualize player and team performance
-Train the deep learning model
-View MAE, MSE, and loss curves
-Generate visualizations (saved in the visuals/ directory)

This repository currently includes the full analysis and training workflow inside a single notebook.
A separate prediction interface or deployment is not included.

---------------------------------------------------------------------------

Visualizations Included

-Feature correlation heatmap
-Top 10 batsmen by total runs
-Top 10 bowlers by total wickets
-Wickets vs economy for bowlers
-Matches played per venue
-Training/validation loss curves


---------------------------------------------------------------------------

Future Improvements

-Predict win/loss probabilities
-Include player form trends across seasons
-Upgrade the model to LSTM or Transformer-based architecture
-Build a Streamlit or Flask web app for real-time score prediction
