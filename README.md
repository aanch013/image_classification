# Image Classification

In this project, I designed, trained, and evaluated a convolutional neural network (CNN) to classify images from the CIFAR-10 dataset, which contains 60,000 32x32 color images, belonging to 1 of 10 object categories, such as airplane, automobile, bird, and cat. I began by preprocessing the data, which included normalizing the image pixel values, and one-hot encoding class labels. I then defined the function visualize_data() which displayed the training images with their corresponding labels. After that, I built and compiled the CNN model, while tracking accuracy to evaluate the model's performance. I also implemented a training loop that shuffled the training data for each epoch, and calculated the loss and accuracy on the test set after each epoch. I observed consistent improvement in the CNN model's performance, which, in the end, reached about 53.6% training accuracy and approximately 63.1% validation accuracy.

Results:

<img width="390" alt="Screen Shot 2025-04-29 at 11 56 16 AM" src="https://github.com/user-attachments/assets/d9a1085b-ecf5-4f19-992b-4297837eeb8a" />


Dataset: https://www.cs.toronto.edu/~kriz/cifar.html (file too large to upload)
