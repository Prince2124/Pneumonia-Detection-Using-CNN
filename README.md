## Pneumonia Detection Using Transfer Learning (CNN)
Emplement of Deep Learning (DL) models particularly Convolutional Neural Networks (CNNs) to detect pneumonia from Lung X-rays of patients. CNN-based VGG16 model is used to classify chest X-ray images of  pneumonia patients and normal patients and predict  patients have with pneumonia or not .

![image](https://user-images.githubusercontent.com/59818604/132743527-7399d1a8-ee8b-4a8e-9cb6-900c7918bced.png)

## Datasets
with Kaggle dataset available from [here](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).It consists of 5863 X-ray images of lungs taken on a group of paediatric patients . All of images have been labeled by 2 specialists to minimize labeling error risk. The data was already split for us into training, validation and test datasets.

## Detection 
In this project we'll Use Transfer learning using VGG16 model and customize our model to predict whether a person has Pneumonia.
* NORMAL IMAGE

![image](https://user-images.githubusercontent.com/59818604/132742509-09bdaa41-241f-41a6-a17d-76fbc183ab30.png)
* PNEUMONIA IMAGE

![image](https://user-images.githubusercontent.com/59818604/132742610-8c00c8ac-8640-4ae0-951e-05e8efab4275.png)

Then transfer learning was used with convolutional neural networks by utilising VGG16 as the base model for image classification. The model was able to achieve *94.5% accuracy* on the validation set.
## References
https://github.com/Sanket2311/Pneumonia-Classification-using-Transfer-learning
