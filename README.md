# *Dog vs Cat Image Classification Project*

#### **Overview**
This project uses a Convolutional Neural Network (CNN) to classify images of dogs and cats. The CNN is implemented using **TensorFlow and Keras**, and the dataset comprises thousands of labeled images.

#### **Dataset**
- Training Set: 8000 images (4000 dogs, 4000 cats).
- Test Set: 2000 images (1000 dogs, 1000 cats).
- Single Prediction Folder: Includes images for testing individual predictions.

#### **Steps to Reproduce**
1. Clone this repository:
   ```bash
   git clone https://github.com/NishaKathiriya/CNN-for-image-classification-cats-vs-dogs.git 
   ```
2. Navigate to the project directory:
   ```bash
   cd CNN-for-image-classification-cats-vs-dogs
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

#### **Model Architecture**
- **Input Shape**: `(64, 64, 3)`
- **Convolutional Layers**: Extract image features.
- **Pooling Layers**: Downsample the features.
- **Dense Layers**: Fully connected layers for binary classification.
- **Output Layer**: Sigmoid activation for binary classification.

#### **Results**
- Training Accuracy: ~85%
- Test Accuracy: ~85%

#### **Medium Link**
Read more about the project and its purpose on my [Medium article](https://medium.com/@nishakathiriya01/dog-vs-cat-image-classification-using-cnn-a-step-by-step-project-5f3eb320393d)



