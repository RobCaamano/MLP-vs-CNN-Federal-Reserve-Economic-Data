# Predictive Modeling using Federal Reserve Economic Data (FRED)

## Sections

- [About](#about)
- [Multilayer Perceptron](#mlp)
- [Convolutional Neural Network](#cnn)
- [Model Comparison](#comparison)

## About <a id="about"></a>

This Predictive Modeling project focuses on time series prediction of Retail Sales in the United States. 
Utilizing data from the Federal Reserve Economic Data (FRED), I implemented both Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN) architectures to forecast retail sales trends.

- **Time Series Analysis:** The training and testing datasets are transformed into a time series format suitable for model training and evaluation.

- **MLP and CNN Models:** Two predictive models are developed using MLP and CNN architectures. These models are trained and evaluated to determine their effectiveness in forecasting retail sales.

- **Visualizations:** The project includes two plots for each model:

  - Plot 1: Displays the complete history, real data, and predicted values, providing a comprehensive view of the model’s performance over the entire dataset.

  - Plot 2: Focuses on the actual data and predicted values, offering a closer look at the model's accuracy in forecasting recent trends.

- **Model Comparison:** At the conclusion of the project, the performance of the MLP and CNN models is compared, highlighting their strengths and weaknesses.

## Multilayer Perceptron Implementation <a id="mlp"></a>

### Hyperparameters

- 1 Hidden Layer with 50 Neurons

- **Activation Function:** Rectified Linear Unit (ReLU) 

- **Loss Function:** Mean Squared Error (MSE)

- **Optimizer:** Adam

- **Learning Rate:** 0.001

### Visualizations

| MLP History, Real Data & Predicted Values | MLP Real Data & Predicted Values |
| -------- | ------- |
| <img src="https://github.com/user-attachments/assets/9c058820-9444-44ed-87fb-31ee5f21972d" /> | <img src="https://github.com/user-attachments/assets/8058970c-c0e3-46db-a898-42b4f49e7d6b" /> |


## Convolutional Neural Network Implementation <a id="cnn"></a>

### Hyperparameters

- 1D CNN Model

- **Activation Function:** Rectified Linear Unit (ReLU)

- **Filters (Feature Maps):** 64

- **Kernel Size (Size of Local Patterns):** 3

- **Loss Function:** Mean Squared Error (MSE)

### Visualizations

| CNN History, Real Data & Predicted Values | CNN Real Data & Predicted Values |
| -------- | ------- |
| <img src="https://github.com/user-attachments/assets/3c5e2bdb-9826-4981-ba8d-574203bc8d71" /> | <img src="https://github.com/user-attachments/assets/8f16d903-cc69-4d11-acbe-87a4ed2fcee9" /> |


## Model Comparison <a id="comparison"></a>

Both the Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN) models are employed to predict retail sales. Each model operates differently and has distinct strengths and weaknesses.

- **MLP:** maps input data to the desired output by learning the weights of the edges during training.

- **CNN:** detects patterns in the input data by scanning through the data and learning to recognize significant patterns in the time series

### Results

Overall, the results of the MLP and CNN models are similar, with both providing reasonable predictions for retail sales. However, the MLP model performs slightly better, offering more precise predictions as indicated by its lower error metrics.

### Visualization

<img src="https://github.com/user-attachments/assets/cec247a5-56e2-4df7-9d45-32a8d7ec4cdd" width=600 />
