# Mamba-Chat 🐍

Mamba-Chat is the first chat language model based on a state-space model architecture, not a transformer.

The model is based on Albert Gu's and Tri Dao's work *Mamba: Linear-Time Sequence Modeling with Selective State Spaces* as well as their [model implementation](https://github.com/state-spaces/mamba). This repository provides training / fine-tuning code for the model based on some modifications of the Huggingface Trainer class.

To learn more, you can:

- Take a look at the model on [Huggingface](https://huggingface.co/havenhq/mamba-chat) 🤗
- Join the [Haven](https://haven.run/) Community [Discord](https://discord.com/invite/JDjbfp6q2G) 🧑‍🤝‍🧑


<br>
## Run Mamba-Chat

We provide code that lets you run inference on mamba-chat as well as our fine-tuning code. Here are the steps to get started:


**Clone repository and install dependencies:**
```
git clone https://github.com/havenhq/mamba-chat.git

cd mamba-chat

pip install -r requirements.txt
```


**Talk to Mamba-Chat:**
```
python chat.py
```

**Fine-Tune Mamba (the base model) on a subset of the Ultrachat dataset:**
```
python train_mamba.py
```
