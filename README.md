# Thesis-Msc
### Title: Neural architectural patterns for Vision Tasks
This Thesis introduces the concept of "neural patterns" or simply "patterns" in the neural architecture for Vision Tasks. The neural architecture for Convolutional Neural Networks (CNNs) for GPU-based systems as well as CNNs tailored for edge devices are analysed. Their ONNX models are fetched under ONNX_model file and the underlying patterns are extracted under ONNX_Patterns. The current repo contains the following implementations:

ONNX Extractor: This contains ONNX Python API to extract the relevant layers in the ONNX model to extract patterns.
Feature Extractor: This contains the implemenation of specified features: Node Type(s)- Split, Clip, Concat, Add, Connection links - Skip, parallel, Sequential and Dense,and Layer Type(s).
Automated Decision Tree: This contains the Automated decision tree that uses the features as the input to provide the name of the pattern as output.

