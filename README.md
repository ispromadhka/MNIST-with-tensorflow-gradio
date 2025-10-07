# MNIST Handwritten Digit Recognition with TensorFlow and Gradio
This is an illustration of how a lightweight tensorflow model can interact with gradio.



This repository contains a project for building and deploying a Convolutional Neural Network (CNN) for the classification of handwritten digits from the MNIST dataset. The model is built using TensorFlow/Keras and is served through an interactive web interface created with Gradio.

### Expected Training Time

The training duration is dependent on the available hardware. Below are performance estimates:
*   **CPU**: Approximately 5 minutes.
*   **GPU**: Less than 2 minutes.
*   **TPU**: Approximately 3.5 minutes.

### Training Configuration

To modify the training duration and performance, you can adjust the `epochs` and `batch_size` parameters within the `model.fit()` function call in the notebook. Increasing the `batch_size` or decreasing the `epochs` can shorten the training time.
