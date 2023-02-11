# SGH-ICU-Patients

In this project, I performed basic preprocessing, [data visualizations](https://github.com/chingfhen/SGH-ICU-Patients/blob/main/Visualizations.ipynb), and [model training](https://github.com/chingfhen/SGH-ICU-Patients/blob/main/Model%20Training.ipynb) on ICU Patient Data from [sqlite3](https://github.com/chingfhen/SGH-ICU-Patients/blob/main/sqlite%20database%20processing.ipynb). 

More info:

The best model could predict survival at 93% fbeta score. With this metric, we can be sure the we are prioritizing patients who are at risk of mortality. Based on my analysis, some indicators of mortality at ICU are SysBP<170, Age>50, or from emergency. It would be interesting to see how these analysis and modelling could be used in practice. Suppose, the complexity of the problem increases, it would be beneficial to automate the detection of serious complications like mortality by deploying models through apps because human detection will not be easy.
