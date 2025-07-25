# Gas Sensor Data Analysis & Classification using Machine Learning

This project focuses on analyzing sensor data collected from a gas sensor array exposed to **seven different gas mixtures** and building a machine learning model to predict the type of gas mixture based on sensor readings. This kind of work is essential in environmental monitoring, industrial safety, and smart sensor applications.


## Dataset Description

The dataset contains sensor readings for the following **7 gas mixtures**:

- MA (Methylamine)
- NH₃ (Ammonia)
- DMA (Dimethylamine)
- TEA (Triethylamine)
- TEA + NH₃
- TEA + MA
- TEA + DMA

Each sample includes:
- Sensor readings from multiple sensors
- Label indicating the gas mixture


## Project Objectives

- Perform exploratory data analysis (EDA) on gas sensor data
- Preprocess the dataset (handle nulls, encode labels, normalize features)
- Visualize sensor response patterns
- Train classification models to accurately **predict the gas mixture**
- Evaluate model performance using metrics like accuracy, precision, recall


## Tools & Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (SVM, Random Forest, Train-test split, accuracy score)
- Jupyter Notebook

## Machine Learning Approach

- **Data Preprocessing:**
  - Label encoding for gas names
  - Feature scaling using MinMaxScaler
- **Modeling:**
  - Random Forest Classifier
  - Support Vector Machine (SVM)
- **Evaluation:**
  - Confusion Matrix
  - Accuracy Score
  - Visualizations of predictions


## Results Summary

- The trained classification model can successfully distinguish between all 7 gas mixtures with high accuracy.
- Random Forest performed slightly better than SVM for this dataset.

