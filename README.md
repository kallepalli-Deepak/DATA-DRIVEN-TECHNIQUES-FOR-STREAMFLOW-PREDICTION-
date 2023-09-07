# Streamflow-prediction-using-AI-ML-techniques
Streamflow prediction is essential for efficiently managing water resources such as dams and reservoirs. If streamflow can be predicted accurately, then the stable water supply for agriculture and industry from the reservoir can be assured. Also, if there is high streamflow, properly planned actions can be taken, such as opening reservoir gates, alerting people living in low-lying areas, or shifting them if required. This study predicts streamflow in the Gopalkheda sub-catchment of the Purna River, a major tributary of the Tapi River, using Multiple Linear Regression (MLR) and M5 Model Trees. Python is used to develop these models, and Jupyter Notebook is used as an Integrated Development Environment for Python. A major part of the Gopalkheda catchment is in Maharashtra, and the minor is in Madhya Pradesh. The model is evaluated using statistical performance indices like R2 value and Root Mean Square Error (RMSE). Based on these parameters, the M5 Model tree performed better than the MLR model. The highest R2 value obtained for the M5 Model Tree is 0.74.


Time series Model: Considering discharge with different time lag are used as variables.
Cause-Effect Model: Considering rainfall and temperature as variables.
Combined Model: Considering mixture of both variables

Models are developed for three data splits:
1. 80% for testing and 20% for training.
2. 75% for testing and 25% for training.
3. 70% for testing and 30% for training.
