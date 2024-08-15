# NIFTY50 Prediction using ARIMA + LSTM

This repository contains a Google Colab notebook that combines ARIMA and LSTM models to predict the NIFTY 50 stock prices.

## Contents
- `NIFTY50_Prediction.ipynb`: The Google Colab notebook with the ARIMA + LSTM model.
- `NIFTY_50_Data.csv`: The dataset used for training and testing the model.

## How to Use

### Step 1: Clone the Repository
Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/NIFTY50-Prediction-ARIMA-LSTM.git
```

### Step 2: Upload the Files to Google Colab

1. Open Google Colab here.
2. Click on `File` > `Upload Notebook`.
3. Select the `NIFTY50_Prediction.ipynb` file from the cloned repository.
4. Upload the `NIFTY_50_Data.csv` file when it asks you once you start running the code.
    

### Step 3: Run the Notebook

1. Follow the instructions in the notebook .
2. Ensure that the ARIMA model is trained first, followed by the LSTM model.
3. The notebook will display the results, including the final predictions and the RMSE.

### Step 4: Experiment with number of parameters ( Optional)
1. You can try changing the number of layers or parameters in the model.
2. Additionally you can try changing batch size or early stopping condition to achieve better accuracy in model.
