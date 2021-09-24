# Robustness-of-CNN-s
## Towards Evaluating the degree of Robustness of CNN's by generation of Adversarial Examples. 

### Measuring the degree of Robustness of Convolutional Neural Networks in classifying images.

<p> The project is aimed at the measurement of the robustness/defensiveness of a convolutional neural network to adversarial examples (images). The idea is to generate slightly distorted images (cited in [1] as attacks to a neural network) and measure the probability of its misclassification. The paper [1] discusses three new attack algorithms tailored to three distance metrics (L0, L2, and Linfinity distances) and uses these as a benchmark to evaluate the defensiveness of a given CNN. I have implemented the L-2 adversarial attack algorithm on top of two convolutional neural networks - a standard network without defense and a defensively distilled neural network. This attack has been considered to one of the most state-of-the-art attacks that even breaks defensive distillation. The attack breaks both networks and successfully generates adversarial images for every (source, target) ordered pair. </p>

Dataset​ : MNIST
Evaluation Metrics​ : L2 distance metric

References:
1. Towards Evaluating the Robustness of Neural Networks authored by Nicholas Carlini & David Wagner, University of California, Berkeley.
2. https://github.com/carlini/nn_robust_attacks
