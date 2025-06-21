# Water_Quality_Prediction
Water quality prediction plays a vital role in ensuring public health and managing water resources efficiently. By leveraging data science and machine learning, we can build predictive models that analyze various water quality parameters and forecast whether water is safe for consumption or usage. Jupyter Notebook provides an ideal interactive environment for this task, combining code, data visualization, and documentation in a single place.

## Overview

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can help in early detection of pollution and ensure timely intervention.

In this project, we:

- Collected and preprocessed real-world water quality datasets
- Used supervised machine learning for multi-target regression
- Built a pipeline using MultiOutputRegressor with RandomForestRegressor
- Evaluated the model using appropriate regression metrics

## Technologies Used

- *Python 3.12*
- *Pandas, NumPy* – Data handling
- *Scikit-learn* – Machine learning model and evaluation
- *Matplotlib, Seaborn* – Data visualization
- *Jupyter Notebook* – Interactive experimentation


## Predicted Water Quality Parameters

The model predicts multiple water quality parameters such as:

- NH4
- BOD5 (BSK5)
- Colloids
- O2, NO3, NO2, SO4, PO4 and 
- CL

## Model Performance

The model was evaluated using:

- *R² Score*
- *Mean Squared Error (MSE)*

Performance was acceptable across all parameters

