# Fault Detection and Prediction in Joint Human-Automated Systems

**This project aims to detect and predict faults in joint human-automated systems using unsupervised PCA anomaly detection and neural networks.**

The dataset used in this project includes fault-free and faulty training datasets with 55 columns of process variables sampled every 3 minutes for a duration of 25 hours.

The faults were introduced after 1 hour into the Faulty Training datasets, and the dataset includes a 'faultNumber' column that ranges from 1 to 20 in the Faulty datasets and represents the fault type in the TEP. The FaultFree datasets only contain fault 0 (normal operating conditions).

## Files

The project includes the following files:
- `README.md`: This file, containing information about the project.
- `data`: A directory containing the fault-free and faulty training datasets in R dataframe format.
- `notebooks`: A directory containing Jupyter notebooks for the unsupervised PCA anomaly detection and neural network fault prediction.



