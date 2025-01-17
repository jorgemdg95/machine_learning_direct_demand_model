# machine_learning_direct_demand_model
Our publicly accessible repository houses a comprehensive dataset of network, operational, and sociodemographic characteristics for various transit agencies. This resource is invaluable for researchers, transit agencies, and data enthusiasts interested in transit system analysis and leveraging machine learning techniques for predictive modeling.

## Files in the folder:

1. training_dataset.csv: Contains all observations used to train the machine learning models.
2. FCM_Clustering_Model.ipynb: The Python notebook with the code for clustering agencies. The cluster number is reported here. 
3. model_optimal_parameters.csv: Includes the optimal parameters for Random Forest, Gradient Boosting Regressor (GBR), and Support Vector Regression (SVR).
4. Direct_Demand_Models.ipynb: The Python notebook with the code for training and applying the models.
5. prediction_dataset.csv: The file that agencies need to modify to input their ridership data for prediction.
6. predictions_results.csv: The output file containing the prediction results.
7. Real world maps: Contains maps used to validate our interpretation of the clusters.

## Instructions:


- Place all files are placed in the same directory for the code to function correctly.
- Add the information of your agency to the prediction_dataset.csv.
- Ensure all file names are as instructed above.
- You should first execute the cluster model code to determine the cluster of each observation.
- Next, you must run the Direct_Demand_Models.ipynb notebook to generate ridership predictions.
- After running the code, predictions_results.csv will be overwritten with the new results.
