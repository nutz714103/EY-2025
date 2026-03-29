Urban Heat Island (UHI) Index Prediction

This project implements a machine learning pipeline to analyze and predict the Urban Heat Island (UHI) Index using multi-source geospatial data. By integrating satellite imagery (Sentinel) and meteorological data, the model aims to quantify temperature variations in urban environments compared to their rural surroundings.
Project Overview

The repository features a comprehensive workflow for geospatial data science:

    Data Acquisition: Automated extraction of satellite imagery and environmental data via the Microsoft Planetary Computer API.

    Geospatial Processing: Advanced handling of raster and vector data using libraries like rioxarray, rasterio, and geopandas.

    Modeling: Implementation of multiple regression architectures, including Random Forest, XGBoost, LightGBM, and deep learning approaches like CNN-LSTM using TensorFlow/Keras.

    Interpretability: Model explainability through SHAP (SHapley Additive exPlanations) values to identify the key environmental drivers of urban heat.

Tech Stack

    Languages: Python

    Libraries: TensorFlow, XGBoost, LightGBM, SHAP, Planetary Computer, GeoPandas, Xarray.

    Platform: Developed and tested on Google Colab with Google Drive integration for large-scale training data management.

Key Features

    Multi-Modal Integration: Combines Sentinel spectral bands with weather data for high-fidelity predictions.

    Hyperparameter Tuning: Utilizes GridSearchCV and RandomizedSearchCV for model optimization.

    Submission Ready: Includes logic for generating predictions in standard CSV formats for benchmarking.
