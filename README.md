# Bioisostere-prediction-using-deep-learning
Prediction of Bioisostere using deep learning method

Theme: Bioisostere prediction using deep learning 
Dataset: Dataset extracted from ChEMBL database. Dataset containing each substituent’s SMILES structure and 20 similar analogues.
Data science approaches 
Generation of Training matrix X 
Using Rdkit python cheminformatic library to calculate each substituent’s molecular descriptor as well as each’s analogues 
Reduce the dimensionality of molecular descriptors by Principal component analysis method(PCA)
Generation of Training matrix Y 
Multi-hot encoding: the positions corresponding to the analogues of the parent substituent were marked as 1, other positions remained 0) 
Deep learning prediction model 
Using X as an input, and Y as an output, implement the deep neural network model based on the Tensorflow Keras framework. 
tested several architectures. Validate the model accuracy by leave-out-cross-validation!
