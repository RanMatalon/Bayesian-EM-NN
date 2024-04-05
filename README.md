# Baysian-EM-NN
Comparing Baysian methods like BNN and EM to classic NN.

Baysian approch assumes the 'a priori' knowledge of probability models, then according to the observed data tries to achive a posterior distribution.

![image](https://github.com/RanMatalon/Baysian-EM-NN/assets/138029692/1b1edfc8-15ed-45dc-a7b3-4f2f7e74f642)

A baysian NN is a Neural Net which its weights are sampled every iteration from a distribution (and are not fixed weights like in classic NN).
![image](https://github.com/RanMatalon/Baysian-EM-NN/assets/138029692/eb41d454-af30-429a-b021-89ce9589d1d5)


I took the famous iris dataset, with another dataset of speaker's recognition that was used in 2 different ways :
  * Small dataset (3 of the 10 speakers, with less features)
  * The whole dataset

On each of the dataset i used PCA to reduce the dimensionality of the data, and to examine the clustering of the data by the 3 main components.

On each dataset we examine the 3 models:
  * EM (Expectation Maximization) algorithm for GMM unsupervised clustering.
  * Classic Deep NN for supervised clusteing.
  * Baysian NN for supervised clustring.
