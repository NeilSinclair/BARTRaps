# BARTRaps
Repository for the "BART Learns to Rap" code for fine-tuning the Hugging Face Transformer BART Model

## Overview
This repository contains two notebooks used to fine-tune Hugging Face's BART model on the seq2seq task of conditional lyric generation - i.e. it teaches BART to write a new rap line based on a previous line fed to the model. Using the pre-trained BART model's seq2seq capabilities, these notebooks essentially allow one to easily fine-tune the model on any other seq2seq task.

The "BART Learns to Rap - Medium.ipynb" notebook borrows relatively liberally from some of Hugging Face's fine-tuning scripts, however it allows one more control over the fine-tuning process. For more information, refer to the Medium post accompanying this repo: https://towardsdatascience.com/teaching-bart-to-rap-fine-tuning-hugging-faces-bart-model-41749d38f3ef 
