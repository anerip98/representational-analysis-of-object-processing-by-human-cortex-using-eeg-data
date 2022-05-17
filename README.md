# Representational Analysis of Object Processing by Human Cortex using EEG Data

Work in this notebook is based on "A Representational Similarity Analysis of the Dynamics of Object Processing Using Single- Trial EEG Classification". How the human brain responds to various inputs from the vision cortex is analyzed using EEG data.

The recognition of object categories is effortlessly accomplished in everyday life, yet its neural underpinnings remain not fully understood. As a part of a project for a course in Machine Learning for Data Mining, we performed single-trial classification to perform a Representational Similarity Analysis (RSA) of categorical representation of objects in human visual cortex using EEG.

The work done in this notebook is aimed at reproducing a fraction of the results in "A Representational Similarity Analysis of the Dynamics of Object Processing Using Single- Trial EEG Classification" using deep learning techniques instead of LDA and SVM-RBF that are proposed in the paper.
Data

Brain responses were recorded while participants viewed a set of 72 photographs of objects with a planned category structure.
Data (X_3D): 124(channels or features) x 32 (time points) x 5188(trials)
Classification Labels: 1 x 5188 (trials)

# Method
  * Binary classification using artificial neural networks to identify whether the stimulus is a human face or an inanimate object at each time step.
  * Multiclass classification (6 classes - ...) using artificial neural networks at each time step.

# Conclusions:

The data analysis revealed that brain responses to images of human faces formed the most distinct category while responses to images from the two inanimate categories formed a single category cluster.
