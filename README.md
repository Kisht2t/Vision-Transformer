# Vision-Transformer
Vision Transformer-based models for image classification on kaggle cats and dogs dataset


# 1. Dataset Preparation

1. Load dataset: The Cats and Dogs contains two classes (cats, dogs).

• Load the dataset using Keras.

• Resize al images to 224x224 pixels, and normalize pixel values to [0, 1].(Binary Classfication)

• Split the data into training and testing sets. Further split the testing set into a testing and
validation subsets. Set up data loading for each.

# 2. Standard Vision Transformer (ViT) Model

.1 Implement the ViT Model:

• Load a pretrained Vision Transformer (ViT) model from Hugging Face using the TFViTModel class.

• Add a classification head after the VTi blocks, with 10 output units (one for each class ni CIFAR-10), or 1output unit for the Cats and Dogs problem).

• Compile the model with an appropriate optimizer, loss function, and metrics. 

.2 Training:

• Train the model on the training set.

• Save checkpoints periodically, and log training/validation loss and accuracy. 

.3 Evaluation:

• Evaluate the model on the test set, reporting accuracy and other relevant metrics. • Plot the training and validation accuracy and loss over epochs.

IDE: Uses Google Collab and Jupyter Notebook
