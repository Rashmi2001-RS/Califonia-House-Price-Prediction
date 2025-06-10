# 🏡 California Housing Price Prediction using Deep Learning

This project uses a deep learning regression model to predict median housing prices in California based on features such as income, house age, rooms, population, and location.

## 📊 Dataset
- Source: Built-in dataset from `sklearn.datasets.fetch_california_housing`
- Contains 20,640 instances and 8 numerical features

## 🚀 Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- Matplotlib

## 🧠 Model Architecture
- Input: 8 features
- Hidden layers: Dense(64, relu) → Dense(32, relu)
- Output layer: Dense(1) for continuous value prediction

## 📈 Results
- R² Score: ~0.778
- MAE: ~0.36
- RMSE: ~0.54

## 📂 How to Run
1. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Open and run the notebook:
    ```bash
    jupyter notebook california_housing_model.ipynb
    ```

3. To save the trained model as `.h5`:
    ```python
    model.save("california_housing_model.h5")
    ```

## 📊 Visualizations
- Loss and MAE curves
- Actual vs. Predicted scatter plot

