# A Deep Neural Network Plays Crew 2

Adapted and inspired by sentdex’s Python Plays GTA V series.

Sentdex Github: https://github.com/Sentdex/pygta5
Sentdex Youtube: https://www.youtube.com/playlist?list...

# Training Details:

- Dataset: 40 GB Training (80%) & Testing (20%) and 10 GB Validation.
- DenseNet121 with fine-tuning on ImageNet weights.
- Duration: Approx. 10 Hours, 8 Epochs.

# Why the model was fine-tuned on ImageNet weights?

- From the paper “How transferable are features in deep neural networks?” by J. Yosinski et al., even big datasets can benefit from transfer learning which improves generalization. 
- Presentation of the review of the paper: https://drive.google.com/file/d/1aGBy...
