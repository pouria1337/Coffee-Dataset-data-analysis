# Coffee-Dataset-data-analysis

Data pre-processing (cleaning), statistical plotting, and machine learning on a public dataset of retail coffee hosted at [Kaggle](https://www.kaggle.com/datasets/a27fcd650722d16b078b5c4160242413865a4ee8897071dd24e7fdc180f328e3). Each process is carried out in a Jupyter Notebook in its own directory. Below is the result of training three features __[price, rating, reviews]__ on five ML classifier to build a model that can predict the __[coffee_type]__ feature.

|             |   LogisticRegression |   Random-forest |   SVM |   GradientBT |   Decision-tree |
|:------------|---------------------:|----------------:|------:|-------------:|----------------:|
| Accuracy    |                 0.61 |            0.7  |  0.46 |         0.69 |            0.76 |
| Precision   |                 0.27 |            0.53 |  0.29 |         0.48 |            0    |
| Recall      |                 0.24 |            0.58 |  0.29 |         0.53 |            0    |
| F1-accuracy |                 0.34 |            0.52 |  0.3  |         0.48 |            0    |

Below I have depicted the Decision Tree:

As it can be observed, each cell has as its first line one of the three features. By following the constraints set on each cell, user can determine the roast type of a coffee product with a 76% accuracy.

![Alt text](Machine-learning%20(Classification)/DTree.png)
