In this chapter I am testing and experimenting with some unsupervised learning technics like:</br>
</br>
- Generative Adversarial Networks (GANs)</br>
- Autoencoder</br>
- K-mean clustering</br>
</br>
GENERATIVE ADVERSARIAL NETWORKS (variational encoder) have been used in many different applications to   </br>
generate realistic synthetic data. I saw that this technic works quite well if we have a huge collection   </br>
of pictures for the tandem training, and if the pictures are quite similiar, for example they are just human   </br>
 faces. I was curious how the model performs if we have a small amount of pictures and if the object's or   </br>
objects' position on the images are varying. I tested the model created in Pytorch on 210 dolphin images.</br>
</br>
AUTOENCODERS are a specific type of feedforward neural networks where the input is the same as the output. </br>
They compress the input into a lower-dimensional code and then reconstruct the output from this  </br>
representation. It can be used as solution for several problems, e.g. anomaly detection. Now I </br>
just created a quite simply model using. Tensorflow to check, how the model performs on a small</br>
amount of images.</br>
</br>
K-MEAN CLUSTERING</br>
</br>
The objective of K-means is simple: group similar data points together and discover underlying patterns.</br>
I use this algorithm in the "ML technics in Sales and Markeitng" chapter as well.
