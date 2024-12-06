---
title: Synthetic Issue Report Data Generation
date: 2024-12-06
tags:
  - Issue Report Classification
  - Large Language Models
  - Synthetic Data
---

## Introduction
The automatic classification of Issue Reports is a crucial task for the efficient management of software projects. Machine learning models, such as BERT and its variants, have shown significant effectiveness in this task. However, training these models requires large amounts of labeled data, which are often expensive to obtain, especially in low-resource settings.

In such cases, the generation of synthetic data emerges as a promising alternative to increase the size of the training dataset and improve the performance of classifiers. The use of large language models (LLMs), such as GPT, for generating synthetic text has demonstrated great potential in various domains.

## Research Objectives
This thesis aims to investigate the use of LLMs for generating synthetic Issue Reports to train classifiers in low-resource settings. The specific objectives of the research are:

- Developing an approach for generating synthetic Issue Reports using few-shot prompts with LLMs.
A labeled initial set of Issue Reports will be used to construct few-shot prompts that guide an LLM in generating new synthetic Issue Reports. Various prompting techniques will be explored to optimize the quality and diversity of the generated data.

- Training and evaluating Issue Report classifiers using a synthetic (or hybrid) dataset.
Several Issue Report classifiers will be trained using the generated synthetic dataset or a hybrid dataset combining real and synthetic data. The classifiers' performance will be evaluated in terms of accuracy, precision, recall, and F1-score, comparing them with the performance achieved using only the initial dataset.

- Analyzing the impact of the size and quality of the synthetic dataset on classifier performance.
The study will investigate how the size and quality of the synthetic dataset influence classifier performance. Techniques to improve the quality of the synthetic data will be explored, such as filtering or manually selecting generated examples.

The results of this research will contribute to a better understanding of the use of LLMs for generating synthetic data in the field of software engineering and provide practical guidelines to enhance the accuracy of Issue Report classifiers in low-resource settings.

<!--more-->