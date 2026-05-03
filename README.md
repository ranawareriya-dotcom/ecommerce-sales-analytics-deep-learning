ECOMMERCE-SALES-ANALYTICS-DEEP-LEARNING
<br>
🔷 Project Title:
<BR>
Deep Learning-Based E-Commerce Revenue Prediction Using ANN, CNN, and LSTM Models
<br>
<br>
🔷 📖 Project Description

This project focuses on predicting e-commerce revenue using multiple deep learning techniques, including Artificial Neural Networks (ANN), Convolutional Neural Networks (CNN), and Long Short-Term Memory (LSTM) models.

 The primary objective of this project is to analyze structured e-commerce sales data and evaluate the performance of different deep learning models in predicting revenue accurately. A comparative study is conducted to identify the most suitable model for this dataset.
<br>
<br>
🔷 📊 Dataset Overview
<br>
*Dataset: E-commerce Sales Analytics (5000 records)
<br>
*Type: Structured (Tabular Data)
<br>
*Contains features related to sales performance, customer activity, and transactions
<br>
*Target Variable: Revenue
<br>
<br>
🔷 ⚙️ Workflow / Methodology
<br>
1. Data Preprocessing
<br>
 *Removed irrelevant columns
<br>
 *Handled missing values (if any)
<br>
 *Separated features (X) and target variable (y)
<br>
 *Applied train-test split (80:20)
<br>
 *Performed feature scaling using StandardScaler
<br>
<br>
2.  Model Implementation
<br>
🔹 Artificial Neural Network (ANN)
<br>
*Fully connected dense layers
<br>
*Activation: ReLU
<br>
*Optimizer: Adam
<br>
*Loss Function: Mean Squared Error
<br>
👉 Best suited for structured/tabular data
<br>
<br>
🔹 Convolutional Neural Network (CNN)
<br>
*1D Convolution layers applied on reshaped data
<br>
*Extracts local feature patterns
<br>
👉 More effective for spatial data, less optimal for tabular data
<br>
<br>
🔹 Long Short-Term Memory (LSTM)
<br>
*Sequential deep learning model
<br>
*Captures temporal dependencies
<br>
👉 Best for time-series data
<br>
<br>
4. Model Evaluation
<br>
*Each model is evaluated using:
<br>
*Mean Absolute Error (MAE)
<br>
*Loss curves (training vs validation)
<br>
*Actual vs Predicted scatter plots
<br>
<br>
🔷 📈 Results & Analysis
<br>
*ANN achieved the best performance with the lowest prediction error
<br>
*CNN showed moderate performance due to lack of spatial structure in data
<br>
*LSTM underperformed because the dataset does not contain strong sequential patterns
<br>
<br>
📊 Graph Insights
<br>
*Loss curves show ANN converges faster and more smoothly
<br>
*Prediction plots show ANN outputs are closest to actual values
<br>
<br>
🔷 Key Findings
<br>
*ANN is the most suitable model for tabular e-commerce data
<br>
*CNN and LSTM are powerful but not ideal for this dataset type
<br>
*Model selection should depend on data structure, not complexity
<br>
<br>
🔷 ✅ Conclusion
<br>

This project demonstrates that Artificial Neural Networks outperform CNN and LSTM models for structured revenue prediction tasks. Proper understanding of dataset characteristics is crucial for selecting the right deep learning model.
<br>
<br>
🔷 🛠️ Technologies Used
<br>
*Python
<br>
*TensorFlow / Keras
<br>
*NumPy & Pandas
<br>
*Matplotlib & Seaborn
<br>
*Scikit-learn
<br>
<br>
🔷 📌 Future Improvements
<br>
*Hyperparameter tuning
<br>
*Feature engineering
<br>
*Trying advanced models (XGBoost, Transformer-based models)
<br>
*Deploying model using Flask/Streamlit
<br>
<br>
🔷 📎 Project Structure
<br>
├── dataset/
<br>
├── notebook.ipynb
<br>
├── models/
<br>
├── graphs/
<br>
├── ppt/
<br>
└── README.md
