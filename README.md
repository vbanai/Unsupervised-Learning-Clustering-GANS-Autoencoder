In this chapter I am testing and experimenting with some unsupervised learning technics like:</br>
</br>
- Generative Adversarial Networks (GANs)</br>
- Autoencoder</br>
- K-mean clustering</br>
</br>
GENERATIVE ADVERSARIAL NETWORKS (variational encoder) have been used in many different applications to generate  </br>
realistic synthetic data. I saw that this technic works quite well if we have a huge collection of pictures for  </br>
the tandem training, and if the pictures are quite similiar, for example they are just human faces. I was curious   </br>
how the model performs if we have a small amount of pictures and if the object's or objects' position on the images  </br>
are varying. I tested the model created in Pytorch on 210 dolphin images.</br>
</br>
AUTOENCODERS are a specific type of feedforward neural networks where the input is the same as the output. They </br>
compress the input into a lower-dimensional code and then reconstruct the output from this representation. It can </br>
be used as solution for several problems, e.g. anomaly detection. Now I just created a quite simply model using Tensorflow  images.</br>
to check, how it performs on a small amount of</br>
K-mean clustering</br>
