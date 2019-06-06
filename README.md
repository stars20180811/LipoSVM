# PLSVM
A Predictor based on Support Vector Machine for lysine lipoylation in Proteins 
# Requirements
•Python>=3.6
•Matlab2016a
# File description
1. The file named Algotithm contains python code for different classification algorithms: KNN, Decision Tree, Logistic Regression, Naive Bayes.
2. The file named Encoding schemes contains code for different encoding schemes: PSSM, BPB, AAindex, BLOSUM62, Binary.
3. The file named PLSVM contains code for optimal model.
4. The file named SMOTE contains code for SMOTE.
# Introduction of five encoding method
BPB
BPB is also known as bilateral Bayes algorithm which was proposed by Shao et al. It encodes positive and negative samples with the position information of amino acids.

Physicochemical and biochemical properties
AAindex is a database of numerical indices representing various physicochemical and biochemical properties of amino acids and pairs of amino acids

Position-specific scoring matrix (PSSM)
To get information of sequential evolution, the position-specific scoring matrix can be utilized. 

BLOSUM62 matrix
BLOSUM matrices have belonged to the most common substitution matrix series for protein homology search and sequence alignments since their publication in 1992. Essential characters of protein evolution can be learned from analysis of aligned protein sequences.

Binary
The amino acids within a small range around the acetylation site are primary sequence features and have proven to be useful information for lysine acetylation sites prediction in previous studies.These features can be used to represent protein sequences.

# Flowchart of PLSM
![image](https://github.com/stars20180811/PLSVM/blob/Image/Figure%201.jpg)

# Result
![image](https://github.com/stars20180811/PLSVM/blob/Image/Figure%202.jpg)
![image](https://github.com/stars20180811/PLSVM/blob/Image/Figure%203.jpg)
![image](https://github.com/stars20180811/PLSVM/blob/Image/Figure%204.jpg)
![image](https://github.com/stars20180811/PLSVM/blob/Image/Figure%205.jpg)




