 IPL Score Prediction using Deep Learning

Predict the final innings score of an IPL match in real time using a neural network trained on ball-by-ball data.
This project blends sports analytics, feature engineering, and deep learning to estimate how many runs a team will score by the end of the innings.

Features

-Clean and modern data visualizations
-Top batsmen & bowlers performance analysis
-Feature engineering with label encoding + scaling
-Deep learning model using TensorFlow/Keras
-Training metrics: MAE, MSE, Loss curves
-Interactive score predictor (Jupyter Widgets)
-Optimized architecture: BatchNorm + Dropout

Reproducible project structure
------------------------------------------------------------

Project Structure
IPL-Score-Prediction/
│
├── data/
│   └── cleaned_ipl_data.csv
│
├── models/
│   └── final_model.h5          # Saved Keras model (create using model.save())
│
├── notebooks/
│   └── analysis.ipynb
│   └── model_training.ipynb
│
├── visuals/
│   └── heatmap.png
│   └── batsmen_stats.png
│   └── bowlers_stats.png
│
├── app/
│   └── score_predictor.ipynb
│
├── requirements.txt
└── README.md
-----------------------------------------------------------

 Installation
pip install -r requirements.txt

Running the Project
Train the Model

Open notebooks/model_training.ipynb

Run all cells.

Use the Interactive Predictor

Open:

app/score_predictor.ipynb


Choose batsman, bowler, overs, wickets, etc…
The model predicts the final score instantly.
------------------------------------------------------------

Visualizations Included

Feature correlation heatmap

Top 10 batsmen by total runs

Top 10 bowlers by wickets

Loss curve (train vs validation)

Error metrics (MAE, MSE)
--------------------------------------------------------------

Future Improvements

Predict probability of win/loss

Add player form trends across seasons

Use LSTM or Transformers for time-series modelling

Make a Streamlit/Flask web app