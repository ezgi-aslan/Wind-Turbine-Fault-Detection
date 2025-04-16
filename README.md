# Wind Turbine Fault Detection

This machine learning-based fault detection system analyzes SCADA data from wind turbines to identify operational anomalies and predict potential failures. The system implements three distinct modeling approaches:

* Random Forest Classifier
* Gradient Boosted Trees (GBT)
* Long Short-Term Memory (LSTM) Network

The project leverages PySpark for large-scale data processing and TensorFlow/Keras for deep learning implementation, achieving high accuracy in fault prediction while maintaining scalability for industrial applications.  

This work was completed as a term project for **Big Data Analytics** course at Istanbul Technical University.

## Key Features
**Scalable Data Processing**: Handles 3.14GB of high-dimensional SCADA data (957 features) using PySpark

**Hybrid Architecture**: Combines Spark ML for feature processing with deep learning for temporal analysis

**Real-time Capabilities**: Includes streaming prediction implementation

**Comprehensive Evaluation**: Compares tree-based and sequential models using multiple metrics

**Dimensionality Reduction**: PCA implementation for feature space optimization



## Project Pipeline Overview

1. **Data Collection**  
   - Source: SCADA data from wind turbines () 
   - Collected metrics: Wind Speed, Rotor Speed, Gear Oil Temperature, Power Output, and more.

2. **Preprocessing & Feature Engineering**
   - Null and constant feature removal
   - Feature correlation analysis
   - One-hot encoding and normalization

3. **Model Training & Evaluation**
   - Implemented Models:
     - Random Forest Classifier (PySpark MLlib)
     - Gradient Boosted Trees Classifier (PySpark MLlib)
     - LSTM (via PySpark → Pandas → TensorFlow)
   - Evaluation Metrics:
     - Accuracy, Precision, Recall, F1 Score
     - Confusion Matrix
     - ROC-AUC (for binary classification)

4. **Tools & Technologies**
   - Apache Spark (PySpark)
   - Spark MLlib
   - Pandas, NumPy, Scikit-learn, TensorFlow/Keras


## Contributors

- Beyza Nur Bozkurt
- Zeynep Begüm Baş  
- Ezgi Aslan  
  


