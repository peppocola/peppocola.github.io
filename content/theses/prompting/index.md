---
title: Investigating Prompt Variations for Issue Report Classification with Large Language Models
date: 2024-12-06
tags:
  - Issue Report Classification
  - Large Language Models
  - Prompting
---

## Introduction
Classifying issue reports is a crucial task in software development, as it helps manage and resolve problems more efficiently. With the advent of Large Language Models (LLMs) such as BERT and GPT, this task can be automated, enhancing both the accuracy and speed of classification.

While BERT-like models require fine-tuning on labeled datasets to achieve optimal performance, GPT-like models can operate in zero-shot scenarios, leveraging their ability to understand tasks through descriptions provided in the prompt. However, the effectiveness of these models heavily depends on the structure of the prompt, including task descriptions, labels, and examples.

This thesis aims to explore the impact of prompt variations on GPT-like models for issue report classification, comparing their performance to that of BERT-like models fine-tuned on datasets sourced from GitHub and Jira.

## Objectives

- Explore prompting techniques for GPT-like models, analyzing how prompt design affects accuracy and performance.
- Identify the best prompting strategies based on model type, availability of labeled data, and computational resources.
- Evaluate performance on issue report datasets from GitHub and Jira, analyzing differences across zero-shot, few-shot, and fine-tuning scenarios.
- Compare GPT-like and BERT-like models, contrasting prompt engineering with fine-tuning for issue report classification.

<!--more-->