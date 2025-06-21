---
title: "Building a Transformer model from scratch"
excerpt: "In this project I build a transformer model only using Pytorch.<br/><img src='/images/transformers_arch.png'>"
collection: portfolio
---

This is a project I worked on to be able to better understand the [Transformer](https://arxiv.org/abs/1706.03762) model architecture.

I mainly followed the [Youtube Tutorial](https://www.youtube.com/watch?v=ISNdQcPhsts&ab_channel=UmarJamil) by Umar Jamil.

This project can be found in a repository in my github under the name of [TransformersTut](https://github.com/PerezDavid-98/TransformersTut)

I made some changes to the original implementation:
- I decided to change the languages of the translation task to make it translate from English to Spanish.
- I changed the configuration a bit to be able to train and inference the model using my personal system (NVIDIA 4070 with 12GBs of VRAM).
- I added type annotation to some of the classes and functions to make them more understandable. 

The reason of trying to build the transformer model from scratch was to get a better understanding of how this model architecture works, rather than just importing it from a commonly used library
and then using it on another project.

Sadly my system was not powerful enough to sustain extended training times, and thus not many meaningful results were obtained.
Nonetheless, the purpose of this project was to improve my understanding of the Transformer Architecture and on that front it was a success.