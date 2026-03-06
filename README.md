# NASA Turbofan Engine Predictive Maintenance

This project predicts the **Remaining Useful Life (RUL)** of aircraft turbofan engines using a **Deep Learning LSTM model** trained on the NASA Turbofan Engine Degradation Dataset.

The goal is to build a **predictive maintenance system** that estimates how many cycles an engine can run before failure.

---

## Model Performance

The trained LSTM model achieved the following performance:

⭐ **Root Mean Squared Error (RMSE): 15.9**

This means the model's prediction error is approximately **±16 cycles**, which is a strong result for turbofan engine degradation prediction.

---

## Dataset

Dataset used: **NASA Turbofan Engine Degradation Simulation Dataset**

Features included:

- Engine ID
- Cycle number
- 3 operational settings
- 21 sensor measurements

Dataset Source:
https://www.kaggle.com/datasets/behrad3d/nasa-cmaps

---

## Technologies Used

- Python
- TensorFlow / Keras
- LSTM Neural Network
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Model Architecture

The project uses an **LSTM (Long Short-Term Memory) network** for time-series prediction.

Input to the model:

- Time window: **50 cycles**
- Features: **17 selected sensors and operational settings**
