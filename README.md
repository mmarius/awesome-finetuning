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

- ... 

## Intermediate task fine-tuning

- [Sentence Encoders on STILTs: Supplementary Training on Intermediate Labeled-data Tasks](https://arxiv.org/abs/1811.01088) Phang et al. (2018) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Muppet: Massive Multi-task Representations with Pre-Finetuning]() Aghajanyan et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)


- ... 

## Parameter-efficient fine-tuning

- [Parameter-Efficient Transfer Learning for NLP](https://proceedings.mlr.press/v97/houlsby19a) Houlsby et al. (2019) ![](https://img.shields.io/badge/ICML-cyan)

- [AdapterFusion: Non-Destructive Task Composition for Transfer Learning](https://aclanthology.org/2021.eacl-main.39/) Pfeiffer et al. (2021) ![](https://img.shields.io/badge/EACL-orange)

- [AdapterDrop: On the Efficiency of Adapters in Transformers](https://aclanthology.org/2021.emnlp-main.626/) Rücklé et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)
 
- [Parameter-efficient transfer learning with diff pruning](https://aclanthology.org/2021.acl-long.378/) Guo et al. (2021) ![](https://img.shields.io/badge/ACL-blue)

- [Compacter: Efficient Low-Rank Hypercomplex Adapter Layers](https://arxiv.org/abs/2106.04647) Mahabadi et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) Hu et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [BitFit: Simple Parameter-efficient Fine-tuning for Transformer-based Masked Language-models](https://arxiv.org/abs/2106.10199) Zaken et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Training Neural Networks with Fixed Sparse Masks](https://proceedings.neurips.cc/paper/2021/hash/cb2653f548f8709598e8b5156738cc51-Abstract.html) Sung et al. (2021) ![](https://img.shields.io/badge/NeurIPS-brightgreen)

- [Towards a Unified View of Parameter-Efficient Transfer Learning](https://openreview.net/forum?id=0RDcd5Axok) He et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- [Composable Sparse Fine-Tuning for Cross-Lingual Transfer](https://arxiv.org/abs/2110.07560) Ansell et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- ... 

Continuous prompt-based methods can also be seen as parameter-efficient fine-tuning methods. For a list of papers see [below](#continuous-prompts).

## Prompt-based fine-tuning

### Discrete prompts

- [Exploiting Cloze Questions for Few Shot Text Classification and Natural Language Inference](https://aclanthology.org/2021.eacl-main.20/) Schick & Schütze (2021a) ![](https://img.shields.io/badge/EACL-orange)

- [It's Not Just Size That Matters: Small Language Models Are Also Few-Shot Learners](https://aclanthology.org/2021.naacl-main.185/) Schick & Schütze (2021b) ![](https://img.shields.io/badge/NAACL-purple)

- [Automatically Identifying Words That Can Serve as Labels for Few-Shot Text Classification](https://aclanthology.org/2020.coling-main.488/) Schick et al. (2020) ![](https://img.shields.io/badge/COLING-pink)

- [Few-Shot Text Generation with Natural Language Instructions](https://aclanthology.org/2021.emnlp-main.32/) Schick & Schütze (2021c) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Making Pre-trained Language Models Better Few-shot Learners](https://aclanthology.org/2021.acl-long.295/) Gao et al. (2021) ![](https://img.shields.io/badge/ACL-blue)

- [How Many Data Points is a Prompt Worth?](https://aclanthology.org/2021.naacl-main.208/) Le Scao & Rush (2021) ![](https://img.shields.io/badge/NAACL-purple)

- [Improving and Simplifying Pattern Exploiting Training](https://aclanthology.org/2021.emnlp-main.407/) Tam et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Adapting Language Models for Zero-shot Learning by Meta-tuning on Dataset and Prompt Collections](https://aclanthology.org/2021.findings-emnlp.244/) Zhong et al. (2021) ![](https://img.shields.io/badge/Findings-EMNLP-yellow)

- [PTR: Prompt Tuning with Rules for Text Classification](https://arxiv.org/abs/2105.11259) Han et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Cutting Down on Prompts and Parameters: Simple Few-Shot Learning with Language Models](https://arxiv.org/abs/2106.13353) Logan IV et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Knowledgeable Prompt-tuning: Incorporating Knowledge into Prompt Verbalizer for Text Classification](https://arxiv.org/abs/2108.02035) Hu et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Prompt-Learning for Fine-Grained Entity Typing](https://arxiv.org/abs/2108.10604) Ding et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Do Prompt-Based Models Really Understand the Meaning of their Prompts?](https://arxiv.org/abs/2109.01247) Webson & Pavlick (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Avoiding Inference Heuristics in Few-shot Prompt-based Finetuning](https://aclanthology.org/2021.emnlp-main.713/) Utama et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- ... 

#### Multi-task fine-tuning using discrete prompts

- [Cross-Task Generalization via Natural Language Crowdsourcing Instructions](https://arxiv.org/abs/2104.08773) Mishra et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Finetuned Language Models Are Zero-Shot Learners](https://openreview.net/forum?id=gEZrGCozdqR) Wei et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- [Discrete and Soft Prompting for Multilingual Models](https://aclanthology.org/2021.emnlp-main.672/) Zhao & Schütze (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://openreview.net/forum?id=9Vrb9D0WI4) Sanh et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- ... 

### Continuous prompts

- [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/abs/2101.00190) Li & Liang (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [WARP: Word-level Adversarial ReProgramming](https://aclanthology.org/2021.acl-long.381/) Hambardzumyan et al. (2021) ![](https://img.shields.io/badge/ACL-blue)

- [Learning How to Ask: Querying LMs with Mixtures of Soft Prompts](https://aclanthology.org/2021.naacl-main.410/) Qin & Eisner (2021) ![](https://img.shields.io/badge/NAACL-purple)

- [Factual Probing Is [MASK]: Learning vs. Learning to Recall](https://aclanthology.org/2021.naacl-main.398/) Zhong et al. (2021) ![](https://img.shields.io/badge/NAACL-purple)

- [The Power of Scale for Parameter-Efficient Prompt Tuning](https://aclanthology.org/2021.emnlp-main.243/) Lester et al. (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- [Multimodal Few-Shot Learning with Frozen Language Models](https://papers.nips.cc/paper/2021/hash/01b7575c38dac42f3cfb7d500438b875-Abstract.html) Tsimpoukelli et al. (2021) ![](https://img.shields.io/badge/NeurIPS-brightgreen)

- [Noisy Channel Language Model Prompting for Few-Shot Text Classification](https://arxiv.org/abs/2108.04106) Min et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [Differentiable Prompt Makes Pre-trained Language Models Better Few-shot Learners](https://openreview.net/forum?id=ek9a0qIafW) Zhang et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- [Continuous Entailment Patterns for Lexical Inference in Context](https://aclanthology.org/2021.emnlp-main.556/) Schmitt & Schütze (2021) ![](https://img.shields.io/badge/EMNLP-yellow)

- [SPoT: Better Frozen Model Adaptation through Soft Prompt Transfer](https://arxiv.org/abs/2110.07904) Vu et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- ... 

## Few-shot fine-tuning

- [True Few-Shot Learning with Language Models](https://arxiv.org/abs/2105.11447) Perez et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [FLEX: Unifying Evaluation for Few-Shot NLP](https://papers.nips.cc/paper/2021/hash/8493eeaccb772c0878f99d60a0bd2bb3-Abstract.html) Bragg et al. (2021) ![](https://img.shields.io/badge/NeurIPS-brightgreen)

- [FewNLU: Benchmarking State-of-the-Art Methods for Few-Shot Natural Language Understanding](https://arxiv.org/abs/2109.12742) Zheng et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- ... 

## Fine-tuning and probing

- [What Happens To BERT Embeddings During Fine-tuning?](https://aclanthology.org/2020.blackboxnlp-1.4/) Merchant et al. (2020) ![](https://img.shields.io/badge/Blackbox--NLP-EMNLP-yellow)

- [On the Interplay Between Fine-tuning and Sentence-level Probing for Linguistic Knowledge in Pre-trained Transformers](https://aclanthology.org/2020.findings-emnlp.227/) Mosbach et al. (2020) ![](https://img.shields.io/badge/Blackbox--NLP-EMNLP-yellow)

- [Fine-Tuned Transformers Show Clusters of Similar Representations Across Layers](https://aclanthology.org/2021.blackboxnlp-1.42/) Phang et al. (2021) ![](https://img.shields.io/badge/Blackbox--NLP-EMNLP-yellow)

- ... 

## Theoretical work

- [A Mathematical Exploration of Why Language Models Help Solve Downstream Tasks](https://openreview.net/forum?id=vVjIW3sEc1s) Saunshi et al. (2021) ![](https://img.shields.io/badge/ICLR-green)

- [Why Do Pretrained Language Models Help in Downstream Tasks? An Analysis of Head and Prompt Tuning](https://arxiv.org/abs/2106.09226) Wei et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- [An Explanation of In-context Learning as Implicit Bayesian Inference](https://arxiv.org/abs/2111.02080) Xie et al. (2021) ![](https://img.shields.io/badge/arXiv-b31b1b)

- ... 