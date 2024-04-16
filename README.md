# Stock Price Prediction using LSTM Model

## Overview
This project aims to predict stock prices using historical data spanning 20 years. We utilize a Long Short-Term Memory (LSTM) model, a type of recurrent neural network (RNN) well-suited for sequence prediction tasks like time series forecasting.

## Dataset
The dataset consists of historical stock price data for 20 different stocks, spanning a period of 20 years. Each stock's data includes daily opening, closing, high, low prices, as well as volume traded. The dataset is preprocessed to handle missing values, normalize features, and split into training and testing sets.

## Pipeline
1. **Data Preprocessing**: Cleanse and preprocess the raw data. This involves handling missing values, normalizing features, and splitting the dataset into training and testing sets.
2. **Model Training**: Build and train an LSTM model using the training data. LSTM is chosen for its ability to capture temporal dependencies in sequential data.
3. **Model Evaluation**: Evaluate the trained model's performance using the testing data. Metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) are used to assess prediction accuracy.
4. **Prediction**: Deploy the trained model to make predictions on unseen data, i.e., future stock prices.

## Usage
1. Clone the repository:



2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the pipeline:



4. View results:
- Trained model: Check the `models/` directory for the saved LSTM model.
- Evaluation metrics: View the evaluation results printed during pipeline execution.
- Predictions: Predicted stock prices can be found in the output or saved to a file specified in the pipeline.

## Directory Structure
- `data/`: Yfinance
- `models/`: Stores trained LSTM model(s).
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `README.md`: Project overview, setup instructions, and usage guide.
- `requirements.txt`: List of Python dependencies required to run the project.

## Contributors

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
