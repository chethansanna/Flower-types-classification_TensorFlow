## Data source:

The model was trained and tested on the dataset from [TensorFlow](https://www.tensorflow.org/datasets/catalog/tf_flowers).

## Data description:

The dataset used for this classification task contains 3670 images which belongs to 5 classes namely:

1. Rose
2. Daisy
3. Dandelion
4. Sunflowers
5. Tulips

---

## Models

Here, flower types are classified using two models:

1. Custom CNN model - created and trained from scratch. This model has 4 Convolutional layers along with Pooling, Fully Connected and Softmax layers.
2. Transfer learning - A pre-trained [MobileNet](https://arxiv.org/pdf/1704.04861.pdf) model by Google was used for classification. The MobileNet model has 27 Convolutional layers along with Pooling, Fully Connected and Softmax layers.

---

## Results:

The Custom CNN model achieved 79.32% validation accuracy. Whereas, MobileNet achieved 90.34% validation accuracy on the same dataset by training for very less number of epochs. 
