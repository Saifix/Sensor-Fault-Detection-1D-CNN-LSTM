# LSTM and CNN Merged Model for Fault Detection in Tennessee Eastman Process Simulation Dataset

## Introduction

This project aims to develop a hybrid model combining LSTM (Long Short-Term Memory) and CNN (Convolutional Neural Network) architectures for fault detection in the Tennessee Eastman Process Simulation dataset. The model utilizes both temporal and spatial information for improved fault classification performance.

### Steps Taken 🚀

1. **Importing Libraries**: Essential libraries including PyReadr for reading RData files, Matplotlib for visualization, Seaborn for statistical graphics, NumPy, Pandas for data manipulation, and Keras for building deep learning models were imported.
2. **Importing Dataset**: Fault-free and faulty training datasets were located and imported. PyReadr was used to read RData files, and Pandas for data manipulation.
3. **Preprocessing Dataset**: Data preprocessing involved filtering, scaling, and encoding categorical variables using StandardScaler and OneHotEncoder from scikit-learn. Sliding window technique was applied for sequence data preparation.
4. **Preparing Merged Model**: A merged model was constructed with branches for LSTM and CNN architectures, followed by a concatenation layer and dense layers for classification.
5. **Training Model**: The merged model was trained on the preprocessed data with early stopping to prevent overfitting.
6. **Evaluating the Model**: The model's performance was evaluated using confusion matrices and accuracy scores.

## Results

- **Training Performance**: The training history depicted decreasing loss and increasing accuracy over epochs, indicating effective learning with some fluctuations.
- **Evaluation Metrics**: The confusion matrix revealed the model's ability to accurately predict fault classes, with an overall accuracy score computed.
- **Real-time Fault Prediction**: Visualization of the model's predictions for real-time fault detection demonstrated its capability to identify fault classes over time.
- **Overall Accuracy**: The overall accuracy of the model was calculated as 0.9178, indicating high performance across fault classes.

## Conclusion

This project demonstrates the effectiveness of a merged LSTM and CNN model for fault detection in industrial processes using the Tennessee Eastman Process Simulation dataset. By leveraging both temporal and spatial information, the model achieves high accuracy in classifying fault instances, showcasing its potential for real-world application in process monitoring and control systems.
