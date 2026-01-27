## Objective

The objective of this project is to **predict land prices in Kozhikode** using real-world data by following a **systematic machine learning methodology**.

---

## Methodology

The project follows a structured machine learning workflow consisting of the following steps:

### 1. Load Data
Import and load the required datasets for analysis.

### 2. Data Preparation & Feature Engineering
Clean the raw data and transform it into meaningful features suitable for model training.

### 3. Split Training and Testing Sets
Divide the dataset into training and testing sets to create a reliable evaluation framework.

### 4. Model Training
Train a machine learning model using the prepared training data.

### 5. Performance Evaluation
Evaluate the model using appropriate metrics to measure prediction accuracy.

### 6. Results Visualization
Visualize predictions and performance metrics to interpret the model’s behavior and results.

---

## Project Structure

```
├── land_price_estimation.ipynb
├── data/
│ └── land_prices.csv
├── requirements.txt
└── README.md
```

---

## Technologies Used

- Python 3.13
- Jupyter Notebook
- Common Python libraries (NumPy, Pandas, Matplotlib, etc.)

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open the Jupyter Notebook and execute all cells in order:

```bash
jupyter notebook land_price_estimation.ipynb
```

Ensure that the dataset path is correct before running the notebook.

---

## Model Used

A **Random Forest Regressor** is used for predicting land price per cent.
Random Forest is chosen as it can handle non-linear relationships and complex feature interactions commonly found in real-world land price data.

---

## Evaluation Metrics

The model performance is evaluated using the following regression metrics:
- Mean Absolute Error (MAE) – Measures the average prediction error
- Root Mean Squared Error (RMSE) – Penalizes larger prediction errors

## Results Summary

The trained model achieves low MAE and RMSE values, indicating good
prediction accuracy. Visualization results show that predicted values
closely follow actual land price trends with no major systematic bias.

---

## Prediction on New Data

The project also demonstrates prediction on new, unseen land data.
New input samples are constructed using the same feature structure (one-hot encoded) as the training data to ensure compatibility with the trained model.

---

## Conclusion

This project demonstrates a complete machine learning pipeline for land price prediction, starting from data preparation and feature engineering to model training, evaluation, visualization, and real-world prediction.
The results show that Random Forest is a suitable model for estimating land prices in Kozhikode based on location and proximity features.