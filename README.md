# Project page of CliqueCNN: Deep Unsupervised Exemplar Learning

Exemplar learning is a powerful paradigm for discovering visual similarities in
an unsupervised manner. In this context, however, the recent breakthrough in
deep learning could not yet unfold its full potential. With only a single positive
sample, a great imbalance between one positive and many negatives, and unreliable
relationships between most samples, training of Convolutional Neural networks is
impaired. Given weak estimates of local distance we propose a single optimization
problem to extract batches of samples with mutually consistent relations. Conflict-
ing relations are distributed over different batches and similar samples are grouped
into compact cliques. Learning exemplar similarities is framed as a sequence of
clique categorization tasks. The CNN then consolidates transitivity relations within
and between cliques and learns a single representation for all samples without
the need for labels. The proposed unsupervised approach has shown competitive
performance on detailed posture analysis and object classification.
---

The paper can be downloaded from https://arxiv.org/abs/1608.08792
All our models fro Olympic Sports dataset can be downloaded from [here](https://hcicloud.iwr.uni-heidelberg.de/index.php/s/kRp6b454Dd0wnts)

Models [deploy.prototxt](olympic_sports_retrieval/models/deploy.prototxt)  

Evaluation script [calculate_roc_auc.py](olympic_sports_retrieval/calculate_roc_auc.py)
