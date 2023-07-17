# Bitcoin-Price-Prediction-using-LSTM-and-Technical-Indicators

Description:
This project focuses on predicting the future price movement of Bitcoin using LSTM (Long Short-Term Memory) neural networks and technical indicators. The project leverages historical price data of Bitcoin, obtained from Yahoo Finance using the yfinance library, to train and evaluate the LSTM model. Additionally, various technical indicators such as RSI (Relative Strength Index) and EMAs (Exponential Moving Averages) are calculated and incorporated as features for improved prediction accuracy.

The project follows the following steps:
• Data Collection: Historical price data of Bitcoin is collected from Yahoo Finance using the yfinance library.

• Data Preprocessing: The collected data is preprocessed and cleaned. Technical indicators such as RSI, EMAs, and target variables are calculated.

• Feature Scaling: MinMaxScaler is applied to scale the data features in the range of 0 to 1.

• Data Preparation: The preprocessed data is transformed into a suitable format for input into the LSTM model. A rolling window approach is used to create input sequences and corresponding target variables.

• Model Development: An LSTM model is constructed using Keras with TensorFlow as the backend. The model architecture includes an LSTM layer, a dense layer, and an output layer.

• Model Training: The LSTM model is trained on the training dataset, with a specified number of epochs and batch size. Adam optimizer is used for optimization.

• Model Evaluation: The trained model is evaluated on the test dataset, and the predicted Bitcoin prices are compared with the actual prices.

• Visualization: The predicted and actual prices are plotted using matplotlib for visual comparison.

The project utilizes Python libraries such as pandas, numpy, matplotlib, yfinance, pandas_ta, and keras for data manipulation, visualization, and model implementation. The code is organized into sections and well-commented for clarity and ease of understanding.

By leveraging LSTM and technical indicators, this project aims to provide insights into Bitcoin price movements, enabling users to make informed decisions in the cryptocurrency market.
