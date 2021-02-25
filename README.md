# Classification of flower's type using TensorFlow

The dataset used for this classification task contains 3670 images which belongs to 5 Classes namely:

1. Rose
2. Daisy
3. Dandelion
4. Sunflowers
5. Tulips

Here, flower is classified using two models:

1. Custom CNN model created and trained from scratch. This model had 4 Convolutional layers along with Pooling, Fully Connected and Softmax layers.
2. Transfer learning - A method in which a pre-trained [MobileNet](https://arxiv.org/pdf/1704.04861.pdf) model by Google was used for classification. The MobileNet model had 27 Convolutional layers along with Pooling, Fully Connected and Softmax layers.

## Results:

The Custom CNN model achieved 79.32% validation accuracy after training for 63 Epochs. Whereas, MobileNet achieved 11.02% more validation accuracy than the custom CNN model i.e. 90.34% in just 30 Epochs. 
