# Conversion of PyTorch models to ONNX for use with Mathematica

This repository contains 2 notebooks demonstrating the conversion of PyTorch neural network models to ONNX format for usage with Mathematica. For demonstration, the model ResNet18 is used in this module.

https://huggingface.co/microsoft/resnet-18

Download the model and configuration files and put them in a new directory called `resnet18` in this directory.

**Note: For conversion from PyTorch model to ONNX model, a dummy input is required in order to estimate an approximate computation graph of the network. This causes the ONNX model to give slightly offset results in comparison to the original network.**
