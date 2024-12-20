# Share-Bike-Station-Clustering-and-Usage-Prediction


Bike sharing systems have become increasingly popular around the world for its benefits in public health, environment, and urban mobility. Managing the operations of such systems, however, requires a good understanding of bike usages. In fact, the prediction of bike de- mands is a critical component of many operational problems, including downstream bike rebalancing efforts. In recent years, there is a growing interest in adopting the cluster-then- predict approach, whereby bike stations are grouped into clusters first and bike demand predictions are made later for each cluster. This thesis project has two main objectives: first, examining how various station-to-cluster assignments may impact the bike check-out and check-in predictions, and second, understanding how transition information may influ- ence the bike check-in predictions. We present a five-step cluster-then-predict framework that generates station clusters using a state-of-the-art clustering algorithm, makes check-out predictions, computes cluster-to-cluster transition matrices, makes check-in predictions, and evaluates the predictions. Computational experiment results on Bike Share Toronto’s 2019 ridership data show that strategic clustering can produce clusters that will lead to better bike demand predictions than clustering by Forward Sortation Areas. In addition, it is discov- ered that the check-in prediction errors are reduced when the number of transition matrices used for the predictions increases (i.e., greater granularity in transition information). This work motivates further explorations of bike station clustering algorithms and establishes a connection between check-out and check-in predictions using cluster-to-cluster transition information. The cluster-then-predict method presented can also serve as a good starting framework to be extended and improved in the future.
