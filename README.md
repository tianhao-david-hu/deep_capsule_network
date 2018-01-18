# Deep Capsule Network Research Project
This research project is part of the CSC411 Machine Learning course.

The motivation is to experiment with the recently proposed capsule network (https://arxiv.org/abs/1710.09829), learn its characteristics, and seek for any possible improvement.
This research leads to a multi-layer capsule network that has a non-trivial improvement on CIFAR10 dataset. The reconstruction network also seems to have a better ability of capture the variation of the objects and their feature hierarchies in MNIST dataset.

The project report is marked, and a good feedback is received from the instructor:
>This paper implements the Capsules network originally proposed by Sabour et. al and applied it on the German Traffic Sign data. A performance gap compared to state of the art CNN architectures was shown. A deep capsules network is then proposed by converting the outputs from a fully connected layer output from the first capsules note into stacked feature images that are fed into a secondary capsules network. The deep and standard capsule network are compared in the MNIST and CIFAR10 dataset (not the GTS dataset, probably due to time constraint). Some more formal description for the capsules network and discussions of more related works to capsules would make the paper more clear. Overall this is a good paper setting up the stage for further investigation into capsules network.

This project is uploaded here in the hope that the result can be useful for researchers in any possible ways. 

## Development Environment
The capsule networks in this project are prototyped using Jupyter Notebook that comes with Anaconda2-2.4.1-Windows-x86. The capsule network is implemented with TensorFlow. The development environment is setup using Conda with the yml file provided in this repository. The official documentation of Conda has a detailed instruction on the setup procedure using yml file: https://conda.io/docs/user-guide/tasks/manage-environments.html

## Repository Structure
* TowardsADeepCapsuleNetwork.pdf: The submitted research report.
* Source: The folder that contains all Jupyter Notebook files and auxiliary python scripts for loading CIFAR10 dataset.
* capsule_dev_env.yml: The environment configuration file.
