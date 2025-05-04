# IMAGE-CLASSIFICATION-MODEL

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Saheel Pasha

**INTERN ID**: CT04WT62

**DOMAIN**:  Machine Learning

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTOSH

# DESCRIPTION

# What is Image Classification?
Image classification means giving a label to an image.
For example:
If you show a photo of a dog, the model should say "Dog".
If you show a car, it should say "Car".
The computer learns from many example images and figures out patterns.
# What is a CNN?
CNN stands for Convolutional Neural Network. It’s a type of deep learning model that works really well with images.
Imagine your eyes:First, you see colors and edges.Then, you recognize shapes like a nose or ear.Finally, you know it’s a dog.
CNN does the same! It has layers that:Look at edges and shapes.Combine them into parts (like eyes, wheels).Decide what the whole image is.
# What Tools Will be Used?
we can use  Python with some libraries:
TensorFlow or PyTorch – to build the model.
NumPy – to handle data.
Matplotlib – to show graphs and images.
# What Data to Use?
can use the CIFAR-10 dataset. It has:
60,000 small color images
10 types of objects: Airplane, Car, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck
Each image is 32x32 pixels.
# Steps to Do the Task
1. Load the dataset
Use TensorFlow or Keras to load CIFAR-10.
2. Preprocess the images
Make the pixel values between 0 and 1 (normalization).
3. Build the CNN model
Add layers like:
Conv2D – to find patterns in images
MaxPooling2D – to reduce size
Flatten – to turn 2D data into 1D
Dense – to make predictions
4. Compile the model
Choose:
Loss function: categorical_crossentropy
Optimizer: adam
Metric: accuracy
5. Train the model
Use the training data and let the model learn for a few rounds (called epochs).
6. Test the model
Use the test data to see how well your model is doing.
7. Show results
Use graphs to show:
Accuracy (how many were correct)
Loss (how much the model is wrong)
8. Predict new images
Try giving it new images and check what it predicts.
# How to Check if Your Model is Good?
Look at:
Accuracy – Higher is better (above 70% is good for CIFAR-10).
Loss – Lower is better.
Try testing with images yourself
# Summary
This task helps to:
Understand how computers recognize images.
Learn how to build and train a CNN.
Get experience in real-world machine learning.
It’s a cool and important skill if you want to work in AI, computer vision, or data science!
# OUTPUT

