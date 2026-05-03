ecommerce-sales-analytics-deep-learning
<br>
🔷 Project Title

Deep Learning-Based E-Commerce Revenue Prediction Using ANN, CNN, and LSTM Models
<br>
🔷 📖 Project Description

This project focuses on predicting e-commerce revenue using multiple deep learning techniques, including Artificial Neural Networks (ANN), Convolutional Neural Networks (CNN), and Long Short-Term Memory (LSTM) models.

The primary objective of this project is to analyze structured e-commerce sales data and evaluate the performance of different deep learning models in predicting revenue accurately. A comparative study is conducted to identify the most suitable model for this dataset.
<br>
🔷 📊 Dataset Overview
Dataset: E-commerce Sales Analytics (5000 records)
Type: Structured (Tabular Data)
Contains features related to sales performance, customer activity, and transactions
Target Variable: Revenue
<br>
🔷 ⚙️ Workflow / Methodology
1. Data Preprocessing
Removed irrelevant columns
Handled missing values (if any)
Separated features (X) and target variable (y)
Applied train-test split (80:20)
Performed feature scaling using StandardScaler
<br>
3. Model Implementation
🔹 Artificial Neural Network (ANN)
Fully connected dense layers
Activation: ReLU
Optimizer: Adam
Loss Function: Mean Squared Error
<br>
👉 Best suited for structured/tabular data
<br>
🔹 Convolutional Neural Network (CNN)
1D Convolution layers applied on reshaped data
Extracts local feature patterns
<br>
👉 More effective for spatial data, less optimal for tabular data
<br>
🔹 Long Short-Term Memory (LSTM)
Sequential deep learning model
Captures temporal dependencies
<br>
👉 Best for time-series data
<br>
3. Model Evaluation

Each model is evaluated using:
<br>
Mean Absolute Error (MAE)
Loss curves (training vs validation)
Actual vs Predicted scatter plots
<br>
🔷 📈 Results & Analysis
ANN achieved the best performance with the lowest prediction error
CNN showed moderate performance due to lack of spatial structure in data
LSTM underperformed because the dataset does not contain strong sequential patterns
<br>
📊 Graph Insights
Loss curves show ANN converges faster and more smoothly
Prediction plots show ANN outputs are closest to actual values
<br>
🔷 🧠 Key Findings
ANN is the most suitable model for tabular e-commerce data
CNN and LSTM are powerful but not ideal for this dataset type
Model selection should depend on data structure, not complexity
<br>
🔷 ✅ Conclusion

This project demonstrates that Artificial Neural Networks outperform CNN and LSTM models for structured revenue prediction tasks. Proper understanding of dataset characteristics is crucial for selecting the right deep learning model.
<br>
🔷 🛠️ Technologies Used
Python
TensorFlow / Keras
NumPy & Pandas
Matplotlib & Seaborn
Scikit-learn
<br>
🔷 📌 Future Improvements
Hyperparameter tuning
Feature engineering
Trying advanced models (XGBoost, Transformer-based models)
Deploying model using Flask/Streamlit
<br>
🔷 📎 Project Structure
├── dataset/
├── notebook.ipynb
├── models/
├── graphs/
├── ppt/
└── README.md
