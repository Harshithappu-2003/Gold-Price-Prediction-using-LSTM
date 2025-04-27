🔍 Problem Statement
--------------------

Forecasting weather conditions accurately is critical for agriculture, aviation, disaster management, and daily life planning. This project aims to develop an RNN-based model to predict the next day's weather type based on historical weather metrics like temperature, wind speed, and precipitation.

🧠 Approach
-----------

1.  **Data Cleaning**: Checked for missing and duplicate values — none found.
    
2.  **Preprocessing**:
    
    *   Normalized continuous features (precipitation, temp\_max, temp\_min, wind).
        
    *   Encoded categorical target (weather) using Label Encoding.
        
3.  **Model Building**:
    
    *   Constructed an RNN model using Keras Sequential API.
        
    *   Input shape designed for sequential time-series data.
        
    *   Output layer uses Softmax for multi-class classification.
        
4.  **Model Training**:
    
    *   Split data into training and testing sets.
        
    *   Trained RNN with appropriate batch size and epochs.
        
5.  **Model Evaluation**:
    
    *   Measured accuracy on test data.
        
    *   Plotted training vs validation loss.
        

📈 Key Features
---------------

*   Built an RNN model for sequence-based classification.
    
*   Handled time-series data effectively.
    
*   Achieved significant accuracy in multi-class weather prediction.
    
*   Visualized loss trends to ensure model generalization.
    

✅ Results
---------

*   **Test Accuracy**: ~91.23%
    
*   Successfully predicted weather types like drizzle, rain, sunny, etc., based on past climatic features with over 90% test set accuracy.
    

📷 Screenshots
--------------
![image](https://github.com/user-attachments/assets/209e4d36-3506-4c78-99ee-b31c0c83cace)
![image](https://github.com/user-attachments/assets/684ad1b9-667f-4ae1-8e3d-af34666aaf2c)


📚 Learnings
------------

*   Understood time-series preprocessing for RNNs.
    
*   Gained experience building and tuning RNN models in TensorFlow/Keras.
    
*   Learned how weather prediction involves sequential pattern recognition.
    
*   Improved skills in feature scaling, label encoding, and sequence modeling.
