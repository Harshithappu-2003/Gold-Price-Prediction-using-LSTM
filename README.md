🔍 Problem Statement
--------------------

The objective is to predict future gold prices based on historical data to aid investors, analysts, and stakeholders in making informed financial decisions. This is especially useful in financial markets where gold prices fluctuate and predicting these movements can have substantial financial impacts.

📁 Dataset

The dataset used is a CSV file containing historical gold price data from 2013 to 2023. The data includes the date and gold price, which is the main variable of interest for this project.

🧠 Approach
-----------

1.  **Data Preprocessing**: Cleaned the data, normalized the gold prices using MinMaxScaler, and split the dataset into training and test sets.
    
2.  **LSTM Model**: Built and trained an LSTM model to predict future gold prices based on the historical data.
    
3.  **Model Evaluation**: Used the Mean Absolute Percentage Error (MAPE) metric to evaluate the performance of the LSTM model.
    

📈 Key Features
---------------

*   Time series analysis of gold prices from 2013-2023
    
*   LSTM-based forecasting model
    
*   Data visualization using Matplotlib and Plotly
    
*   Performance evaluation using MAPE
    

✅ Results
---------

*   **Test Accuracy**: 92.99% (using the MAPE metric)
    
*   The LSTM model provides predictions that can help forecast future trends in gold prices, with a high degree of accuracy.
    

📷 Screenshots
--------------
![image](https://github.com/user-attachments/assets/209e4d36-3506-4c78-99ee-b31c0c83cace)
![image](https://github.com/user-attachments/assets/684ad1b9-667f-4ae1-8e3d-af34666aaf2c)


📚 Learnings

*   Gained hands-on experience with LSTM networks for time series forecasting.
    
*   Learned how to preprocess data for LSTM models, including normalization and splitting datasets.
    
*   Gained insights into evaluating model performance using MAPE.
