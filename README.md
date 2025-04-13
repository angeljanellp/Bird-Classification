# Bird-Classification :bird:

Goal: Create a image classification model with a 85% or higher accuracy. Animal chosen: bird :bird:.

Dataset: Bird Species dataset from Kaggle.

URL: https://www.kaggle.com/datasets/umairshahpirzada/birds-20-species-image-classification?resource=download

The dataset contains:

20 bird species 3208 training images, 100 test images(5 images per species) 100 validation images (5 images per species)

Description:
* Imports
* EDA
* ImageDataGenerator
* models: CNN, VGG16, Inception V3
* For all models: changes in the layers, model.fit, metrics Dataframe, loss and accuracy plots, and predictions, save all models, but using the one with highest accuracy to predict the new images.

Analysis: we noticed that although you add a ton of layers, you add more filters, sometimes more, can be bad for your model, which can lead to overfitting, so although it does well in the training, when its time to test it, its lower.
  
