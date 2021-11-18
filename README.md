# Awesome Fine-tuning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources on fine-tuning language models, inspired by [awesome-implicit-representations](https://github.com/vsitzmann/awesome-implicit-representations).

## Disclaimer

This list does __not aim to be exhaustive__. Feel free to open a pull request in order to suggest papers that should be added to the list.

Disclosure. I'm an author of the following papers:

- [On the Stability of Fine-tuning BERT: Misconceptions, Explanations, and Strong Baselines](https://openreview.net/forum?id=nzpLWnVAyah)
- [On the Interplay Between Fine-tuning and Sentence-level Probing for Linguistic Knowledge in Pre-trained Transformers](https://aclanthology.org/2020.findings-emnlp.227/)


## Table of contents

- [Papers](#papers)
# Papers

## Fine-tuning stability

- [Fine-Tuning Pretrained Language Models: Weight Initializations, Data Orders, and Early Stopping](https://arxiv.org/abs/2002.06305) Dodge et al. (2020) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Revisiting Few-sample BERT Fine-tuning]() Zhang et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- [On the Stability of Fine-tuning BERT: Misconceptions, Explanations, and Strong Baselines](https://openreview.net/forum?id=nzpLWnVAyah) Mosbach et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

## Intermediate Task Fine-tuning

- [Placeholder](https://github.com/mmarius/awesome-finetuning) ![](https://img.shields.io/badge/arXiv-b31b1b)

## Parameter-efficient Fine-tuning

- [Training Neural Networks with Fixed Sparse Masks](https://proceedings.neurips.cc/paper/2021/hash/cb2653f548f8709598e8b5156738cc51-Abstract.html) Sung et al. (2021) ![](https://img.shields.io/badge/NeurIPS-grey)

## Prompt-based Fine-tuning

### Discrete Prompts

- [Exploiting Cloze Questions for Few Shot Text Classification and Natural Language Inference](https://aclanthology.org/2021.eacl-main.20/) Schick & Schütze (2021a) ![](https://img.shields.io/badge/EACL-orange)

- [It's Not Just Size That Matters: Small Language Models Are Also Few-Shot Learners](https://aclanthology.org/2021.naacl-main.185/) Schick & Schütze (2021b) ![](https://img.shields.io/badge/NAACL-purple)

- [Automatically Identifying Words That Can Serve as Labels for Few-Shot Text Classification](https://aclanthology.org/2020.coling-main.488/) Schick et al. (2020) ![](https://img.shields.io/badge/COLING-pink)

- [Few-Shot Text Generation with Natural Language Instructions](https://aclanthology.org/2021.emnlp-main.32/) Schick & Schütze (2021c) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Making Pre-trained Language Models Better Few-shot Learners](https://aclanthology.org/2021.acl-long.295/) Gao et al. (2021) ![](https://img.shields.io/badge/ACL-blue)

- [How Many Data Points is a Prompt Worth?](https://aclanthology.org/2021.naacl-main.208/) Le Scao & Rush (2021) ![](https://img.shields.io/badge/NAACL-purple)

- [Improving and Simplifying Pattern Exploiting Training](https://aclanthology.org/2021.emnlp-main.407/) Tam et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Adapting Language Models for Zero-shot Learning by Meta-tuning on Dataset and Prompt Collections](https://aclanthology.org/2021.findings-emnlp.244/) Zhong et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

### Continuous Prompts

- [Factual Probing Is [MASK]: Learning vs. Learning to Recall](https://aclanthology.org/2021.naacl-main.398/) Zhong et al. (2021) ![](https://img.shields.io/badge/NAACL-purple)

## Theoretical Work

- [A Mathematical Exploration of Why Language Models Help Solve Downstream Tasks](https://openreview.net/forum?id=vVjIW3sEc1s) Saunshi et al. (2021) ![](https://img.shields.io/badge/ICLR-green)