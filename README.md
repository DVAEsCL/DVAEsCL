# Shared and Private VAEs with Generative Replay for Continual Learning
This is the official PyTorch implementation of [Shared and Private VAEs with Generative Replay for Continual Learning](https://arxiv.org/abs/2105.07627). 
# Abstract 
Continual learning tries to learn new tasks without forgetting previously learned ones. In reality, most of the existing artificial neural network(ANN) models fail, while humans do the same by remembering previous works throughout their life. Although simply storing all past data can alleviate the problem, it needs large memory and often infeasible in real-world applications where last data access is limited. We hypothesize that the model that learns to solve each task continually has some task-specific properties and some task-invariant characteristics. We propose a hybrid continual learning model that is more suitable in real case scenarios to address the issues that has a task-invariant shared variational autoencoder and T task-specific variational autoencoders. Our model combines generative replay and architectural growth to prevent catastrophic forgetting. We show our hybrid model effectively avoids forgetting and achieves state-of-the-art results on visual continual learning benchmarks such as MNIST, Permuted MNIST(QMNIST), CIFAR100, and miniImageNet datasets. We discuss results on a few more datasets, such as SVHN, Fashion-MNIST, EMNIST, and CIFAR10.

# Authors:
[Subhankar Ghosh](https://sites.google.com/view/subhankarghosh/home)(Indian Institute of Science)
# Citation
If using this code, parts of it, or developments from it, please cite our paper:
```
@article{ghosh2021shared,
  title={Shared and Private VAEs with Generative Replay for Continual Learning},
  author={Ghosh, Subhankar},
  journal={arXiv preprint arXiv:2105.07627},
  year={2021}
}
```
# Datasets
The required instructions are given in each notebook.\
Without further waiting, open any of the notebooks and run the code to see the results.
# Questions/ Bugs
For questions and bugs, please contact the author Subhankar Ghosh via email [subhankarg@alum.iis.ac.in](mailto:x@x.com)
# License
This source code is released under The MIT License found in the [LICENSE](https://github.com/DVAEsCL/DVAEsCL/blob/main/LICENSE) file in the root directory of this source tree.



