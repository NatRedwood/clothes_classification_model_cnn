# Clothes Prediction with Fashion MNIST
## Multi-classification prediction with CNN

## Dataset

The data used for the model training was downloaded directly from Keras datasets library. More details about the dataset available here: [fashion_mnist](https://keras.io/api/datasets/fashion_mnist/)
The project used the data split: 70/15/15 for train/dev/test set.
All the details about the experiments' set up are included in the pdf files [report(https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/pdfs/Redwood_Lab2_Raport.pdf). 

## Project Keypoints

1. How to build a CNN model?
2. How do different regularization techniques influence the CNN model performance?
3. How to interpret CNN representations?

## CNN Architectures and Experiments

The project concludes 8 experiments done on validation set to find the best performing model with 8 dofferent configurations of CNN model with various regularization techiniques. The top-performing model is used in the later analysis.
The Report pdf includes the interpretation of the performance, training time and accuracy curve.
![Experiment Results](https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/graphs/experiments_results.png)
![Learning Curves Model 1-4](https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/graphs/accuracy_first4models.png)
![Learning Curves Model 5-8](https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/graphs/accuracy_second4models.png)

## CNN Representations - Visualization of Convolutional Layers

The top-performing model was slightly changed and used for CNN represantation experiments.
The project explores the role of 2 different convolutional layers by analyzing its plotted representations. The deep interpretation is included in the pdf report files: report file or report+code file; both can be found in the [repo directory](https://github.com/Nwojarnik/clothes_classification_model_cnn/tree/main/pdfs).

![1st Conv Layer](https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/graphs/1st_conv_layer.png)

![4th Conv Layer](https://github.com/Nwojarnik/clothes_classification_model_cnn/blob/main/graphs/4th_conv_layer.png)
