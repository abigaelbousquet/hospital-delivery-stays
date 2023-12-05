# hospital-delivery-stays
This project follows the complete supervised ML pipeline to create a regression model for predicting length of stay for new mothers delivering in a hospital. This is based on public hospital discharge data (2021) from the NY DOH.

## Dataset
Original Dataset: https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/tg3i-cinn
Final Dataset (the relevant subset of the above): ./data/planned_deliveries.csv
Data Dictionary for Final Dataset: ./data/DataDictionaryPlannedDeliveries.txt

## Dependencies
Please see ./data1030project.yml for the complete list of dependencies.

Key Dependencies:
- python=3.11.4
- scikit-learn=1.2.2
- pandas=2.0.3
- matplotlib=3.7.2
- numpy=1.24.4
- scipy=1.11.2
- verstack=3.8.12
- xgboost=2.0.0
- shap=0.42.1
- jupyterlab=4.0.5
- ipykernel=6.25.2
- pickleshare=0.7.5
