# Bioisostere-prediction-using-deep-learning
<b>Prediction of Bioisostere using deep learning method<b>

<b>Theme: Bioisostere prediction using deep learning <b>

<b>Dataset: Dataset extracted from ChEMBL database. Dataset containing each substituent’s SMILES structure and 20 similar analogues.<b>

<b>Data science approaches<b>

<b>Generation of Training matrix X<b>

Using Rdkit python cheminformatic library to calculate each substituent’s molecular descriptor as well as each’s analogues 

Reduce the dimensionality of molecular descriptors by Principal component analysis method(PCA)

<b>Generation of Training matrix Y <b>

Multi-hot encoding: the positions corresponding to the analogues of the parent substituent were marked as 1, other positions remained 0) 

<b>Deep learning prediction model<b>

Using X as an input, and Y as an output, implement the deep neural network model based on the Tensorflow Keras framework. 
tested several architectures. Validate the model accuracy by leave-out-cross-validation!
