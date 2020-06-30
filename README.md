# RBM-Gene-Network
Bidirectional RBM has been used for two way communication to draw gene network

The phenomenon of two or more genes affecting the expression of each other in various ways in the development of a single character of an organism is known as gene interaction. Most of the characters in the living organism are governed by collaboration of several different genes. These patterns of gene interaction not only apply to normal human traits but to the diseased samples as well. Many human diseases are the result of mutation in multiple genes. Thus analysis of gene interaction could help us to differentiate between the normal and the diseased samples or between the two/ more phases any diseased samples. At the first stage of this work we have used Restricted Boltzmann Machine (RBM) model to find such interactions present in normal and/ or cancer samples of every gene pairs of 20 genes of colorectal cancer dataset (GDS4382) selected from NCBI database along with the weight/ degree of those interactions. In the second stage, we are looking for those interactions present in adenoma and/ or carcinoma samples of the same 20 genes of colorectal cancer dataset (GDS1777). What interests us in this work is to identify those  significant interactions responsible for colorectal cancer disease or the different phases of this cancer disease to take place. The weight/ degree of those interactions represent how strong/ weak an interaction is. At the end we will create a gene regulatory network (GRN) with the help of those interactions, where the regulatory genes are identified by using Naïve Bayes Classifier (NBC). Experimental results are validated biologically by comparing the interactions with NCBI database.

There are two program files Gene_Network.ipynb and Gene_Network_Diseased.ipynb are use to compute the gene-gene interactions for Normal Genes and Diseased Genes respectively.
