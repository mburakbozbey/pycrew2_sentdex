# A Deep Neural Network Plays Crew 2
 <p align="center"> 
    <img src="https://github.com/mburakbozbey/pycrew2/blob/master/giphy.gif" alt="img">
 </p>
 
- Adapted and inspired by sentdex’s Python Plays GTA V series.
- Sentdex <a href="https://github.com/Sentdex/pygta5" target="_blank">Github</a>
- Sentdex <a href="https://www.youtube.com/watch?v=ks4MPfMq8aQ&list=PLQVvvaa0QuDeETZEOy4VdocT7TOjfSA8a" target="_blank">Youtube</a>

### Training Details:

- Dataset: 40 GB Training (80%) & Testing (20%) and 10 GB Validation.
- DenseNet121 with fine-tuning on ImageNet weights.
- Duration: Approx. 10 Hours, 8 Epochs.

### Demo Videos

<a href="https://www.youtube.com/watch?v=1Ho4b1gUS7Y" target="_blank">`First version`</a>

### Why the model was fine-tuned on ImageNet weights?

- From the paper “How transferable are features in deep neural networks?” by J. Yosinski et al., even big datasets can benefit from transfer learning which improves generalization. 
- Presentation of the review of the paper: https://drive.google.com/file/d/1aGBy...

## TODO:

- Data generator
- Inference optimization
- Post-processing
- Object detection - crash prevention
