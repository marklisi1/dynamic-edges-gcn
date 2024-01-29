# dynamic-edges-gcn
This repository contains all code used in the research project ["Variable Proximity-Based Graph Structure for Emission Modeling and Prediction"](variable_prox_graph.pdf) by Mark Lisi! For a detailed explanation of the data, models, and techniques used, check out the attached PDF in this repository.

There are three notebooks for different tasks outlined in the paper:
- `node-connections.ipynb` for aggregation of tabular data into graph structures/PyG `Data` objects
- `classification-testing.ipynb` for setup, training, and testing of models on classification tasksk
- `regression-testing.ipynb` for setup, training, and testing of models on regression tasks

All data used is publicly available on the [Climate TRACE 2021 website]([url](https://climatetrace.org/downloads)https://climatetrace.org/downloads). To recreate the results, download relevant datasets from this website. Then, you must generate edge indices using the scripts created in the first notebook (`node-connections.ipynb`). From there you are free to test your results in both the classification and regression notebooks!
