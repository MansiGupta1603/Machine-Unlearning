# Machine-Unlearning
Experimenting with the use of pruning combined with lora in order to perform machine unlearning

## 1. Overview

 **Machine unlearning** is an emergent subfield of machine learning that aims to remove the influence of a specific subset of training examples — the "forget set" — from a trained model. Furthermore, an ideal unlearning algorithm would remove the influence of certain examples while maintaining other beneficial properties, such as the accuracy on the rest of the train set and generalization to held-out examples.

A straightforward way to produce this unlearned model is to retrain the model on an adjusted training set that excludes the samples from the forget set.

## 2. Approach

We have gone beyond traditional fine-tuning methods by exploring the impact of sparsity enforcement on the unlearning process. Our experimentation involves the utilization of  structured as well as unstructured techniques, followed by unlearning by Lora finetuning in order to further reinforce the idea of sparsity as well as speed up the process of finetuning.
