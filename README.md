In this chapter I am testing and experimenting with some unsupervised learning technics like:</br>
</br>
- Generative Adversarial Networks (GANs)</br>
- Autoencoder</br>
- K-mean clustering</br>
</br>
GENERATIVE ADVERSARIAL NETWORKS (variational encoder) have been used in many different applications to generate realistic synthetic</br>
data. I saw that this technic works quite well if we have a huge collection of pictures for the tandem training, and if the pictures are</br>
quite similiar, for example they are just human faces. I was curious how the model performs if we have a small amount of pictures </br>
and if the object's or objects' position on the images are varying. I tested the model created in Pytorch on 210 dolphin images.</br>
</br>
AUTOENCODERS are a specific type of feedforward neural networks where the input is the same as the output. They compress the input into</br>
a lower-dimensional code and then reconstruct the output from this representation. It can be used as solution for several problems, e.g.</br>
anomaly detection. Now I just created a quite simply model using Tensorflow to check, how it performs on a small amount of images.</br>
</br>
K-mean clustering</br>
