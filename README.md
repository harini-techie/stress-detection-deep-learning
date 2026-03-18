# 🧠 Stress Detection in Workplaces using Deep Learning

## 📌 Overview

This project implements a deep learning-based approach to detect stress levels using multiple Recurrent Neural Network (RNN) architectures.

The models used include:

* GRU
* DeepGRU
* LSTM
* DeepLSTM

## ⚙️ Features

* Automatic feature selection
* Categorical encoding using OneHotEncoder
* Data normalization using StandardScaler
* Model training with EarlyStopping and ReduceLROnPlateau
* Performance evaluation using:

  * MSE
  * MAE
  * RMSE
  * R² Score
* Visualization of Actual vs Predicted values

## 📊 Dataset

* Input file: `Dataset for human.xlsx`
* Supports automatic target detection
* Handles missing values

## 🧠 Models Implemented

| Model    | Description       |
| -------- | ----------------- |
| GRU      | Basic GRU model   |
| DeepGRU  | Multi-layer GRU   |
| LSTM     | Standard LSTM     |
| DeepLSTM | Deep stacked LSTM |

## 🚀 How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the script:

```
python src/train_models.py
```

Or open the notebook in Jupyter/Colab.

## 📈 Output

* Model performance metrics
* Comparison table
* Graphs of predictions vs actual values

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

## 📌 Future Improvements

* Add CNN-LSTM hybrid models
* Hyperparameter tuning
* Real-time stress detection

