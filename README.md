
# Reason-Action Online RL
The goal of this project to demonstrate the effectiveness of reason-action online RL training vs only reasoning.

## Background
DeepSeek R1 paper demonstrates the effectiveness of training using a very basic CoT template prompt +  an online RL with respect to a simple reward function.
In this recent work, they demonstrate that this training paradigm also works well with small models with a small amount of data.
We know the advantages of ReACT prompting over simple CoT. The assumption is that using the same recipe of online RL-training with ReACT will perform better than reasoning model or even reasoning model training + inference time ReACT prompting

## 
The code is based on [simpleRL-reason](https://github.com/hkust-nlp/simpleRL-reason/tree/main)
