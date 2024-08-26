# 🚦 Dynamic 3D Traffic Flow Visualization and Advanced Forecasting 🚀

This repository showcases a project focused on visualizing traffic flow in Los Angeles using 3D maps and improving traffic forecasting accuracy through advanced deep learning models.

## 🔥 Dynamic 3D Traffic Flow Visualization

Leveraging the **METR-LA dataset**—which records traffic flow at 207 locations in Los Angeles every five minutes for three months—this project creates dynamic 3D visualizations. Using **Pydeck** and tools like **Selenium** and **Imageio**, we transform static data into vivid videos, overcoming limitations in built-in animation and export features.

**Key Features:**
- **Dynamic 3D Visualization**: Integrates Pydeck’s Heatmap, Scatter, Grid, and Text layers to present a comprehensive view of traffic flow.
- **Visualization Tools**: Developed in Kaggle, this project highlights Pydeck’s data visualization capabilities.

### 🎥 Visualization Demo

[dataset_animation.gif]

## 🚦 Advanced Traffic Forecasting with Deep Learning

Building on the Spatio-Temporal Graph Convolutional Networks (STGCN) model, this project explores the use of alternative architectures to enhance traffic forecasting accuracy. We experimented with:

- (Bi)GRU
- (Bi)LSTM
- Attention-based (Bi)LSTM
- Attention-based (Bi)GRU
- Multi-Head Attention (MHA)
- MAMBA

**Key Results:**
- **Model Improvement**: Replacing the TCN with GRU in STGCN significantly reduced the Mean Absolute Error (MAE) from 3.33 to 3.26.
- **Visualization Tools**: Pydeck, Plotly, and Mapbox were used to visualize model predictions against actual data.

### 🎥 Experiment Report

[output_0411.gif]

## 🔗 Explore More

- **Public Kaggle Notebook**: [Link to the notebook](https://lnkd.in/eKx7Rw_N)
- **Original LinkedIn Post**: [Link to the post](https://lnkd.in/eZpUjYGj)
