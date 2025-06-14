# Lab_FMNISTWithPytorch

Fashion MNIST, often abbreviated as FMNIST, is a popular dataset designed for benchmarking machine learning algorithms in the context of multi-class classification tasks. 

This lab enhancement focuses on addressing the FashionMNIST dataset, a widely recognized multi-class classification problem in the field of machine learning. The primary objective is to explore and utilize Pytorch develop a computer vision neural network capable of accurately identifying and categorizing various styles of clothing represented in the dataset. By delving into this problem, we aim to understand the process of building, training, and evaluating neural network architectures tailored for image classification tasks. The lab enhancement explores three different types of models: the baseline model featuring linear layers, Model 2, which builds on the baseline by adding a ReLU activation layer, and Model 3, a convolutional neural network (CNN). Additionally, you'll gain hands-on experience with PyTorch, learning to utilize its libraries for various tasks, such as transforming tensors, loading datasets, leveraging nn.Module to build models, and using it for evaluation and predictions.

### Table Of Contents
- 1.0 Install and Import Libraries
- 2.0 Load Datasets
- 3.0 Data Visualization
- 4.0 DataLoader
- 5.0 Model 0: Baseline Model
   - 5.1 Setup loss, optimizer and evaluation metrics
   - 5.2 Pytorch Training loop
   - 5.2 Pytorch Testing loop
- 6.0 Model 1: Non-linearity Model
- 7.0 Model 2: Convolutional Neural Network (CNN)
    - 7.1 Understand Convolutional layer
    - 7.2 Understand Max Pooling layer
- 8.0 Model Evaluation
- 9.0 Make Predictions