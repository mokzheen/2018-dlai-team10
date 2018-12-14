# Deep Learning for Artifitial Intelligence (DLAI) Project
Group 10: M. Alonso, M. Busquets, P. Palau, C. Pitarque

GitHub project page: [...]

# Quick, Draw! Doodle Recognition Challenge
Our project consists on trying different approaches for *Kaggle's Quick, Draw! Doodle Recognition Challenge*.

Quick, Draw! is a game that was created in 2016 to educate the public in a playful way about how AI works. The basic idea of the game is that it tells the player a simple concept (such as banana, apple...) and he/she has to draw it in a certain amount of time. While the player is drawing, the AI [...]

However, since the training data comes from the game itself, drawings can be incomplete or may not match the label. The challenge consists on building a recognizer that can effectively learn from this noisy data and perform well on a manually-labeled test set from a different distribution.

Competition link: https://www.kaggle.com/c/quickdraw-doodle-recognition


The main objective of this project was for us to deeply understand the concepts and implementations of various Deep Learning models studied in the course. [...]


# Models
We decided to evaluate three different approaches of increasing difficulty and performance: a Multilayer Perceptron (MLP), a Convolutional Neural Network (CNN) and a Recurrent Nerual Network (RNN). 

For the first two approaches (MLP and CNN) we used the simplified dataset, in which the simplified drawings have been rendered into a 28x28 grayscale bitmap in numpy .npy format. While for the RNN, [...]

# Results
Results [...]

The evaluation of the challenge is performed according to the Mean Average Precision @ 3 (MAP@3): MAP@3=1U∑u=1U∑k=1min(n,3)P(k)
where U is the number of scored drawings in the test data, P(k) is the precision at cutoff k, and n is the number predictions per drawing.

The current leader of the competition has a score of 0.95480. However, our results can not be compared to this because we have not implemented our models neither used all the data that the challenge requested. 


# Conclusions
Conclusions [...]
