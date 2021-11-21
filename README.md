# Handwritten-Digits-Generation
A DCGAN model to generate some handwritten digits trained on the MNIST dataset(70,000).

## About
GANs consist of two neural networks, a
generator and a discriminator, playing a game of cat and mouse. The generator creates new
data from by drawing from and manipulating a noise distribution, while the discriminator
distinguishes between generated and real data drawn from a target distribution. Through
this adversarial process, the generator learns to produce structurally realistic images, and the
discriminator learns to distinguish real vs. fake, until the latter can no longer make confident
distinctions.

## Modules Used:
1.) Numpy<br>
2.) Matplotlib<br>
3.) Tensorflow
<br>
## Optimizer Used:
Adam Optimizer

## Loss Function
Loss Funtion:Binary CrossEntropy
