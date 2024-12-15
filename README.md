# Finetuning_Llama
Fine-tuning large language models like LLaMA has transformed the way we adapt pre-trained models for specialized tasks. This repository focuses on parameter-efficient fine-tuning techniques such as LoRA and QLoRA to adapt the LLaMA2-7B model to Indian legal text datasets.<br>

## Problem Statement

You are tasked with fine-tuning the LLaMA2-7B model on a dataset related to Indian laws to make it capable of generating context-aware legal insights. The challenge is to leverage advanced fine-tuning techniques like LoRA/QLoRA to optimize the training process while keeping computational requirements minimal. Demonstrate your skills in model tuning and deployment! <br>

## Instructions

- Refer to articles, research papers, and official documentation for guidance on techniques and best practices.

- Do not alter any pre-written code or comments.

- Write code only in the provided space and document your steps with comments for better understanding.

- Use Google Colab or similar GPU-enabled environments for training and testing the model. <br>

## Procedure

### Task 1: Setup

- Check GPU connection to ensure compatibility.

- Import required libraries for processing and training.

- Validate the dataset from the Hugging Face dataset hub.

### Task 2: Data Preprocessing

- Reformat the dataset to match the LLaMA2 input format.

- Push the preprocessed dataset to the Hugging Face hub for collaborative access.

### Task 3: Model Definition

- Define the Llama2-7B-chat-hf model.

- Load the preprocessed dataset.

- Implement supervised fine-tuning with 4-bit quantization to minimize memory usage.

### Task 4: Training Preparation

- Split the dataset into training and validation sets.

- Configure the tokenizer and model with QLoRA settings.

- Check GPU compatibility.

- Load the model using AutoModelForCausalLM and LLaMA tokenizer.

- Set up LoRA configuration for parameter-efficient training.

### Task 5: Training

- Set the training parameters and fine-tuning configurations.

- Train the model on the dataset.

- Evaluate the model’s performance after training.

### Task 6: Evaluation

- Use TensorBoard to visualize training progress and metrics.

- Evaluate the model using a text generation pipeline on example legal prompts.

### Task 7: Deployment

- Save the fine-tuned model.

- Push the model to the Hugging Face hub for public use.

### Bonus Task

- Integrate the fine-tuned model with a React-based frontend and deploy it for interactive usage. 😉 <br>

- Help

- For any queries or support, feel free to reach out via email at iib2023013@iiita.ac.in or iit2023153@iiita.ac.in or join the discussion on the project’s Discord server. <br>

## Contributions

- Contributions are welcome! Follow these steps:

- Fork this repository and clone it to your local device.

- Work on individual tasks in a separate branch.

- Push your updates to the forked repo and create a Pull Request (PR).

- Your PR will be reviewed, and upon approval, merged into the main repository.

## Resources

- Dataset: Indian Law Dataset (https://huggingface.co/datasets/jizzu/llama2_indian_law_v2)

- Parameter-Efficient Fine-Tuning: LoRA Paper (https://arxiv.org/pdf/1902.00751)

- Hugging Face Transformers Documentation: Link(https://huggingface.co/docs/transformers/index) <br>

## Happy Fine-Tuning!

