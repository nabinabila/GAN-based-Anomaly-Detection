# GAN-based-Anomaly-Detection

# Overview of GAN
Generative Adversarial Networks (GAN) introduced by Goodfellow is considered as one of the most powerful member of the neural network family, due to realistic data generation capacities.
As showen in figure GANs operate by training two competing networks: a generator and a discriminator. The generator produces realistic synthetic samples from noise (the z-latent space), while the discriminator discerns between genuine and synthetic samples. This flexible architecture has been utilized for tasks like identifying the location of vertebrae, discs, and spinal shape.
![unnamed (3)](https://github.com/nabinabila/Vertebral-Deformities-Diagnosis-based-on-Deep-Learning/assets/52214161/03afe3e0-e2bd-46f0-b622-1f67bc4e7683)

# Requirements
The main requirements are listed below:

Tested with Keras 2.3.1

Python 3.6

OpenCV 3.4.2

scikit-image 0.16.2

Numpy

Scikit-Learn

Matplotlib

# Dataset
MURA Dataset Public, detect abnormality in X-Ray images.
Provided by: https://stanfordmlgroup.github.io/competitions/mura/

Rib Fracture Detection , provided by : https://ribfrac.grand-challenge.org/tasks/

xVertSeg Dataset provided by: public SpineWeb (http://spineweb.digitalimaginggroup.ca)
