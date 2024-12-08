# Amino-Acid-Sequence-Function-Prediction

ABSTRACT :

The prediction of protein functions from amino acid sequences is pivotal for advancements in
biotechnology, drug discovery, personalized medicine, and genomics. In this project, we aim to
predict biological functions of proteins using the CAFA 5 Protein Function Prediction dataset.
Employing TensorFlow and ProtT5 embeddings, we tackle the challenge of multi-label classification
by predicting 5,000 protein functions, selected due to computational constraints. Pre-trained ProtT5
embeddings provided by Sergei Fironov are utilized, bypassing the need for large-scale embedding
computation. The model is trained using a V100 GPU for 20 epochs, leveraging binary cross-entropy
loss and metrics like binary accuracy and AUC to assess performance. A validation split of 20% is
applied to evaluate the model’s generalization on unseen data.


PLAN OF ACTION :

1) What will you implement?
In this project, we will implement a protein function prediction model using TensorFlow and
ProtT5 embeddings. The goal is to predict the biological functions of a protein given its
amino acid sequence. By utilizing pre-trained embeddings from the ProtT5 model, we can
bypass the resource-intensive step of embedding computation and focus on building and
training a multi-label classification model. This model will be trained to predict 5,000 protein
functions from the CAFA 5 dataset, using binary cross-entropy as the loss function and
metrics like binary accuracy and AUC to assess performance.

2) What methods are you going to compare and how will you get them?
We will compare the performance of the protein function prediction model using ProtT5
embeddings with other potential models or approaches, such as models using different embedding
techniques or baseline classifiers. These comparisons will focus on metrics like binary accuracy and
AUC. By using the CAFA 5 dataset and pre-trained ProtT5 embeddings, I will evaluate how well the
embeddings contribute to accurate predictions compared to simpler or alternative methods.

3) Which datasets are you going to use and where will you get them from (links
if possible)?
We will use the CAFA 5 Protein Function Prediction dataset from Kaggle, which contains amino acid
sequences and their associated functions. The specific dataset can be accessed via this Kaggle link.
Additionally, I will utilize the pre-trained ProtT5 embeddings provided by Sergei Fironov, available in
the competition resources.


Links for Datasets :
CAFA 5 : https://www.kaggle.com/competitions/cafa-5-protein-function-prediction/data
Prot_T5 Embeds : https://www.kaggle.com/datasets/sergeifironov/t5embeds/data
4) What kind of experiment will you run and what will you measure (e.g., time,
score, p-value etc).
We will run experiments to train a multi-label classification model using the CAFA 5 dataset. And we
will be measuring Training time, Binary Accuracy, AUC(Area Under the Curve), Validation Loss, and
Early Stopping Performance. These are the metrics that will evaluate the model's performance and
efficiency.
