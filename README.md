# Stock-Price-Prediction-LSTM
This project implements a LSTM hybrid model for time series forecasting to predict stock prices. The model leverages LSTM for sequential learning, making it more effective for analyzing stock trends and understanding about the market better.

Dataset :
Used Tesla stock price dataset(tesla-stock-price.csv).
Data sourced from Kaggle.

Model Overview :
Preprocessing: Min-Max Scaling for normalization.

Architecture:
CNN Layer: Extracts spatial features.
LSTM Layer: Captures sequential patterns.
Dense Layers: Outputs the final stock price predictions.
Loss Function: Mean Squared Error (MSE).

Optimizer: Adam.

Results:
Below is the comparison of actual vs. predicted stock prices:

![image](https://github.com/user-attachments/assets/6ca1ad0e-562d-4f2b-939d-5f6364168336)


How to Run:
Clone the repository:
git clone https://github.com/Rajesh-M01/Stock-Price-Prediction-CNN-LSTM.git

cd Stock-Price-Prediction-CNN-LSTM
pip install tensorflow pandas numpy scikit-learn matplotlib  

Run the Jupyter Notebook (CNN-LSTM Time Series Forecasting.ipynb) in Google Colab or locally.

Libraries Used
TensorFlow
Keras
NumPy
Pandas
Matplotlib
Scikit-learn

Key Learnings
How to use LSTM for time series forecasting.
Importance of scaling data before feeding into LSTMs.
How to visualize model predictions for stock prices.

🚀 Connect with Me
If you liked this project, feel free to ⭐ the repository and connect with me on https://www.linkedin.com/in/rajesh-m-a42539317/! 🚀





