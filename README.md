Vision Transformer and MLP-Mixer Architectures
In this repository we release models from the papers

An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale
MLP-Mixer: An all-MLP Architecture for Vision
How to train your ViT? Data, Augmentation, and Regularization in Vision Transformers
When Vision Transformers Outperform ResNets without Pretraining or Strong Data Augmentations
LiT: Zero-Shot Transfer with Locked-image text Tuning
Surrogate Gap Minimization Improves Sharpness-Aware Training
The models were pre-trained on the ImageNet and ImageNet-21k datasets. We provide the code for fine-tuning the released models in JAX/Flax.

The models from this codebase were originally trained in https://github.com/google-research/big_vision/ where you can find more advanced code (e.g. multi-host training), as well as some of the original training scripts (e.g. configs/vit_i21k.py for pre-training a ViT, or configs/transfer.py for transfering a model).

Table of contents:

MLP-Mixer Architectures
Colab
Installation
Fine-tuning a model
Vision Transformer
MLP-Mixer

Colab
Below Colabs run both with GPUs, and TPUs (8 cores, data parallelism).

The Colab demonstrates the JAX code of Vision Transformers and MLP Mixers. This Colab allows you to edit the files from the repository directly in the Colab UI and has annotated Colab cells that walk you through the code step by step, and lets you interact with the data.

https://colab.research.google.com/github/google-research/vision_transformer/blob/main/vit_jax.ipynb

Note: The code will run only in colab.