# PyTorch

- PyTorch is an open source machine learning library for Python and is completely based on Torch. 
- It is primarily used for applications such as deep learning and neural network modeling.
- PyTorch redesigns and implements Torch in Python while sharing the same core C libraries for the backend code.
- PyTorch developers tuned this back-end code to run Python efficiently, including GPU hardware acceleration and extensibility.

## Neural Networks

Neural networks provide solutions to many complex problems like classification and predictive modeling.
- PyTorch is one of the leading deep learning frameworks, being both powerful and easy to use.
- Neural networks are a set of algorithms designed to recognize patterns, modeled after biological neural networks.
- The networks consist of individual units called neurons, each having weighted inputs.
- These weighted inputs are summed together and passed through an activation function to generate the output.

## Training Process Neural Nets

A typical training procedure for a neural network implemented in this project includes:
- Defining the neural network with learnable parameters and weights.
- Iterating over the dataset in batches.
- Processing inputs through the network layers.
- Computing the loss using specific criteria.
- Backpropagating gradients into the network parameters.
- Updating the weights using an optimizer.

## Code Description

    File Name : engine.py
    File Description : Main script developed and structured to orchestrate the execution flow of data processing and model training.

    File Name : preprocessing.py
    File Description : Custom data preprocessing module handling data cleaning, encoding, scaling, and splitting.

    File Name : pytorch_NN.py
    File Description : PyTorch neural network architecture and training logic implementation.

## Steps to Run

The project is built and structured modularly for local execution.

1. Create and activate a virtual environment:
    - For Linux and macOS:
        python3 -m venv venv
        source venv/bin/activate
    - Alternatively, using the uv package manager:
        uv pip install -r requirements.txt

2. Install project requirements:
    python -m pip install --upgrade pip
    pip install -r requirements.txt

## Execution Instructions

To run the pipeline locally:
- Activate your virtual environment.
- Navigate to the src directory.
- Run the engine script:
    python engine.py
    (or using uv: uv run python engine.py)