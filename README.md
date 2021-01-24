# Fake-News-Bangla

This is the very first work in natural language processing that addresses the class imbalance issue on Bengali, a low resource language. We tackle the problem by applying a number of strategies that include data augmentation with synthetic samples via text and embedding generation with a view to augmenting the proportion of the minority samples. Additionally, we apply ensembling of deep learning models by subsetting majority samples. Moreover, we enforce the focal loss function for class imbalanced data classification. We also apply the outlier detection technique, data resampling, and hidden feature extraction to improve the minority-f1 score. We perform these strategies in one of the most trending NLP tasks, i.e. fake news detection using a benchmark dataset that contains critical class imbalance, i.e. only 3.27% of minority class samples. Our extensive experimentation results in a maximum minority-f1 score of 87% without degrading the overall performance which is an excellent outcome on such a highly class-imbalanced dataset.

Scripts include training & testing for: 

1. Deep Learning models trained using weighted binary cross-entropy
1. Deep Learning models trained using weighted focal loss
1. ML models trained on hidden layer of a DL model
1. Resampling using upsampling and downsampling
1. Ensembling using horizontal partitioning

keras, scikit-learn, tensorflow
