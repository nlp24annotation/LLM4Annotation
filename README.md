# Large Language Models for Data Annotation: Methods, Applications, and Challenges

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/nlp24annotation/LLM4Annotation?color=yellow)

This is a curated list of papers about , etc.

If you want to add new entries, please make PRs with the same format.

This list serves as a complement to the survey below.

[[A Comprehensive Survey on Large Language Models for Data Annotation: Methods, Applications, and Challenges]](https://)

<div align=center><img src="https://github.com/nlp24annotation/LLM4Annotation/blob/main/figure/figure.png" width="500" /></div>

If you find this repo helpful, we would appreciate it if you could cite our survey.

```
@article{,
  title={Large Language Models for Data Annotation: Methods, Applications, and Challenges},
  author={},
  journal={},
  year={2024}
}
```

## LLM-Based Data Annotation

### Manually Engineered Prompt
- [arXiv 2023] RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment. [[pdf]](https://arxiv.org/pdf/2304.06767.pdf)

- [EMNLP 2022] ZeroGen: Efficient Zero-shot Learning via Dataset Generation. [[pdf]](https://arxiv.org/pdf/2202.07922.pdf) [[code]](https://github.com/jiacheng-ye/ZeroGen)

- [ACM 2023] Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3560815)

- [EMNLP 2021] Constrained Language Models Yield Few-Shot Semantic Parsers. [[pdf]](https://aclanthology.org/2021.emnlp-main.608.pdf) [[code]](https://github.com/microsoft/semantic_parsing_with_constrained_lm)

- [NAACL-HLT 2022] Learning To Retrieve Prompts for In-Context Learning. [[pdf]](https://arxiv.org/pdf/2112.08633.pdf) [[code]](https://github.com/OhadRubin/EPR)

- [arXiv 2023] Small Models are Valuable Plug-ins for Large Language Models. [[pdf]](https://arxiv.org/pdf/2305.08848.pdf) [[code]](https://github.com/JetRunner/SuperICL)

### Alignment via Pairwise Feedback

- [arXiv 2023] A Survey of Large Language Models. [[pdf]](https://arxiv.org/pdf/2303.18223.pdf)

- [ACL 2023] Why Can GPT Learn In-Context? Language Models Secretly Perform Gradient Descent as Meta-Optimizers. [[pdf]](https://aclanthology.org/2023.findings-acl.247.pdf) [[code]](https://github.com/microsoft/LMOps/tree/main/understand_icl)

- [arXiv 2019] Fine-Tuning Language Models from Human Preferences. [[pdf]](https://arxiv.org/pdf/1909.08593.pdf) [[code]](https://github.com/openai/lm-human-preferences)

- [NeurIPS 2022] Fine-tuning language models to find agreement among humans with diverse preferences. [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/f978c8f3b5f399cae464e85f72e28503-Paper-Conference.pdf) 

- [arXiv 2022] Improving alignment of dialogue agents via targeted human judgements. [[pdf]](https://arxiv.org/pdf/2209.14375.pdf) 

- [arXiv 2022] Teaching language models to support answers with verified quotes. [[pdf]](https://arxiv.org/pdf/2203.11147.pdf) [[data]](https://storage.googleapis.com/deepmind-media/DeepMind.com/Authors-Notes/gophercite-teaching-language-models-to-support-answers-with-verified-quotes/eli5-examples-v2.html)

- [NeurIPS 2020] Learning to summarize with human feedback. [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2020/file/1f89885d556929e98d3ef9b86448f951-Paper.pdf) [[code]](https://github.com/openai/summarize-from-feedback)

- [arXiv 2023] Direct Preference Optimization: Your Language Model is Secretly a Reward Model. [[pdf]](https://arxiv.org/pdf/2305.18290.pdf)

<!-- ########################################### -->

## Assessing LLM-Generated Annotations

### Evaluating LLM-Generated Annotations

### Data Selection via Active Learning

<!-- ########################################### -->

## Learning with LLM-Generated Annotations

### Target Domain Inference: Direct Utilization of Annotations

### Knowledge Distillation: Bridging LLM and task-specific models

### Harnessing LLM Annotations for Fine-Tuning and Prompting

<!-- ########################################### -->

## Surveys

Graph Reduction/ Summarization / Simplification

- **[Ours][arXiv 2024] A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation. [[pdf]](https://arxiv.org/abs/2402.03358)**
- [arXiv 2024] A Survey on Graph Condensation. [[pdf]](https://arxiv.org/abs/2402.02000)

## Toolkits

- Mongoose: [[pdf]](https://people.clas.ufl.edu/hager/files/mongoose.pdf) [[code]](https://github.com/ScottKolo/Mongoose)