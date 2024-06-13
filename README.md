# Data-Mangement-Spark-MLlib
## Data Processing
This project uses the Iris dataset. First, load the Iris dataset into a Spark DataFrame. And perform data cleaning, remove NA values, and create a new column to store the results of encoding the "Species" column The following figure shows the data set.

![WhatsApp 图像2024-06-13于15 59 45_b8198481](https://github.com/PanLuochuan/Data-Mangement-Spark-MLlib/assets/152348928/156fbb69-2a84-4bff-b5e2-fc382dbc5d8a)

The processed data set is divided into training set and test set, with a ratio of 7:3.

## Decision Tree
Use Decision Tree from Spark MLlib. A parameter grid is set up, taking into account the maxDepth, maxBins, and Impurity of the Decision Tree, which directly affect the complexity and performance of the model. Cross-validation is performed through CrossValidator. The output in the figure below is the parameters of the best model and performance evaluation (Accuracy, Precision, Recall, and F1 score)

![WhatsApp 图像2024-06-13于16 19 12_f3151226](https://github.com/PanLuochuan/Data-Mangement-Spark-MLlib/assets/152348928/051855b3-5499-4b8e-801b-ed7486b6bf80)

## Random Forest
Use Random Forest from Spark MLlib. A parameter grid is set up, taking into account the maxDepth, numTrees, and minLinstancesPerNode of the Random Forest, which directly affect the complexity and performance of the model. Cross-validation is performed through CrossValidator. The output in the figure below is the parameters of the best model and performance evaluation (Accuracy, Precision, Recall, and F1 score)

![WhatsApp 图像2024-06-13于16 23 15_8f397370](https://github.com/PanLuochuan/Data-Mangement-Spark-MLlib/assets/152348928/3859a198-3ac3-4f1a-96ba-4a5efd58d5ae)

## Logistic Regression
Use Logistic Regression from Spark MLlib. A parameter grid is set up, taking into account the regParam and ElasticNetParam of the Logistic Regression, which directly affect the complexity and performance of the model. Cross-validation is performed through CrossValidator. The output in the figure below is the parameters of the best model and performance evaluation (Accuracy, Precision, Recall, and F1 score)

![WhatsApp 图像2024-06-13于16 28 48_5cce1d8f](https://github.com/PanLuochuan/Data-Mangement-Spark-MLlib/assets/152348928/f1d8591f-74a3-45d3-9fc1-af6f139412ac)

