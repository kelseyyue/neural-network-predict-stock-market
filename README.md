# neural-network-predict-stock-market

# **Stock Price Prediction Using Machine Learning and Deep Learning**

## **Overview**  
This project focuses on predicting stock prices using machine learning and deep learning techniques. It implements and compares fully connected neural networks and LSTM models to analyze and forecast time-series stock data.

## **Key Features**  
- **Data Preprocessing**:  
  - Utilized `Pandas` and `MinMaxScaler` for data normalization and feature scaling to ensure stability during model training.  

- **Model Architectures**:  
  - **Fully Connected Neural Network**: Built with TensorFlow, featuring multiple hidden layers to capture complex relationships.  
  - **LSTM (Long Short-Term Memory)**: Implemented with Keras to model temporal dependencies and improve forecasting accuracy.  

- **Performance Metrics**:  
  - Achieved a minimum Mean Squared Error (MSE) of **0.0012** on the test dataset.  
  - Visualized actual vs. predicted values to compare model performance and highlight prediction trends.

- **Visualization**:  
  - Used Matplotlib to plot actual and predicted stock prices, providing clear insights into model accuracy.  

## **Technologies Used**  
- **Languages**: Python  
- **Libraries**: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Scikit-learn  

## **Results**  
- The LSTM model outperformed the fully connected neural network in terms of predictive accuracy, demonstrating its capability to handle time-series data effectively.  
- Visual comparison of predictions and actual prices shows the robustness of the trained models.

## **Future Work**  
- Incorporate more advanced architectures such as Transformer models or hybrid approaches.  
- Expand the dataset with additional features to improve model generalization.  
- Experiment with other optimization techniques to further minimize loss values.

---


