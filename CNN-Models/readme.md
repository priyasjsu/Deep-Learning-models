<img width="612" alt="image" src="https://github.com/priyasjsu/Deep-Learning-models/assets/113324576/2858fed5-2be1-4e4b-aa60-bc37091b5b22">

# Fashion Clothes Classification Using Convolutional Neural Network

### Implementation 1: Apply the following models on the Fashion Mnist Dataset. Train the model with the training data and evaluate the model with the test data.

a. CNN model from scratch: Develop a CNN model with 5 convolutional layers (with kernel size= 3, stride =1, padding = “same”, activation function = “relu”) with the following MaxPooling layer (Size= 2) and 3 fully connected layer (including one output layer). After each of the Convolutional layers apply Batch Normalization. In the fully connected layer apply dropout (rate 0.50).

b. Data Augmentation: Apply two image augmentation techniques on the Fashion Mnist train data to augment it and then apply the previously developed model to it.

c. Transfer Learning: Load the VGG-19 model. Drop after the block4 conv1 layer (highlighted in the image below) and on top of it add one global average pooling and one final output layer. Keep the base model layers (VGG19) freeze.

<img width="472" alt="image" src="https://github.com/priyasjsu/Deep-Learning-models/assets/113324576/df66fe43-1bf2-4402-a905-7ae91f93fe8e">

d. Make a comparison table including the above three models’ performance on the test data (accuracy), number of trainable parameters and the execution time. 

### Implementation 2: Develop the ResNet model from scratch, Applying a residual network specified in the following architecture.
All convolutional layers use kernel size 3, stride = 1, and padding = “same”, Save the trained model after training.

Code is not training the model from scratch and returning the model. Rather, the code should load a trained model from a model file and return it.

