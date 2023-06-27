---
author: pipinstallyp
pubDatetime: 2022-09-23T15:22:00Z
title: LLaMA can run on your toaster, here are 8 developments that enable it
postSlug: fundamental-developments-in-llama
featured: true
draft: false
tags:
  - developments,  
  - llama
ogImage: ""
description: A look at some significant developments, tools and techniques in Llama.
---

A roundup of considerable developments, tools, and techniques in LlaMA landscape. These techniques are an attempt to squeeze the most juice out of the large family of llama models by Meta by hackers, research labs and independent researchers alike.
These developments form a foundational understanding of how to make LLaMA models the best they could ever be. 

## Table of Contents

## MEGABYTE (Context Length of a Million Tokens)
Predicting Million-byte Sequences with Multiscale Transformers [Read paper here](https://arxiv.org/abs/2305.07185)

## QLoRA (Train a language model on your consumer machine)
1. 4-bit finetuning of LLMs is here! With it comes Guanaco, a chatbot on a single GPU, achieving 99% ChatGPT performance on the Vicuna benchmark [Find it here](https://github.com/artidoro/qlora)
2. This is a bits and bytes release that can finetune 65B llama on single GPU.

## Sophia (New Optimiser)
A new optimizer that is 2x faster than Adam on LLMs [Read further here](https://arxiv.org/abs/2305.14342)

## AMD Support
Technique that makes llama cpp run on AMD [Check it out](https://github.com/ggerganov/llama.cpp/pull/1459)

## Context Free Grammar Constraints
Make your llama follow certain grammar [Learn more here](https://github.com/grantslatton/llama.cpp/commit/007e26a99d485007f724957fa8545331ab8d50c3)

## Reading to Understand Lora
[Lightning AI's blog to understand LoRA in depth](https://lightning.ai/pages/community/tutorial/lora-llm/)

## Repo
Repo that runs llama at 2x speed [Find here](https://github.com/turboderp/exllama) 

## LIMA
Training using 1000 instructions which don’t involve RLHF to achieve near GPT-4 level performance in looks. Note that not all GPT-4 features are available as GPT-4 is too huge. [Read paper here](https://arxiv.org/pdf/2305.11206.pdf)