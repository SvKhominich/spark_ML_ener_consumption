# Energy Consumption Prediction with Spark ML

**Dataset:** HEAPO – Heat Pump Optimization Dataset  
**Goal:** predict household electricity consumption and test a simple consumption segmentation task.

In this notebook, I:
1. load and join metadata, smart meter, and weather parquet files,
2. prepare a machine-learning dataset,
3. build stronger time features,
4. avoid time leakage by using a **time-based train/test split**,
5. train **Linear Regression** and **Random Forest Regression** with a proper Spark ML pipeline,
6. test a secondary **classification** task with Logistic Regression,
7. evaluate the models without using pandas.
