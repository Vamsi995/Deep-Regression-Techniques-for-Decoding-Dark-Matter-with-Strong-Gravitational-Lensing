# Deep-Regression-Techniques-for-Decoding-Dark-Matter-with-Strong-Gravitational-Lensing


## Getting Started

These are developed on google colab and have been downloaded as .ipynb files. So apologies for using colab directory paths in the code.

### Prerequisites

The drive link for the data and the model weights - https://drive.google.com/drive/folders/1zB1d1FmBObQWcateWo7Tlh9TOFohHshs?usp=sharing


# Theory

## About Gravitational Lensing

One of the consequences of general relativity is massive objects (such as a cluster of galaxies) lying between a more distant source (such as a quasar) and an observer should act as a lens to bend the light from this source. The more massive an object, the more lensing is observed.

Strong lensing is the observed distortion of background galaxies into arcs when their light passes through such a gravitational lens. By measuring the distortion geometry, the mass of the intervening cluster can be obtained. In the dozens of cases where this has been done, the mass-to-light ratios obtained correspond to the dynamical dark matter measurements of clusters.

![](/images/gravlens.jpg)
![](/images/lensing1.jpg)

## About Dark Matter

Visible matter in the universe only forms a very small fraction of all the matter in the universe. There is about six times more matter than what we can see, but except it is hidden/invisible. This invisible matter is dark matter. Dark matter does not interact with electro magnetic fields, i.e it does not absorb, reflect, or emit electromagnetic radiation. Hence it is difficult to detect but its only interaction is through gravity. Hence we can gain more evidence through the CMB, strong lensing, rotaion curves of galaxies etc,..,.

From the studies of [Vera Rubin](https://www.researchgate.net/publication/333131297_Vera_Rubin_and_the_hypothesis_of_dark_matter_existence) it is concluded that most of the dark matter form a halo around the galaxy.

![](/images/halo.jpeg)

## Dark Matter and Strong Lensing

One of the observational evidence of dark matter is through strong galay - galaxy graviational lensing. The light from the background galaxy is also distorted due to the gravitaional effects of dark matter which distorts space. Hence with this effect, we can try to study the dark matter substructure through its lensing effects.

[The dark matter of gravitational lensing](https://arxiv.org/pdf/1001.1739.pdf)

![](/images/halolens.png)


## Dark Matter Substructure

The bigger dark matter envelope might have some smaller subhalos which consists of even smaller substrucures making these subhalos.

One of the distinguising features among all the types of dark matter proposed comes with the substructure these types can create. Different types of dark matter models have different substructure. WIMP DM forms spherical subhalos, where as wam and hot DM tend to wash out substrucuture on small scales.

Superfluid and condensate dark matter form some exotic substructure having one dimesional line densities called vortices and two dimensional disks.


## Regression Approach

For the regression part I have first made a Deep Multi Layered Perceptrona (MLP) and then trained the given data, after preprocessing the data appropriately. And my second approach was similar to what was mentioned in most of the papers, where they trained ResNet18 on the simulated images for classification tasks. But i slightly tweaked the model to make use of it for regression and hence trained it on a limited number of epochs over the entire dataset after preprocessing and data augumentation.


# Built With

* [PyAutoLens](https://pyautolens.readthedocs.io/en/latest/) - PyAutoLens is open source software for the analysis and modeling of strong gravitational lenses.
* [Python](https://www.python.org/) - Programming Language
* [PyTorch](https://pytorch.org/) - Deep Learning Framework

