Older Driver Classification Code Repository
This repository contains code used for the research project on detecting abnormal driving behaviors among elderly drivers using advanced multimodal deep learning techniques.



Files Overview

Naive_Approach.ipynb: Contains the implementation of the naive model, which uses basic telematics features for abnormal driving detection.

Naive_Approach_Preprocessing.ipynb: Preprocessing code specifically for the naive approach, preparing the data for analysis.

Grid_Based_Approach.ipynb: Implements a grid-based approach that segments driving trajectories into grid cells, capturing spatial patterns in driver behavior.

Grid_Based_Approach_Preprocessing.ipynb: Preprocessing notebook for the grid-based approach, including steps to transform raw data into a suitable format.

Combined_Approach.ipynb: Combines features from both the naive and grid-based approaches for improved classification accuracy.

Validation_Experiment.ipynb: A 5-fold cross-validation setup to ensure that the model does not overfit, validating its robustness on unseen data.


Dataset
Please note that the dataset used for this research is not available in this repository as it is currently restricted. The data used consists of two years of driving telemetry for elderly drivers, focusing on capturing long-term driving patterns.

Methodology
Data Preprocessing: The preprocessing files prepare the raw driving telemetry for analysis, specifically tailored for the naive and grid-based approaches.

Experimentation: We applied various models on the final two years of data, incorporating 5-fold cross-validation (see Validation_Experiment.ipynb) to validate the model's performance and mitigate overfitting.
