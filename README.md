# Generating-DeepFakes-using-GANs
Deep fake images are synthetic images generated to mimic the looks
of real people or objects images which can be used in entertainment,
education, and other industries. Generative Adversarial Networks
(GANs) have revolutionized the field of deep fake images as they
are designed to learn and replicate the underlying distribution of
the training data. GANs are composed of two neural networks
that are simultaneously trained in a game-theoretic framework:
a generator that generates synthetic images and a discriminator
that distinguishes between the real and the synthetic images generated. The development of numerous GAN designs, each with
specific strengths and drawbacks, has resulted from this adversarial training process. This paper analyses the performance of three
prominent GAN architectures: Vanilla GAN, Deep Convolutional
GAN (DCGAN), and Wasserstein GAN (WGAN) with weight clipping and gradient penalty. We evaluate the performance of these
architectures by implementing them on CelebA dataset. Among
them, WGAN with gradient penalty performed the best followed
by DCGAN, while the Vanilla GAN performed the worst among
all. Our findings highlight the differences and trade-offs among the
three GAN models, offering valuable insights for researchers and
practitioners in the field of image synthesis using GANs.
