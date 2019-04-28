# Feature-selection-parallelization

In machine learning linear regression is popular modeling method. We predict the response variable given a set of input variables(features). As number of input variables increases, the model can become complex, increases computation and memory usage and difficult to comprehend. It will also be more susceptible to noise. It is necessary to exclude some features as they might be adding less value in predicting response variable. Hence, we use dimensionality reduction to explain the model which reduced number of features. This helps to make the model simple and comprehensible.
This paper uses subset selection as the way to reduce the dimensions. Given N number of dimensions(features), we will have 2N combinations of models to choose from. i.e. we evaluate the performance of each model and choose the best fitting model. This is method is not scalable and will perform poorly as number of features increases. It is essential to paralyse the algorithm to improve the scalability. Hence, this paper gives the method to paralyze subset selection procedure for multiple linear regression.

Implement subset selection in multiple regression using R with libraries foreach and doParallel. Compare the efficiency of algorithm in linear versus parallel algorithms.
Design sequential algorithm using R which find the best model with subset of features. Paralyze the algorithm with doParallel and foreach packages. Goal is increase the efficiency by utilising the given resource to the fullest.

DataSet: https://archive.ics.uci.edu/ml/datasets/wine+quality
