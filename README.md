## Best Artworks of All Time

This project aimed to create a convolutional neural network (CNN) capable of recognizing artists based on the colours used and geometric patterns present in their artwork.

**Dataset**

The dataset utilized in this project was obtained from [Kaggle](https://www.kaggle.com/) and scraped from [artchallenge.ru](http://artchallenge.ru/).

It includes the following components:

* artists.csv: This CSV file contains information about each artist, which was used for data exploration and visualization. It formed the initial part of my presentation.

* images.zip: This compressed file consists of a collection of full-size images, categorized into folders based on the respective painters. This portion of the dataset was used to train a model capable of predicting the artist based on an input image.

It is important to note that the dataset is imbalanced, with training performed on 38 painters who each have a minimum of 80 paintings.

**Methodology**

The following techniques and tools were employed in this project:

* ImageDataGenerator: This tool was used for data augmentation, enabling the generation of additional training images to enhance the model's performance

* Class_weights: Class weights were employed to address the imbalance within the dataset during model training

* Pre-defined model (ResNet50): A pre-trained ResNet50 model with weights from ImageNet was utilized as a baseline. This model served as a starting point and provided a solid foundation for predicting artists based on the artwork
  
**Conclusion**

The Best Artworks of All Time project involved the development of a convolutional neural network to recognize artists based on colour usage and geometric patterns present in their artwork. Leveraging the provided dataset, various techniques and pre-trained models were employed to achieve accurate predictions.
