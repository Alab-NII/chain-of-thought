# Chain-of-thought
Summarize and classify related papers about CoT.

## Original work on CoT:
- First release time: 28 Jan 2022
- Title: [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
- Conference: NeurIPS 2022

## Content
- [Related Surveys](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#related-surveys)
- [COT Enhancement](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#cot-enhancement)
- [Two main types of CoTs](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#two-main-types-of-cots)
- [Why CoT works? - Analysis of CoT](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#why-cot-works---analysis-of-cot)
- [CoT Evaluation](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#cot-evaluation)
- [Other types of CoTs](https://github.com/Alab-NII/chain-of-thought/blob/main/README.md#other-types-of-cots)

## Related Surveys
|First release time|Title|Conference|
|---|---| --- |
|27 Sep 2023| [A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future](https://arxiv.org/abs/2309.15402)| arXiv |
|  15 Feb 2023   |  [Augmented Language Models: a Survey](https://arxiv.org/pdf/2302.07842.pdf)   |  arXiv   |
|   4 Jan 2023  |  [Iterated Decomposition: Improving Science Q&A by Supervising Reasoning Processes](https://arxiv.org/abs/2301.01751)   |  arXiv   |
|  20 Dec 2022   |  [Towards Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2212.10403)   |  ACL 23 Findings   |
| 19 Dec 2022 | [Reasoning with Language Model Prompting: A Survey](https://arxiv.org/abs/2212.09597)  | ACL 2023   |

## COT Enhancement
|First release time|Title|What Changes?|
|21 Mar 2022| [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171)| naive greedy decoding => self-consistency |

## Two main types of CoTs
### Zero-shot:
|First release time|Title|Conference|
|---|---| --- |
|  6 May 2023 |  [Plan-and-Solve Prompting: Improving Zero-Shot Chain-of-Thought Reasoning by Large Language Models](https://arxiv.org/abs/2305.04091)  |  ACL 23  |
|  3 Nov 2022  |  [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/abs/2211.01910)  |  ICLR 23  |
|  24 May 2022  | [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916)   |  NeurIPS2022  |

### Few-shot: five sub-groups
- Related to code generation
- Auto CoT
- Iterative prompt CoT
- Involve question decomposition
- Mix

#### Related to code generation
|First release time|Title|Conference|
|---|---| --- |
|  22 Nov 2022  | [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/abs/2211.12588)  |  arXiv  |
| 18 Nov 2022   | [PAL: Program-aided Language Models](https://arxiv.org/pdf/2211.10435.pdf)  |  ICML 2023  |
 |  13 Oct 2022  | [Language models of code are few-shot commonsense learners](https://aclanthology.org/2022.emnlp-main.90.pdf)  |  EMNLP 2022  |


#### Involve question decomposition
|First release time|Title|Conference|
|---|---| --- |
|  8 Dec 2022    |  [Successive Prompting for Decomposing Complex Questions](https://aclanthology.org/2022.emnlp-main.81.pdf)   |    EMNLP 2022   |
|   7 Oct 2022   |  [Measuring and Narrowing the Compositionality Gap in Language Models](https://arxiv.org/pdf/2210.03350.pdf)   |    arXiv   |
|  5 Oct 2022    |  [Decomposed Prompting: A Modular Approach for Solving Complex Tasks ](https://arxiv.org/pdf/2210.02406.pdf)   |     ICLR 2023   |
|  21 May 2022    |  [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625)   |    ICLR 2023   |
|   19 May 2022   |  [Selection-Inference: Exploiting Large Language Models for Interpretable Logical Reasoning](https://arxiv.org/abs/2205.09712)   |   arXiv    |
|  15 May 2022    |  [SeqZero: Few-shot Compositional Semantic Parsing with Sequential Prompts and Zero-shot Models](https://aclanthology.org/2022.findings-naacl.5/)   |   Findings of NAACL 2022    |


#### Auto CoT
|First release time|Title|Conference|
|---|---| --- |
|  24 Feb 2023   |  [Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data](https://arxiv.org/abs/2302.12822)   |   arXiv |
|  7 Oct 2022   |  [Automatic Chain of Thought Prompting in Large Language Models](https://arxiv.org/abs/2210.03493)   |   ICLR 23    |


## Why CoT works? - Analysis of CoT
|First release time|Title|Conference|
|---|---| --- |
|  20 Dec 2022   |   [Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters](https://aclanthology.org/2023.acl-long.153/)  |  ACL 2023   |
|   25 Nov 2022  |   [Complementary Explanations for Effective In-Context Learning](https://aclanthology.org/2023.findings-acl.273/)  |  ACL 2023 (Findings)   |
|  3 Oct 2022   |  [Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought](https://arxiv.org/abs/2210.01240)   |   ICLR 2023   |
|  16 Sep 2022   |  [Text and Patterns: For Effective Chain of Thought, It Takes Two to Tango](https://arxiv.org/abs/2209.07686)   |  Google Research   |


## CoT Evaluation

## Other types of CoTs
|First release time|Name | Title|Conference|
|---|---| ---| --- |
|   28 May 2023   |  Tab-CoT |  [Tab-CoT: Zero-shot Tabular Chain of Thought](https://arxiv.org/abs/2305.17812)  |  ACL 23 Findings    |
|   17 May 2023   | Tree of Thoughts |  [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/abs/2305.10601)  |  arXiv    |
|  9 May 2023    |  Memory of Thoughts|  [MoT: Pre-thinking and Recalling Enable ChatGPT to Self-Improve with Memory-of-Thoughts](https://arxiv.org/abs/2305.05181)  |    arXiv  |
|  22 Nov 2022    | Program of Thoughts |  [Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks](https://arxiv.org/abs/2211.12588)   |   arXiv   |
