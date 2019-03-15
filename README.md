# Text-classification-using-CNN
I have tried implementing multiclass text classification. The data used was customer review data with labels (1,2,3,4,5), 5 being the most positive review.

# Pre-Processing
Steps like punctuation removal, lower casing, word-segmentation have been implemented

# Model
A CNN with first layer as the 'Embedding Layer' (https://keras.io/layers/embeddings/) with Convolutional filters and finally dense layers with softmax output

