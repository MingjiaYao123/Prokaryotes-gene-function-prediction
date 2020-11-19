# Prokaryotes gene function prediction
Goal:
To predict the function of the genes of some not well-studied prokaryotes genomes by machine learning on the genomes of some well-studied and annotated prokaryotes. In this project, classifiers for predictions will be trained by E. coli genome.

Approach:
Use the the annotated genome of E coli (Escherichia coli str. K-12 substr.) as training set.
Train the classifiers for 7 different functional categories of proteins with E-coli genome, and then we can use the classifiers to predict whether a gene has this function. Use the number of times each amino acid k-mer occurs in protein sequences as features for the classification.
Using SVM and Logistic regression as the methods.

In this directory, the file 'transcpirtional_classifier.ipynb' shows how the prediction algorithm works in the "transcriptional" function genes, with E. coli genome as training set and Granulosicoccus antarcticus genome as the test set. The file 'M225FinalReport_Yao.docx' is the report of this project.
