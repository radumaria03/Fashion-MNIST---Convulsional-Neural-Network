# Fashion-MNIST---Convulsional-Neural-Network

# PyTorch Course Project - Classification Problem

**FashionMNIST Dataset**
 * the dataset contain 32*32px gray scale images of different fashion products

<img width="716" height="557" alt="fashion" src="https://github.com/user-attachments/assets/ad7b293d-0a59-464d-a28f-3cf01a438110" />

# Computer Vision - Convulsional Neural Network
 * the data is passed through a convulsional neural network
 * the model find patterns and tries to predict the fashion products category

# Model Predictions - after Training Session

<img width="763" height="715" alt="predictions" src="https://github.com/user-attachments/assets/25733d05-6068-46c7-beda-362a882a7a53" />

# Metrics
 * since we have a classification problem, to evaluate our model performance it's best to use a cofusion matrix
 * a confusion matrix help us see where our model got "confused", for example since some fashion items look similar the model might predict the wrong category ( shirt vs t-shirt)
 * based on the images below, the model classified 235 images as "Shirt" but the true label was "T-shirt" - so the confusion matrix is helping us to see where our model has difficulties in making the right prediction

<img width="675" height="647" alt="confusion matrix" src="https://github.com/user-attachments/assets/26af4d85-559a-4724-9a6b-068dfc77ef59" />


