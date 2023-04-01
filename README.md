# Metric_Learning
Metric Learning for Face Identification

# Introduction
The Metric Learning method is a machine learning technique that aims to learn a distance function that can measure the similarity between two data examples. It is often used in classification and pattern recognition problems, including face identification.

# Concepts
The goal of Metric Learning is to learn a distance function that can measure the similarity between two data samples, so that similar samples have a smaller distance than dissimilar samples. The method uses pairs of training examples to learn this function, where a pair is composed of two samples that are either similar or dissimilar. The model learns to optimize a distance metric, such as Euclidean distance, in order to minimize the distance between similar samples and maximize the distance between dissimilar samples.

In face identification, Metric Learning can be used to learn a distance function that can measure the similarity between two facial images. This is useful for the task of face recognition, where the goal is to identify whether two facial images belong to the same person. The Metric Learning method can be used to learn the distance between facial features extracted from each image, so that images of the same individual have more similar facial features than images of different individuals.

# Usage in Face Identification
Metric Learning has been widely used in face identification applications, including real-time face recognition systems and large-scale face recognition systems. The method is often combined with feature extraction techniques, such as Deep Learning, to learn a robust representation of facial features. Then, the learned distance function can be used to measure the similarity between the facial features of two images and identify whether they belong to the same person.

# Conclusion
Metric Learning is a useful method for face identification and other pattern recognition applications. It allows for learning a distance function that can measure the similarity between two data samples, which is particularly useful for the task of face recognition. Combined with feature extraction techniques, Metric Learning can be used to learn a robust representation of facial features and measure the similarity between them.

However, despite all of us having unique features on our faces, the Covid-19 pandemic brought a major problem for facial recognition models: face masks. Covering an important part of our face, from which deep learning models extracted features to compute the descriptor vector, facial recognition models presented a high rate of failures. Some solutions have been found to overcome this problem. The proposed solution will follow these steps:

1 - Train a neural network model on the "post-processed.zip" dataset (the dataset contains a wide variety of celebrities).
2 - Once the model is trained, you should create a database with images of the celebrities and the output of the descriptor vector from your model.
3 - After training the neural network, you should include the person "Davi" without a mask in the database.
4 - Once steps (1), (2), and (3) are completed, you should use the image of the person "Davi" from item (3) wearing a face mask and perform facial recognition on it.
