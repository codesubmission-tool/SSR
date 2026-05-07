# SRR: Situational Risk Reasoning Dataset

This repository provides information and links for the **SRR (Situational Risk Reasoning)** dataset.

SRR is a supervised fine-tuning dataset for post-training vision-language models (VLMs). It is designed to improve VLMs' ability to reason about **situational risks**, where the safety of a user request depends on the interaction between the user's intended activity and the visual scenario.

## Dataset

The dataset is hosted on Hugging Face:

**Hugging Face Dataset:**  
https://huggingface.co/datasets/Anonymous-SRR/SRR

The dataset contains image-instruction-response examples formatted in a ShareGPT-style conversation format, making it suitable for supervised fine-tuning with common VLM training frameworks such as LLaMA-Factory.

## Model Checkpoint

We also provide the LoRA checkpoint trained with SRR for reproducing our post-training experiments:

**LoRA Checkpoint:**  
[https://huggingface.co/Anonymous-SRR/SRR-LoRA](https://github.com/codesubmission-tool/SSR/releases/tag/V1)

The checkpoint is intended for research use and should be used together with the Qwen2-VL described in the paper.

