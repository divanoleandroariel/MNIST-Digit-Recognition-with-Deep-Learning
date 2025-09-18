# MNIST-Digit-Recognition-with-Deep-Learning

## Model Architecture
- **Sequential Model**:
  - Flatten layer to convert 28x28 images into a 784-dimensional vector
  - Dense hidden layers with ReLU activation
  - Output layer with Softmax activation for classification
- **Loss function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Metrics:** Accuracy

## Training
- Number of epochs: 5
- Batch size: 32
- Achieved **final test accuracy:** ~97.8%
- Loss: 0.0720

## Visualizations
- Training/Validation Accuracy and Loss plots
- Sample images with predicted vs actual labels
- Summary of model layers and trainable parameters

## Future Improvements
- Experiment with **Convolutional Neural Networks (CNNs)** to further increase accuracy (>99%)
- Implement data augmentation to improve generalization
- Test alternative optimizers and learning rates

## Skills Demonstrated
- Python programming
- TensorFlow/Keras for Deep Learning
- Data preprocessing and visualization
- Model evaluation and performance metrics
- Portfolio-ready AI project presentation
