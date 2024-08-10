# Finetune-Run-Llama3.1-Locally

![thumbnail](https://github.com/user-attachments/assets/c6971535-6a44-473d-b2f6-0c96254e253c)

Welcome to the Llama 3.1 Fine-Tuning and Inference Repository!

This repository contains two Jupyter notebooks designed to facilitate the fine-tuning and evaluation of the Llama 3.1 8B model using advanced techniques.

Overview
**Fine-Tuning Notebook**: This notebook guides you through the process of fine-tuning the Llama 3.1 8B model on a specialized dataset. We use the QLoRA technique to efficiently train the model and save the LoRA adapters to Hugging Face. These adapters help customize the model's performance for specific tasks, such as understanding Arabic instructions. The notebook covers the entire fine-tuning pipeline, including data preparation, model training, and adapter saving.

**Inference Notebook**: In this notebook, we focus on using the fine-tuned model for inference. It demonstrates how to import the saved LoRA adapters into LM Studio and perform inference on a dataset. This notebook allows you to evaluate the model's performance by comparing its outputs with ground truth data. We also provide a section on how to set up a local server for model inference, using the base model and the fine-tuned model for comparison.
