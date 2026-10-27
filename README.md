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

text
Input (2 features)
       ↓
Dense Layer (16 neurons)
       ↓
Dense Layer (16 neurons)
       ↓
Output (1 neuron)


Activation: ReLU and Sigmoid  
Optimizer: Adam  
Loss: Binary Cross-Entropy

Results

The model successfully learns the pattern in the dataset and predicts the class of new data points.
The notebook also shows the accuracy, loss, confusion matrix, ROC-AUC score, and decision boundary.

 Author

Janani M
B.Tech Artificial Intelligence and Data Science  
KalaignarKarunanidhi Institute of Technology, Coimbatore
