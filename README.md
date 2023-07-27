Seminar DO+ML 2022
Inspired by Hooker et al https://arxiv.org/abs/1911.05248.

Studied the effect of knowledge distillation (by comparing BERT and DistilBERT) on the test error distribution on the Toxic Comment Classification Dataset (https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).
The distilled model performs worse on examples that are harder to classify by the base model. Moreover, it seems to amplify biases that are already present in the base model.
