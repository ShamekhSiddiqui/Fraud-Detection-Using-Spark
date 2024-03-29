# Fraud Detection using Spark (Scalable ML) and AWS


==========================

This project involved solving:

Problem 1: Classification and prediction ensembles using existing libraries for in-memory processing on a single machine (spark) by training individual models using existing libraries - scikit learn and coding the parallel framwork of ensemble from scratch. 

Problem 2: Classification and prediction in spark MLlib by training models using decision trees and random forest - MLlib libraries

========================== 

This project consists of several folders, each serving a specific purpose. Below is an overview of the folders and their contents:

- **conf**: Contains the `install_python_dependencies.sh` file used for bootstrapping in AWS before executing the PySpark script.

- **src**:
  - **spark-base**: Implements individual models using scikit-learn libraries, focusing on parallel processing using PySpark.
  - **spark-mllib**: Implements models using decision tree and random forest classifiers with Spark MLlib library.

- **input**: Designated location for input files used by the PySpark scripts.

- **output**: Stores the output of various runs from both the `spark-base` and `spark-mllib` programs.

- **logs**: Contains AWS stdout/stderror logs for debugging or monitoring purposes.

- **Makefile**: Provides commands and scripts to facilitate setup and execution of the project on an AWS bucket.

Please refer to the individual folders and their contents for more detailed information on each component of the project.
