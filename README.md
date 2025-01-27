# IPL-Score-Prediction
This project aims to predict the total score of a cricket team at the end of their innings during an IPL match. The model is built using historical data from IPL seasons 1 to 9 (2008-2016) and tested on data from season 10 (2017). The model uses various machine learning algorithms to predict the score.

## Files in the Repository

1. **Module Project.ipynb**
   - This Jupyter Notebook contains the Python code for the entire workflow, including data preprocessing, model training, evaluation, and predictions.

2. **ipl.csv**
   - The dataset used in the project. It includes IPL match-related data for building and testing the model.

3. **linear_regression_model.pkl**
   - The serialized pickle file containing the trained linear regression model. This file allows for loading and using the pre-trained model without retraining.

4. **x_train_columns.pkl**
   - A pickle file that contains the names of the columns used for training the model. It ensures compatibility during model inference.
