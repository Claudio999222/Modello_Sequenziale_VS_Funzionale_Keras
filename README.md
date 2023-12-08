# Sequential vs Functional Models in Keras

In this notebook, we explore the two primary ways of creating neural network models in Keras: Sequential and Functional models. Both approaches offer flexibility and are suitable for different scenarios.

## Sequential Model:

- **Linear Stack of Layers**: The Sequential model represents a linear stack of layers where each layer has exactly one input tensor and one output tensor.
- **Simplicity**: Well-suited for simple, linear architectures where each layer follows the previous one.

## Functional Model:

- **Graph-like Structure**: The Functional API allows for creating models with more complex architectures, including multiple inputs and outputs and shared layers.
- **Flexibility**: Ideal for building models with branched or merged architectures, enabling the creation of more intricate neural networks.

## Core Concepts Explored:

- **Dense Layers**: Fully connected layers for information propagation.
- **Activation Functions**: Introducing non-linearity to the model.
- **Model Compilation**: Defining the optimizer, loss function, and evaluation metrics.
- **Model Training**: Utilizing training data to optimize model parameters.
- **Model Evaluation**: Assessing the model's performance on test data.

## Use Cases:

- **Sequential Model**: Suitable for straightforward, linear architectures, such as feedforward neural networks.
- **Functional Model**: Appropriate for complex architectures involving multiple inputs/outputs or shared layers, such as multi-input models or models with residual connections.

By comparing these two approaches, this notebook aims to provide insights into choosing the most appropriate model creation method based on the complexity of the neural network architecture.
