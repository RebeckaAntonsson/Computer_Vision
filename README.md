# Computer_Vision
Three projects in computer vision that I carried out during my master program\
\
# CNN_happy_sad project
This is a smaller convolutional neural network that i built independently\
The network have been trained on ~10 photos of me that are either happy or sad, with the goal to distinguish the two emotions.\
\
## Model
- Two convolutional layers
- LeakyReLU activation
- Flatten + fully connected output layer
- Softmax classification
- Adam optimizer
- Categorical cross-entropy loss

## Data preprocessing
- Face cropping
- Grayscale conversion
- Resize
- Normalization

## Evaluation
- Train/test split
- Test accuracy
- Example predictions
- Visualization of learned convolutional filters

## Results
Test accuracy 85.7%

## Technologies
Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib


# Neural network built from scratch
This is a notebook where most of the initial implementation was provided as course material in BERN02. My work focused on running and understanding the implementation, writing comments, interpreting the different components of the neural network, experimenting with the provided code, and making modifications where appropriate.
