# Bladder-cancer-prediction
Aim: To apply Machine learning algorithms for the classification of various stages of bladder Cancer (BCa) patients based on RNA-Seq TPM gene counts data and its corresponding pathological stages from the TCGA database, and to ascertain the classification performance between different stages.

 Design/Methodology/Approach: From the TCGA database, the data category as "Transcriptome Profiling", data type "Gene Expression Quantification", and experimental strategy "RNA-Seq” of BCa were downloaded and the transcriptome per million (TPM) as the gene count matrix with American Joint Committee on Cancer (AJCC) pathological stages as label data. A forward feature selection technique was used to select the best features for ML classifiers in conjunction with 3-fold nested cross-validation (nCV), which was performed using binary classification with various machine learning algorithms.
 
Limitation: NGS experimental design might not be the same for all type of bladder cancer stages

Findings: This research revealed new insights that the application of ML classification techniques can be used to predict cancer stages based on RNA-Seq TPM count data and corresponding clinical pathological stages.

Practical Implication: The research presents a better approach that can be used in classifying the stages of bladder cancer (BCa) and other cancer types, using TPM count data as input and AJCC pathological stages as target labels for the benefit of bladder cancer treatment.


