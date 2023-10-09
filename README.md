# Melanoma Cancer Detection Using CNN
We are usiung multiclass classification model using a custom convolutional neural network in TensorFlow.
In the past 10-year period, from 2008 to 2018, the annual number of melanoma cases has increased by 53%, partly due to increased UV exposure. Although melanoma is one of the most lethal types of skin cancer, a fast diagnosis can lead to a very high chance of survival.

The first step in the diagnosis of a malignant lesion by a dermatologist is visual examination of the suspicious skin area. A correct diagnosis is important because of the similarities of some lesion types; moreover, the diagnostic accuracy correlates strongly with the professional experience of the physician. Without additional technical support, dermatologists have a 65%-80% accuracy rate in melanoma diagnosis. In suspicious cases, the visual inspection is supplemented with dermatoscopic images taken with a special high-resolution and magnifying camera. During the recording, the lighting is controlled and a filter is used to reduce reflections on the skin, thereby making deeper skin layers visible. With this technical support, the accuracy of skin lesion diagnosis can be increased by a further 49%. The combination of visual inspection and dermatoscopic images ultimately results in an absolute melanoma detection accuracy of 75%-84% by dermatologists.

- Convolutional Neural Networks
CNNs are neural networks with a specific architecture that have been shown to be very powerful in areas such as image recognition and classification. CNNs have been demonstrated to identify faces, objects, and traffic signs better than humans and therefore can be found in robots and self-driving cars.

CNNs are a supervised learning method and are therefore trained using data labeled with the respective classes. Essentially, CNNs learn the relationship between the input objects and the class labels and comprise two components: the hidden layers in which the features are extracted and, at the end of the processing, the fully connected layers that are used for the actual classification task. Unlike regular neural networks, the hidden layers of a CNN have a specific architecture. In regular neural networks, each layer is formed by a set of neurons and one neuron of a layer is connected to each neuron of the preceding layer. The architecture of hidden layers in a CNN is slightly different. The neurons in a layer are not connected to all neurons of the preceding layer; rather, they are connected to only a small number of neurons. This restriction to local connections and additional pooling layers summarizing local neuron outputs into one value results in translation-invariant features. This results in a simpler training procedure and a lower model complexity.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Conclusions
- Conclusion 1 > 90.46% Training accuracy and 52.35% validation accuracy.
- Conclusion 2 > 60.32% Training accuracy and 56.15% validation accuracy ( Data Augumentation).
- Conclusion 3 > 62.44% Training accuracy and 57.49% validation accuracy ( Data Augumentation + 1 Dropout layer)
- Conclusion 4 > 95.72% Training accuracy and 82.33% validation accuracy ( Class rebalancing )




## Technologies Used
- Tensorflow- version 2.14.0
- Keras     - version 2.14.0
- Pandas    - version 2.0.3
- Augmentor - version 0.2.12
- Numpy     - version 1.24.3
- Glob


## Acknowledgements

- References if any https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6231861/
- This project was based on [this tutorial](https://www.tensorflow.org/tutorials/images/classification).


## Contact
Created by [@yuvarajgb] - feel free to contact me!

