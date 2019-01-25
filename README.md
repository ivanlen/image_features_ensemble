## Ensembling images and features using fit generator

In this notebook see how to generate a NN that is feeded with multiple inputs. In particular is feeded with a features vector and with images.
We generate a network that ensembles features with images for a classification problem.

The main idea is to show how to :

* ensemble CNN with other architectures to train a network using images and features together.
* implement a fit generator with multiple inputs.

The dataset consists on features a and images of leaves from 99 different plants from a [Kaggle contest](https://www.kaggle.com/c/leaf-classification) and the idea is to generate a classifier:

> The objective of this playground competition is to use binary leaf images and extracted features, including shape, margin & texture, to accurately identify 99 species of plants. Leaves, due to their volume, prevalence, and unique characteristics, are an effective means of differentiating plant species. They also provide a fun introduction to applying techniques that involve image-based features.

In this notebook we discuss some points about the implementation and procedures.
