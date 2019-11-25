# Robustness-of-CNN-s
Towards Evaluating the degree of Robustness of CNN's by generation of Adversarial Examples. 

Title of project​ : Measuring the degree of Robustness of Convolutional Neural Networks in
classifying images.

Problem statement​ : The project is aimed at the measurement of the vulnerability of a
convolutional neural network to adversarial examples (images). For instance, given an input x,
and any target classification t, it is possible to find a new input x’ that is similar to x but is
classified as t. The idea is to generate slightly distorted images (cited in [1] as attacks to a neural
network) and measure the probability of its misclassification. The paper [1] discusses three new
attack algorithms tailored to three distance metrics (L0, L2, and Linfinity distances) and uses
these as a benchmark to evaluate the defensiveness of a given CNN. I am looking forward to
implementing these image distortion algorithms and measuring the robustness/defensiveness of a
CNN to these distortions thereafter.

Dataset​ : MNIST and/or CIFAR10
Evaluation Metrics​ : L2 distance metric & demonstration of the failure of transferability [1].

References:
1. Towards Evaluating the Robustness of Neural Networks authored by Nicholas Carlini & David Wagner, University of California, Berkeley.
