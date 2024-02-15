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

- [arXiv 2020] The Turking Test: Can Language Models Understand Instructions? [[pdf]](https://arxiv.org/pdf/2010.11982.pdf)

- [arXiv 2022] Unnatural Instructions: Tuning Language Models with (Almost) No Human Labor. [[pdf]](https://arxiv.org/pdf/2212.09689.pdf) [[code]](https://github.com/orhonovich/unnatural-instructions)

- [arXiv 2023] Open-Source Large Language Models Outperform Crowd Workers and Approach ChatGPT in Text-Annotation Tasks. [[pdf]](https://arxiv.org/pdf/2307.02179.pdf)

- [arXiv 2023] Open-Source Large Language Models Outperform Crowd Workers and Approach ChatGPT in Text-Annotation Tasks. [[pdf]](https://arxiv.org/pdf/2307.02179.pdf)

- [NAACL 2022] LMTurk: Few-Shot Learners as Crowdsourcing Workers in a Language-Model-as-a-Service Framework. [[pdf]](https://aclanthology.org/2022.findings-naacl.51.pdf) [[code]](https://github.com/lmturk)

- [EMNLP 2022] Large Language Models are Few-Shot Clinical Information Extractors. [[pdf]](https://aclanthology.org/2022.emnlp-main.130.pdf) [[data]](https://huggingface.co/datasets/mitclinicalml/clinical-ie)

- [arXiv 2023] AnnoLLM: Making Large Language Models to Be Better Crowdsourced Annotators. [[pdf]](https://arxiv.org/pdf/2303.16854.pdf)

### Data Selection via Active Learning

- [EACL 2021] Active Learning for Sequence Tagging with Deep Pre-trained Models and Bayesian Uncertainty Estimates. [[pdf]](https://aclanthology.org/2021.eacl-main.145.pdff)

- [arXiv 2022] Active learning helps pretrained models learn the intended task. [[pdf]](https://arxiv.org/pdf/2204.08491.pdf) [[code]](https://github.com/alextamkin/active-learning-pretrained-models)

- [EMNLP 2023] Active Learning Principles for In-Context Learning with Large Language Models. [[pdf]](https://aclanthology.org/2023.findings-emnlp.334.pdf)

- [arXiv 2023] Large Language Models as Annotators: Enhancing Generalization of NLP Models at Minimal Cost. [[pdf]](https://arxiv.org/pdf/2306.15766.pdf)

- [IUI 2023] ScatterShot: Interactive In-context Example Curation for Text Transformation. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3581641.3584059) [[code]](https://github.com/tongshuangwu/scattershot)

- [ICML 2023] Prefer to Classify: Improving Text Classifiers via Auxiliary Preference Learning. [[pdf]](https://arxiv.org/pdf/2306.04925) [[code]](https://github.com/minnesotanlp/p2c)

<!-- ########################################### -->

## Learning with LLM-Generated Annotations

### Target Domain Inference: Direct Utilization of Annotations

- [ACL 2022] An Information-theoretic Approach to Prompt Engineering Without Ground Truth Labels. [[pdf]](https://aclanthology.org/2022.acl-long.60.pdf) [[code]](https://github.com/BYU-PCCL/information-theoretic-prompts)

- [TMLR 2022] Emergent Abilities of Large Language Models. [[pdf]](https://arxiv.org/pdf/2206.07682.pdf)

- [NeurIPS 2022] Large Language Models are Zero-Shot Reasoners. [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2022/file/8bb0d291acd4acf06ef112099c16f326-Paper-Conference.pdf)

- [EMNLP 2019] Language Models as Knowledge Bases? [[pdf]](https://arxiv.org/pdf/1909.01066.pdf) [[code]](https://github.com/facebookresearch/LAMA)

- [arXiv 2023] Causal Reasoning and Large Language Models: Opening a New Frontier for Causality. [[pdf]](https://arxiv.org/pdf/2305.00050.pdf) 

- [ECIR 2024] Large Language Models are Zero-Shot Rankers for Recommender Systems. [[pdf]](https://arxiv.org/pdf/2305.08845.pdf) [[code]](https://github.com/RUCAIBox/LLMRank)

- [arXiv 2023] A Systematic Survey of Prompt Engineering on Vision-Language Foundation Models. [[pdf]](https://arxiv.org/pdf/2307.12980.pdf)  [[repo]](https://github.com/JindongGu/Awesome-Prompting-on-Vision-Language-Model/)


- [PMLR 2021] Learning Transferable Visual Models From Natural Language Supervision. [[pdf]](http://proceedings.mlr.press/v139/radford21a/radford21a.pdf) [[code]](https://github.com/OpenAI/CLIP)

- [arXiv 2022] Visual Classification via Description from Large Language Models. [[pdf]](https://arxiv.org/pdf/2210.07183.pdf)

### Knowledge Distillation: Bridging LLM and task-specific models

- [arXiv 2022] Teaching Small Language Models to Reason. [[pdf]](https://arxiv.org/pdf/2212.08410.pdf)

- [arXiv 2023] Specializing Smaller Language Models towards Multi-Step Reasoning. [[pdf]](https://arxiv.org/pdf/2301.12726.pdf)

- [EMNLP 2023] Is ChatGPT Good at Search? Investigating Large Language Models as Re-Ranking Agents. [[pdf]](https://arxiv.org/pdf/2304.09542.pdf) [[code]](https://github.com/sunnweiwei/RankGPT)

- [ACL 2023] Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes. [[pdf]](https://arxiv.org/pdf/2305.02301.pdf) [[code]](https://github.com/google-research/distilling-step-by-step)

- [ACL 2023] GPT4All: Training an Assistant-style Chatbot with Large Scale Data Distillation from GPT-3.5-Turbo. [[pdf]](http://static.nomic.ai.s3.amazonaws.com/gpt4all/2023_GPT4All_Technical_Report.pdf) [[code]](https://github.com/nomic-ai/gpt4all)

- [ACL 2023] GKD: A General Knowledge Distillation Framework for Large-scale Pre-trained Language Model. [[pdf]](https://aclanthology.org/2023.acl-industry.15.pdf) [[code]](https://github.com/aitsc/GLMKD)

- [EMNLP 2023] Lion: Adversarial Distillation of Proprietary Large Language Models. [[pdf]](https://arxiv.org/pdf/2305.12870.pdf) [[code]](https://github.com/YJiangcm/Lion)

- [arXiv 2023] Knowledge Distillation of Large Language Models. [[pdf]](https://arxiv.org/pdf/2306.08543.pdf) [[code]](https://github.com/microsoft/LMOps/tree/main/minillm)

- [arXiv 2023] Distilling Large Language Models for Biomedical Knowledge Extraction: A Case Study on Adverse Drug Events. [[pdf]](https://arxiv.org/pdf/2307.06439.pdf)

- [arXiv 2023] Web Content Filtering through knowledge distillation of Large Language Models. [[pdf]](https://arxiv.org/pdf/2305.05027.pdf)


### Harnessing LLM Annotations for Fine-Tuning and Prompting

#### In-Context Learning

#### Chain-of-Thought Prompting

#### Instruction Tuning

#### Alignment Tuning

<!-- ########################################### -->

## Surveys

Graph Reduction/ Summarization / Simplification

- **[Ours][arXiv 2024] A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation. [[pdf]](https://arxiv.org/abs/2402.03358)**
- [arXiv 2024] A Survey on Graph Condensation. [[pdf]](https://arxiv.org/abs/2402.02000)

## Toolkits

- Mongoose: [[pdf]](https://people.clas.ufl.edu/hager/files/mongoose.pdf) [[code]](https://github.com/ScottKolo/Mongoose)