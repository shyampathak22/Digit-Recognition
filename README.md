# Digit-Recognition
This program aims to utilize a Convolutional Neural Network (CNN) in order to recognize custom handwritten digits. The network is trained using the classic MNIST dataset, and leverages the strong image and pattern recognition capabilities of CNN's in order to be able to intake the user's hadnwritten digits as well and recognize them with high accuracy. The image files are labeled 1_1.jpg, 1_2.jpg, and so on. The first number in the name of the image file is the digit displayed within the file, while the second is an identifier of which version of the digit image has been selected. For example, 2_1.jpg is the first image entry for the digit '2', whike 2_2.jpg is the second entry for the digit '2'. Both digits were written in different formats, as can be seen when opening the files. This was done to test the network's ability to actually recognize a handwritten input, rather than just testing on the MNIST set. The 'epochs' has been set to a low value in this file (10) so that it can be easily and more rapidly tested. Using a higher number of epochs (100+) will provide a much higher accuracy (>99.5%). The decision to use a CNN for this project came after a regular neural network from PyTorch was used. This network was only able to reach an accuracy of about 7.5% on the handwritten digits. The very first iteration of the CNN already did significantly better, reaching an accuracy of 61.25%. Thus, the CNN was utilized and parameters were altered until the accuracy was above 85%.
