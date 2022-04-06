# Exploratory Data Analysis and PCA of Scania Truck APS System Dataset

In this project I perform data preparation and analysis of data collected from Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurized air that are utilized in various functions in a truck, such as braking and gear changes. The dataset’s  positive class consists of component failures for a specific component of the APS system.

The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts. The goal of this analysis is to demonstrate dimensionality reduction and feature extraction techniques, establish the minimum number of features needed for retaining 99.5% variance in the data, and implement PCA to dimensionally reduce the data to the minimum number of features required. 

The data for this project was sourced from the UCI Machine Learning Repository - https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks
