# Fake-News-Bangla

This paper addresses the class imbalance issue on a low resource language, called Bengali. As a use-case, we choose one of the most trending NLP tasks, i.e. fake news detection where we utilize a benchmark dataset that contains critical class imbalance, i.e. only 3.27% of minority class samples. We attempt to tackle the problem by applying several strategies that include data augmentation with synthetic samples via text and embedding generation in order to augment the proportion of the minority samples. Moreover, we apply ensembling of deep learning models by subsetting majority samples. Additionally, we enforce the focal loss function for class imbalanced data classification. We also apply the outlier detection technique, data resampling, and hidden feature extraction to improve the minority-f1 score. All of our experimentation are entirely focused on textual content analysis which result in a maximum minority-f1 score of 91% with 85% recall and 97% precision which is an excellent outcome on such a highly class-imbalanced dataset and also an improvement over the previous work.

Scripts include training & testing for: 

1. Deep Learning models trained using weighted binary cross-entropy
1. Deep Learning models trained using weighted focal loss
1. ML models trained on hidden layer of a DL model
1. Resampling using upsampling and downsampling
1. Ensembling using horizontal partitioning

keras, scikit-learn, tensorflow
