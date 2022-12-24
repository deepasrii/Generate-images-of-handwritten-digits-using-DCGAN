# Generate-images-of-handwritten-digits-using-DCGAN

Here, the code generate images of handwritten digits using a Deep Convolutional Generative Adversarial Network (DCGAN).

GAN has two models called Generator Model and Discriminator Model where the two models are trained simultaneously by an adversarial process. A generator learns to create images that look real, while a discriminator learns to tell real images apart from fakes.

The MNIST dataset is used to train the generator and the discriminator. The generator will generate handwritten digits resembling the MNIST data. 

The generator uses tf.keras.layers.Conv2DTranspose (upsampling) layers to produce an image from a seed (random noise). The generator is used to create an image.

The discriminator is a CNN-based image classifier. The discriminator is used to classify the generated images as real or fake. The model will be trained to output positive values for real images, and negative values for fake images.

