 **Predicting Density of Monoethanolamine-Methanol Mixture from Temperature Using Artificial Neural Networks**

#### Project Overview

This project focuses on predicting the density of a monoethanolamine-methanol mixture based on temperature measurements using Artificial Neural Networks (ANNs). The objective is to build a model that can accurately forecast the density of the mixture given its temperature, leveraging both Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) as performance metrics to assess the model's effectiveness.

#### Key Components

1. **Data Collection and Preprocessing**
   - **Datasets:** The project utilizes two datasets containing temperature and density measurements. One dataset (`density12.xlsx`) includes training and testing data, while the second (`density13.xlsx`) serves as an additional validation set.
   - **Preprocessing Steps:** Data from both datasets is loaded and standardized to ensure uniformity in the features and target variables. This involves scaling the temperature and density values to facilitate effective model training.

2. **Model Building and Training**
   - **Artificial Neural Network (ANN):** A Sequential ANN model is constructed with multiple dense layers. The model architecture includes input, hidden, and output layers, with ReLU activation functions in the hidden layers.
   - **Loss Functions:** The model is trained using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) as loss functions to measure prediction accuracy.
   - **Training Process:** The ANN is trained over several epochs with a specified batch size, employing data splitting to validate the model's performance on unseen data.

3. **Model Evaluation**
   - **Error Metrics:** Performance is evaluated using MSE and RMSE to quantify prediction accuracy. The Mean Absolute Percentage Error (MAPE) is also calculated to provide a percentage-based error metric.
   - **Comparison and Visualization:** Actual vs. predicted densities are compared, and error percentages are computed. Results are visualized through plots and saved to an Excel file for further analysis.
![download (18)](https://github.com/user-attachments/assets/5d20317d-eac0-49f1-a47b-be5faccd0f56)


4. **Results and Analysis**
   - **Comparison Tables:** A detailed comparison of actual vs. predicted densities is provided, including error percentages for each prediction.
   - **Visual Plots:** Graphical representations of the actual and predicted densities are generated to visually assess model performance.
![Screenshot 2024-08-07 204858](https://github.com/user-attachments/assets/337c6226-f762-44f1-a8b5-2e2ecfd48d74)

![download (19)](https://github.com/user-attachments/assets/1062eaa3-b887-4523-ab03-5c54f4bb20d9)

![Screenshot 2024-08-07 204955](https://github.com/user-attachments/assets/299e9422-723f-4685-b56f-6193e984477b)

5. **Additional Features**
   - **Model Visualization:** The model architecture is visualized using tools such as `pydot` and `graphviz`, offering insights into the network structure and layer configuration.

This project demonstrates the application of ANNs in predicting physical properties of chemical mixtures, highlighting the importance of model performance metrics and visualization techniques in evaluating and refining predictive models.
