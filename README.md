### 🚀 Key Projects

#### **Predicting Stock Prices Using 60 Days of Closing Prices**
- **Description**: Developed a machine learning model to predict stock prices based on the last 60 days' closing prices. The project utilizes historical data to forecast future prices, aiding investors in making informed decisions.
  
- **Technologies Used**:
  - **Python**: Core programming language used for data analysis, model building, and prediction.
  - **Pandas**: Managed and manipulated the time-series data.
  - **NumPy**: Utilized for numerical operations and efficient data handling.
  - **Scikit-Learn**: Used MinMaxScaler for feature scaling to normalize the dataset.
  - **Keras & TensorFlow**: Employed LSTM (Long Short-Term Memory) neural networks to model the sequential data.
  - **Matplotlib**: Visualized the training results and model predictions.

- **Key Steps**:
  1. **Data Preprocessing**: 
     - Imported the stock data and filtered to keep only the 'Close' price.
     - Normalized the data using MinMaxScaler to scale values between 0 and 1.
     - Split the data into training (80%) and testing (20%) sets while preserving the sequence.
     - Created sequences of 60 days of closing prices to predict the 61st day.

  2. **Model Development**:
     - Built an LSTM model with 2 LSTM layers (100 and 50 neurons) and Dense layers.
     - Trained the model on the training dataset over 10 epochs.
  
  3. **Evaluation**:
     - Evaluated the model's performance on the test dataset using RMSE (Root Mean Square Error).
     - Visualized the model's predictions against the actual closing prices.

- **Outcome**: The model achieved a Root Mean Square Error (RMSE) of `X` (replace with your result), indicating its accuracy in predicting stock prices. The predictions closely followed the actual closing prices, demonstrating the model's effectiveness in financial forecasting.

- **Visualization**:
  ![Model Performance](.png) 

- **Repository Link**: [Predicting Stock Prices](#) (Add your repository link here)
