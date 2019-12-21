# Cat-and-Dog-image-classification

**The dataset can be downloaded from Kaggle: <a href='https://www.kaggle.com/c/dogs-vs-cats'>Kaggle dataset</a>.**

This project is geared towards understanding the importance of using the State-of-the-art image classification models on your own small image classification problem

### For this project we built Convolutional Neural Network (CNN) model from scratch, and further utilized the state-of-the-art models such as VGG16 and ResNet50 as our pretrained model to perform Transfer learning on the dataset.

### To make your work computationally efficient, GPU will be required for this analysis

### ***Libraries used: pandas, matplotlib, pytorch, numpy***

We were able to visualize the loss and accuracy after each model training to observe and evaluate how the model did on our test data, from these visualization we were able to decipher how the model performed on the dataset

Overall we observed that for the model built from scratch and model built with transfer learning (using VGG16), the training accuracy was increasing (got to about 99% accuracy at the end of the model training) and the loss was declining in a manner that we would expect, BUT the test loss and accuracy were fluctuating. Even though, the accuracy was approximately between 98 - 99% , which is considerably good regarding our dataset but the loss wasn't decreasing as we would expect for the Test data.

On other hand, when we used ResNet 50 as our pretrained model for the transfer learning, these abnormalities seen in the earlier models were totally gone, even though we trained for only 5 epochs (based on my intuition), the accuracy for both the train and test data increased in a similar manner (got to about 98.5% accuracy at the end of the model evaluation) and also the loss for both dataset decreased in approximately similar manner, Nevertheless the train loss was smaller than the test loss as we would expect, but both were decreasing as the model was been trained and tested iteratively.

### Room for improvenments: ***there is inexhaustive room for improvenment for this project, for example, we could have tuned the hyperparameters more closely, but this would require the availability of GPU which is not readily available for the tuning and tweaking of hyperparameters as this would take a longer time than expected.***
