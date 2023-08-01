# Power Plant Electrical Energy Output
This repository contains a Python project that aims to predict the electrical energy output of a power plant based on various environmental factors, such as temperature, ambient pressure, relative humidity, and exhaust vacuum. Several regression models are utilised and evaluated for this prediction task, including Linear Regression, Decision Tree, Random Forest, XGBoost, and Neural Network.

## Dataset:
The dataset used for this project can be found in `power_plant_data.csv`. It contains a collection of features (input variables) and the power plant's corresponding energy output (target variable).
### Source:
Pnar Tfekci, Heysem Kaya. (2014). Combined Cycle Power Plant. 
UCI Machine Learning Repository. 
https://doi.org/10.24432/C5002N

## Code:
The main Python script `Power_Plant_Energy_Output.ipynb` includes code snippets for data preprocessing, model training, hyperparameter tuning, and evaluation. The script employs TensorFlow for the Neural Network and sci-kit-learn for other regression models. The trained models are also saved to disk for future reuse.

## Model Evaluation and Visualization
The project evaluates each model's performance using Mean Squared Error (MSE) and R-squared (R2). Hyperparameter tuning is employed for better model generalization. The results are visualized with bar charts, showcasing the comparative performance of the different models.

## Conclusion
After a thorough evaluation, the Random Forest and XGBoost models outperform the other regression models and the Neural Network in predicting the power plant's energy output. XGBoost achieves the lowest MSE and the highest R-squared value, indicating its superior predictive capabilities. These findings demonstrate the effectiveness of ensemble methods and gradient boosting in handling complex regression tasks.
