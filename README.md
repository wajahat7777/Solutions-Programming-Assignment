# Solutions-Programming-Assignment
This repository contains my solutions to the Scientific Programming admission assignments for the Master's Programme in Computer Vision & Data Science (2027–2028) at NHL Stenden University of Applied Sciences.

The assignments focus on Python programming, debugging, NumPy operations, data visualisation and understanding the behaviour of machine learning code. Each exercise includes the corrected implementation and an explanation of the identified issues and solutions.

Assignments

Exercise 1: Fruit Indexing and Python Data Structures

Identified why Python sets cannot be accessed using numerical indices.

Replaced the unordered set with an ordered list.

Implemented index validation to handle invalid fruit IDs.

Added verification tests for expected results.

Concepts: Python data structures, indexing, type hints and error handling.

Exercise 2: NumPy Coordinate Swapping

Identified incorrect column indexing in a coordinate array.

Corrected the swapping of x and y coordinates.

Used NumPy advanced indexing to avoid unintended overwriting.

Preserved the original input array by working on a copy.

Concepts: NumPy arrays, array indexing, memory views and copying.

Exercise 3: CSV Data Processing and Visualisation

Identified the issue caused by reading numerical CSV values as strings.

Converted the loaded data into a numerical NumPy array.

Corrected the plotting coordinates and axis labels.

Used Matplotlib to visualise precision and recall values.

Concepts: CSV processing, NumPy, numerical data conversion and Matplotlib.

Exercise 4: Generative Adversarial Network (GAN) Debugging

Investigated a batch-size mismatch during GAN training.

Corrected the generation of labels and latent noise for variable batch sizes.

Fixed the condition for displaying generated images at the end of each epoch.

Improved figure handling and corrected plotting labels.

Concepts: Python, PyTorch, neural networks, batch processing and GAN training.

Technologies and Libraries

Python

NumPy

Matplotlib

PyTorch

Torchvision

CSV
