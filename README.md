# DATA-DRIVEN TECHNIQUES FOR STREAMFLOW PREDICTION 
Accurate streamflow prediction is crucial for effectively managing water resources, particularly in dams and reservoirs. It ensures a steady water supply for agriculture and industry and plays a vital role in disaster mitigation during floods and water conservation in times of low flows. This study aims to predict daily streamflows in Yerli catchment of the Tapi Basin. The selected catchment represents a semi-arid climate, marked by low precipitation levels and higher losses, contributing to occasional flash floods. In this context, the term “losses” refers to various processes that lead to the reduction or non-inclusion of water in the streamflow. These can include evaporation, infiltration, and other forms of water depletion that occur within the catchment before water contributes to the streamflow. The study aims to understand and model these dynamics to enhance streamflow predictions in these semi-arid regions. The predictive models employed include Multiple Linear Regression (MLR), M5 Model Tree, and Random Forests, developed using Python with Jupyter Notebook as the Integrated Development Environment. The input variables for the models consist of rainfall values from various gauge stations, temperature data, and discharge from preceding days. Feature selection involves considering correlations and clustering, leading to the training of machine learning models for different combinations of these selected variables. The models’ performance is evaluated using various statistical parameters. This study rigorously investigates the effectiveness of diverse data-driven approaches, including Multiple Linear Regression (MLR), Random Forest (RF), and M5 Model Tree, in streamflow prediction. The M5 Model Tree consistently outperform the other models, showcasing remarkable predictive accuracy with maximum R2 values 0.77 for Yerli. These findings provide valuable insights for managing water resources in complex hydrological systems.

Time series Model: Considering discharge with different time lag are used as features.
Cause-Effect Model: Considering rainfall and temperature as features.
Combined Model: Considering mixture of both features mentioned above.

80% of data is used for training the machine learning models and 20% is used to test the model.

![image](https://github.com/kallepalli-Deepak/DATA-DRIVEN-TECHNIQUES-FOR-STREAMFLOW-PREDICTION-/assets/144247554/32bdbe0b-5557-40f8-a8de-9bd47458cf2f)
Visualization of annual rainfall distribution for the Yerli catchment in the Tapi basin.

![image](https://github.com/kallepalli-Deepak/DATA-DRIVEN-TECHNIQUES-FOR-STREAMFLOW-PREDICTION-/assets/144247554/715a70d6-a547-49fb-8dcc-3fdedd77ba27)



