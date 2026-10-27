ANN Binary Classification

About the Project
This project uses an Artificial Neural Network (ANN) to classify data into two classes.
For this project, I used the **make_moons dataset** from Scikit-learn. The dataset has a non-linear pattern, so it is useful for understanding how a neural network learns and separates data.
Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

What I Did

1. Created the make_moons dataset.
2. Split the data into training and testing sets.
3. Scaled the input features.
4. Built an ANN with two hidden layers.
5. Trained the model using the Adam optimizer.
6. Evaluated the model using accuracy and other metrics.
7. Visualized the results using graphs and a confusion matrix.
8. Tested the model with new sample data.

Model Structure

Input (2 features)
       |
Dense Layer (16 neurons)
       |
Dense Layer (16 neurons)
       |
Output (1 neuron)


Activation: ReLU and Sigmoid  
Optimizer: Adam  
Loss: Binary Cross-Entropy

Results

The model successfully learns the pattern in the dataset and predicts the class of new data points.
The notebook also shows the accuracy, loss, confusion matrix, ROC-AUC score, and decision boundary.

CNN project

Cat vs Dog Image Classification
About the Project
This project uses a Convolutional Neural Network (CNN) to identify whether an image is a Cat or a Dog.
I used the Cats vs Dogs dataset and trained the model using TensorFlow and Keras.

Technologies Used

- Python
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

What I Did

- Loaded the Cats vs Dogs dataset.
- Resized the images to 128 × 128.
- Built a CNN model with convolution and pooling layers.
- Trained the model using training and validation data.
- Tested the model on unseen images.
- Checked the results using accuracy and a confusion matrix.
- Tested the model with a sample image.

Model

Input Image
    |
Convolution + Pooling
    |
Convolution + Pooling
    |
Convolution + Pooling
    |
Dense Layer
    |
Cat / Dog Prediction


Optimizer: Adam  
Loss: Binary Cross-Entropy  
Epochs: Up to 10

Result

The model can classify images as Cat or Dog and shows the prediction probability along with the actual class.


Author

Janani M
B.Tech Artificial Intelligence and Data Science  
KalaignarKarunanidhi Institute of Technology, Coimbatore
