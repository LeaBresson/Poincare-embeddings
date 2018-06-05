# Poincare-embeddings
Project for the course "Geometric Machine Learning" at ENSAE ParisTech (lecturer: Marco Cuturi)

## Contents
Implementation of the algorithm introduced in 2017 by Maximilian Nickel and Douwe Kiela in the paper "*Poincaré Embeddings for Learning Hierarchical Representations*". I made slight modifications in order to improve the algorithm based on the blog post https://rare-technologies.com/implementing-poincare-embeddings. 

## Findings
To conclude learning embeddings in a hyperbolic plane, rather than Euclidean space, allows to capture not only semantic, but also hierarchical structure of the data. This improves the quality of the learned representations while also reducing the number of dimensions needed to obtain a good representation. My implementations suggest that traditional optimization approaches such as SGD or Adam converge faster and give similar results as a full Riemannian optimization approach.

## Author 
Léa Bresson (lea.bresson@polytechnique.edu)
