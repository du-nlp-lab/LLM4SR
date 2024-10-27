# [LLM4SR: A Survey on Large Language Models for Scientific Research](https://arxiv.org)

<!-- ### :star: News! We have released a comprehensive survey. -->

<!-- <p align="center">
  <img src="assets/tax.png" alt="TAX" style="display: block; margin: 0 auto;" />
</p> -->

This is a repository for organizing papres, codes and other resources related to large language models for the scientific research process.

<!-- Hallucination in LLM usually refers to the phenomenon that the generated content is nonsensical or unfaithful to the provided source content, such as violation of input instruction, or containing factual errors, etc.
In the context of MLLM, hallucination refers to the phenomenon that the generated text is semantically coherent but inconsistent with the given visual content.
The community has been constantly making progress on analyzing, detecting, and mitigating hallucination in MLLM.

#### :books: How to read?
The main contribution of a specific paper is proposing either a new hallucination benchmark (metric) or proposing a hallucination mitigation method.
The analysis and detection of hallucination are only part of the whole paper, serving as the basis of evaluation and mitigation.
Therefore, we divide the papers into two categories: **hallucination evaluation & analysis ** and **hallucination mitigation**.
In each category, the paper are listd in an order **from new to old**.
Note that there might be some duplicated papers in the two categories. Those papers contain both evaluation benchmark and mitigation method.

#### :high_brightness: This project is still on-going, pull requests are welcomed!!

If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and pull a request. Just letting us know the title of papers can also be a great contribution to us. You can do this by open issue or contact us directly via email.

#### :star: If you find this repo useful, please star it!!! -->

## Table of Contents <!-- omit in toc -->

  - [LLMs for Scientific Hypothesis Discovery](#llms-for-scientific-hypothesis-discovery)
  - [LLMs for Experiment Planning and Implementation](#llms-for-experiment-planning-and-implementation)
  - [LLMs for Scientific Paper Writing](#llms-for-scientific-paper-writing)
  - [LLMs for Peer Reviewing](#llms-for-peer-reviewing)
    - [Automated Peer Reviewing Generation](#automated-peer-reviewing-generation)
      - [Peer Reviewing Tools](#peer-reviewing-tools)
    - [LLM-assisted Peer Reviewing Workflows](#llm-assisted-peer-reviewing-workflows)
    - [Benchmarks](#benchmarks)

## LLMs for Scientific Hypothesis Discovery

- **SciMON** [SciMON: Scientific Inspiration Machines Optimized for Novelty](https://arxiv.org/abs/2305.14259) (May. 23, 2023; ACL 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14259)

- **MOOSE** [Large Language Models for Automated Open-domain Scientific Hypotheses Discovery](https://arxiv.org/abs/2309.02726) (Sep. 6, 2023; ICML AI4Science Workshop Best Poster Award; ACL 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02726)

- **MCR** [Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design](https://arxiv.org/abs/2310.14420) (Oct. 22, 2023; EMNLP 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14420)

- [Large language models are zero shot hypothesis proposers](https://arxiv.org/abs/2311.05965) (Nov. 10, 2023; COLM 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.05965)

- **FunSearch** [Mathematical discoveries from program search with large language models](https://www.nature.com/articles/s41586-023-06924-6) (Dec. 14, 2023; Nature)

- **ChemReasoner** [ChemReasoner: Heuristic Search over a Large Language Model's Knowledge Space using Quantum-Chemical Feedback](https://arxiv.org/abs/2402.10980) (Feb. 15, 2024; ICML 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10980)

- **SGA** [LLM and Simulation as Bilevel Optimizers: A New Paradigm to Advance Physical Scientific Discovery](https://arxiv.org/abs/2405.09783) (May. 16, 2024; ICML 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.09783)

- **AIScientist** [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292) (Aug. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06292)

- **MLR-Copilot** [MLR-Copilot: Autonomous Machine Learning Research based on Large Language Models Agents](https://arxiv.org/abs/2408.14033) (Aug. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14033)

- **IGA** [Can llms generate novel research ideas? a large-scale human study with 100+ nlp researchers](https://arxiv.org/abs/2409.04109) (Sep. 6, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04109)

- **SciAgents** [SciAgents: Automating scientific discovery through multi-agent intelligent graph reasoning](https://arxiv.org/abs/2409.05556) (Sep. 9, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05556)

- **Scideator** [Scideator: Human-LLM Scientific Idea Generation Grounded in Research-Paper Facet Recombination](https://arxiv.org/abs/2409.14634) (Sep. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.14634)

- **MOOSE-Chem** [MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses](https://arxiv.org/abs/2410.07076) (Oct. 9, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07076)
  [![Star](https://img.shields.io/github/stars/ZonglinY/MOOSE-Chem%20)](https://github.com/ZonglinY/MOOSE-Chem)


- **VirSci** [Two Heads Are Better Than One: A Multi-Agent System Has the Potential to Improve Scientific Idea Generation](https://arxiv.org/abs/2410.09403) (Oct. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.09403)

- **CoI** [Chain of Ideas: Revolutionizing Research in Novel Idea Development with LLM Agents](https://arxiv.org/abs/2410.13185) (Oct. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13185)

- **Nova** [Nova: An Iterative Planning and Search Approach to Enhance Novelty and Diversity of LLM Generated Ideas](https://arxiv.org/abs/2410.14255) (Oct. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14255)

- [Hallucination of Multimodal Large Language Models: A Survey](https://arxiv.org/abs/2404.18930) (Apr. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.18930)

---

## LLMs for Experiment Planning and Implementation

- **EventHallusion** [Diagnosing Event Hallucinations in Video LLMs](https://arxiv.org/abs/2409.16597) (Sep. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16597)
  [![Star](https://img.shields.io/github/stars/Stevetich/EventHallusion.svg?style=social&label=Star)](https://github.com/Stevetich/EventHallusion)

- **FIHA** [Autonomous Hallucination Evaluation in Vision-Language Models with Davidson Scene Graphs](https://arxiv.org/abs/2409.13612) (Sep. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13612)

- **QL-Bench** [Explore the Hallucination on Low-level Perception for MLLMs](https://www.arxiv.org/abs/2409.09748) (Sep. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.09748)

- **ODE** [Open-Set Evaluation of Hallucinations in Multimodal Large Language Models](https://web3.arxiv.org/abs/2409.09318) (Sep. 14, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://web3.arxiv.org/abs/2409.09318)

- **Pfram** [Understanding Multimodal Hallucination with Parameter-Free Representation Alignment](https://arxiv.org/abs/2409.01151) (Sep. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01151)
  [![Star](https://img.shields.io/github/stars/yellow-binary-tree/Pfram.svg?style=social&label=Star)](https://github.com/yellow-binary-tree/Pfram)

- [Pre-Training Multimodal Hallucination Detectors with Corrupted Grounding Data](https://arxiv.org/abs/2409.00238) (Aug. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.00238)

- **Reefknot** [Reefknot: A Comprehensive Benchmark for Relation Hallucination Evaluation, Analysis and Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2408.09429) (Aug. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09429)

- **Hallu-PI** [Hallu-PI: Evaluating Hallucination in Multi-modal Large Language Models within Perturbed Inputs](https://arxiv.org/abs/2408.01355) (Aug. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.01355)
  [![Star](https://img.shields.io/github/stars/NJUNLP/Hallu-PI.svg?style=social&label=Star)](https://github.com/NJUNLP/Hallu-PI)

- **HaloQuest** [HaloQuest: A Visual Hallucination Dataset for Advancing Multimodal Reasoning](https://arxiv.org/abs/2407.15680) (Jul. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.15680)

- **ROPE** [Multi-Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2407.06192) (Jul. 08, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06192)
  [![Star](https://img.shields.io/github/stars/sled-group/moh.svg?style=social&label=Star)](https://github.com/sled-group/moh)

- **BEAF** [BEAF: Observing BEfore-AFter Changes to Evaluate Hallucination in Vision-language Models](https://arxiv.org/abs/2407.13442) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.13442)
  [![Star](https://img.shields.io/github/stars/postech-ami/BEAF.svg?style=social&label=Star)](https://github.com/postech-ami/BEAF)

- **VideoHallucer** [VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models](https://arxiv.org/abs/2406.16338) (Jun. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16338)
  [![Star](https://img.shields.io/github/stars/patrick-tssn/VideoHallucer.svg?style=social&label=Star)](https://github.com/patrick-tssn/VideoHallucer)

- **HQHBench** [Evaluating the Quality of Hallucination Benchmarks for Large Vision-Language Models](https://arxiv.org/abs/2406.17115) (Jun. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17115)
  [![Star](https://img.shields.io/github/stars/HQHBench/HQHBench.svg?style=social&label=Star)](https://github.com/HQHBench/HQHBench)

- [Does Object Grounding Really Reduce Hallucination of Large Vision-Language Models?](https://arxiv.org/abs/2406.14492v1) (Jun. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14492v1)

- **VGA** [VGA: Vision GUI Assistant -- Minimizing Hallucinations through Image-Centric Fine-Tuning](https://arxiv.org/abs/2406.14056) (Jun. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.14056)

- [Do More Details Always Introduce More Hallucinations in LVLM-based Image Captioning?](https://arxiv.org/abs/2406.12663v1) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12663v1)

- **MFC-Bench** [MFC-Bench: Benchmarking Multimodal Fact-Checking with Large Vision-Language Models](https://arxiv.org/abs/2406.11288) (Jun. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11288)

- **AutoHallusion** [AUTOHALLUSION: Automatic Generation of Hallucination Benchmarks for Vision-Language Models](https://arxiv.org/abs/2406.10900v1) (Jun. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10900v1)

- **Med-HallMark** [Detecting and Evaluating Medical Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2406.10185) (Jun. 14, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10185)

- **MetaToken** [MetaToken: Detecting Hallucination in Image Descriptions by Meta Classification](https://arxiv.org/abs/2405.19186) (May. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.19186)

- **THRONE** [THRONE: An Object-based Hallucination Benchmark for the Free-form Generations of Large Vision-Language Models](https://arxiv.org/abs/2405.05256) (May. 08, 2024, CVPR 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05256)

- **VALOR-EVAL** [VALOR-EVAL: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models](https://arxiv.org/abs/2404.13874) (Apr. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13874)
  [![Star](https://img.shields.io/github/stars/haoyiq114/VALOR.svg?style=social&label=Star)](https://github.com/haoyiq114/VALOR)

- **ALOHa** [ALOHa: A New Measure for Hallucination in Captioning Models](https://arxiv.org/abs/2404.02904v1) (Apr. 03, 2024, NAACL 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02904v1)

- **UPD** [Unsolvable Problem Detection: Evaluating Trustworthiness of Vision Language Models](https://arxiv.org/abs/2403.20331) (Mar. 29, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.20331)
  [![Star](https://img.shields.io/github/stars/AtsuMiyai/UPD.svg?style=social&label=Star)](https://github.com/AtsuMiyai/UPD)

- **IllusionVQA** [IllusionVQA: A Challenging Optical Illusion Dataset for Vision Language Models](https://arxiv.org/abs/2403.15952) (Mar. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15952)

- **CounterAnimal** [Do CLIPs Always Generalize Better than ImageNet Models ?](https://arxiv.org/abs/2403.11497) (Mar. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.11497)

- **PhD** [PhD: A Prompted Visual Hallucination Evaluation Dataset](https://arxiv.org/abs/2403.11116) (Mar. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.11116)

- [AIGCs Confuse AI Too: Investigating and Explaining Synthetic Image-induced Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2403.08542) (Mar. 13, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08542)

- **Hal-Eval** [Hal-Eval: A Universal and Fine-grained Hallucination Evaluation Framework for Large Vision Language Models](https://arxiv.org/abs/2402.15721) (Feb. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15721)

- **VHTest** [Visual Hallucinations of Multi-modal Large Language Models](https://arxiv.org/abs/2402.14683v1) (Feb. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14683v1)
  [![Star](https://img.shields.io/github/stars/wenhuang2000/VHTest.svg?style=social&label=Star)](https://github.com/wenhuang2000/VHTest)

- **MAD-Bench** [How Easy is It to Fool Your Multimodal LLMs? An Empirical Analysis on Deceptive Prompts](https://arxiv.org/abs/2402.13220) (Feb. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.13220)

- **MHaluBench** [Unified Hallucination Detection for Multimodal Large Language Models](https://arxiv.org/abs/2402.03190) (Feb. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03190)
  [![Star](https://img.shields.io/github/stars/OpenKG-ORG/EasyDetect.svg?style=social&label=Star)](https://github.com/OpenKG-ORG/EasyDetect)

- **VQAv2-IDK** [Visually Dehallucinative Instruction Generation: Know What You Don't Know](https://arxiv.org/abs/2402.09717) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09717)

- **CorrelationQA** [The Instinctive Bias: Spurious Images lead to Hallucination in MLLMs](https://arxiv.org/abs/2402.03757) (Feb. 06, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03757)
  [![Star](https://img.shields.io/github/stars/MasaiahHan/CorrelationQA.svg?style=social&label=Star)](https://github.com/MasaiahHan/CorrelationQA)

- **MMVP** [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209) (Jan. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.06209)

- **MOCHa (OpenCHAIR)** [MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations](https://arxiv.org/abs/2312.03631) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03631)
  [![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star)](https://github.com/assafbk/mocha_code)

- **FGHE** [Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites](https://arxiv.org/abs/2312.01701) (Dec. 04, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.01701)
  [![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star)](https://github.com/Anonymousanoy/FOHE)

- **MERLIM** [Behind the Magic, MERLIM: Multi-modal Evaluation Benchmark for Large Image-Language Models](https://arxiv.org/abs/2312.02219) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02219)

- **CCEval** [HallE-Switch: Controlling Object Hallucination in Large Vision Language Models](https://arxiv.org/abs/2310.01779v2) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01779v2)
  [![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star)](https://github.com/bronyayang/HallE_Switch)

- **HallusionBench** [HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination & Visual Illusion in Large Vision-Language Models](https://arxiv.org/abs/2310.14566) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14566)

- **RAH-Bench** [Mitigating Hallucination in Visual Language Models with Visual Supervision](https://arxiv.org/abs/2311.16479) (Nov. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16479)

- **AMBER** [An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation](https://arxiv.org/abs/2311.07397) (Nov. 13, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07397)
  [![Star](https://img.shields.io/github/stars/junyangwang0410/AMBER.svg?style=social&label=Star)](https://github.com/junyangwang0410/AMBER)

- **Bingo** [Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges](https://arxiv.org/abs/2311.03287) (Nov. 7, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.03287)
  [![Star](https://img.shields.io/github/stars/gzcch/Bingo.svg?style=social&label=Star)](https://github.com/gzcch/Bingo)

- **FAITHSCORE** [FAITHSCORE: Evaluating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2311.01477) (Nov. 2, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.01477)
  [![Star](https://img.shields.io/github/stars/bcdnlp/FAITHSCORE.svg?style=social&label=Star)](https://github.com/bcdnlp/FAITHSCORE)

- **HaELM** [Evaluation and Analysis of Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2308.15126) (Oct. 10, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.15126)
  [![Star](https://img.shields.io/github/stars/junyangwang0410/HaELM.svg?style=social&label=Star)](https://github.com/junyangwang0410/HaELM)

- **NOPE** [Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models](https://arxiv.org/abs/2310.05338) (Oct. 9, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.05338)

- **LRV (GAVIE)** [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565) (Sep., 29 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14565)
  [![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star)](https://github.com/FuxiaoLiu/LRV-Instruction)

- **MMHal-Bench** [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2306.14565) (Sep. 25, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14525)
  [![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)](https://github.com/llava-rlhf/LLaVA-RLHF)

- **CIEM** [CIEM: Contrastive Instruction Evaluation Method for Better Instruction Tuning](https://arxiv.org/abs/2309.02301) (NeurlPS Workshop)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02301)

- **POPE** [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2305.10355) (EMNLP 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10355)
  [![Star](https://img.shields.io/github/stars/AoiDragon/POPE.svg?style=social&label=Star)](https://github.com/AoiDragon/POPE)

- **CHAIR** [Object Hallucination in Image Captioning](https://arxiv.org/abs/1809.02156) (EMNLP 2018)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1809.02156)

---

## LLMs for Scientific Paper Writing

- **MemVR** [Look Twice Before You Answer: Memory-Space Visual Retracing for Hallucination Mitigation in Multimodal Large Language Models](https://arxiv.org/abs/2410.03577) (Oct. 7, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03577)
  [![Star](https://img.shields.io/github/stars/1zhou-Wang/MemVR.svg?style=social&label=Star)](https://github.com/1zhou-Wang/MemVR)
- **HELPD** [Mitigating Hallucination of LVLMs by Hierarchical Feedback Learning with Vision-enhanced Penalty Decoding](https://www.arxiv.org/abs/2409.20429) (Sep. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.20429)

- **Dentist** [A Unified Hallucination Mitigation Framework for Large Vision-Language Models](https://www.arxiv.org/abs/2409.16494) (Sep. 22, TMLR, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2409.16494)

- **PACU** [Effectively Enhancing Vision Language Large Models by Prompt Augmentation and Caption Utilization](https://arxiv.org/abs/2409.14484) (Sep. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.14484)

- **RBD** [Mitigating Hallucination in Visual-Language Models via Re-Balancing Contrastive Decoding](https://arxiv.org/abs/2409.06485) (Sep. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.06485)

- **MVP** [Look, Compare, Decide: Alleviating Hallucination in Large Vision-Language Models via Multi-View Multi-Path Reasoning](https://arxiv.org/abs/2408.17150) (Aug. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.17150)
  [![Star](https://img.shields.io/github/stars/GasolSun36/MVP.svg?style=social&label=Star)](https://github.com/GasolSun36/MVP)

- **ConVis** [Contrastive Decoding with Hallucination Visualization for Mitigating Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2408.13906) (Aug. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13906)
  [![Star](https://img.shields.io/github/stars/yejipark-m/ConVis.svg?style=social&label=Star)](https://github.com/yejipark-m/ConVis)

- **CLIP-DPO** [Vision-Language Models as a Source of Preference for Fixing Hallucinations in LVLMs](https://www.arxiv.org/abs/2408.10433) (Aug. 19, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.10433)

- **SID** [Self-Introspective Decoding: Alleviating Hallucinations for Large Vision-Language Models](https://www.arxiv.org/abs/2408.02032) (Aug. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.02032)
  [![Star](https://img.shields.io/github/stars/huofushuo/SID.svg?style=social&label=Star)](https://github.com/huofushuo/SID)

- **ARA** [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation](https://arxiv.org/abs/2408.00555) (Aug. 01, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.00555)

- **PAI** [Paying More Attention to Image: A Training-Free Method for Alleviating Hallucination in LVLMs](https://arxiv.org/abs/2407.21771) (Jul. 31, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21771)
  [![Star](https://img.shields.io/github/stars/LALBJ/PAI.svg?style=social&label=Star)](https://github.com/LALBJ/PAI)

- **MAD** [Interpreting and Mitigating Hallucination in MLLMs through Multi-agent Debate](https://arxiv.org/abs/2407.20505) (Jul. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.20505)
  [![Star](https://img.shields.io/github/stars/LZzz2000/HalluciMAD.svg?style=social&label=Star)](https://github.com/LZzz2000/HalluciMAD)

- **VACoDe** [VACoDe: Visual Augmented Contrastive Decoding](https://www.arxiv.org/abs/2408.05337) (Jul. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2408.05337)

- **REVERIE** [Reflective Instruction Tuning: Mitigating Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2407.11422) (Jul. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.11422)
  [![Star](https://img.shields.io/github/stars/zjr2000/REVERIE.svg?style=social&label=Star)](https://github.com/zjr2000/REVERIE)

- **BACON** [BACON: Supercharge Your VLM with Bag-of-Concept Graph to Mitigate Hallucinations](https://arxiv.org/abs/2407.03314) (Jul. 03, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03314)
  [![Star](https://img.shields.io/github/stars/ztyang23/BACON.svg?style=social&label=Star)](https://github.com/ztyang23/BACON)

- **Pelican** [Pelican: Correcting Hallucination in Vision-LLMs via Claim Decomposition and Program of Thought Verification](https://arxiv.org/abs/2407.02352) (Jul. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.02352)

- **MMHalSnowball** [Investigating and Mitigating the Multimodal Hallucination Snowballing in Large Vision-Language Models](https://www.arxiv.org/abs/2407.00569) (Jun. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2407.00569)
  [![Star](https://img.shields.io/github/stars/whongzhong/MMHalSnowball.svg?style=social&label=Star)](https://github.com/whongzhong/MMHalSnowball)

- **AGLA** [AGLA: Mitigating Object Hallucinations in Large Vision-Language Models with Assembly of Global and Local Attention](https://arxiv.org/abs/2406.12718) (Jun. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12718)
  [![Star](https://img.shields.io/github/stars/Lackel/AGLA.svg?style=social&label=Star)](https://github.com/Lackel/AGLA)

- **MedThink** [MedThink: Inducing Medical Large-scale Visual Language Models to Hallucinate Less by Thinking More](https://arxiv.org/abs/2406.11451) (Jun. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.11451)

- **TUNA** [Reminding Multimodal Large Language Models of Object-aware Knowledge with Retrieved Tags](https://arxiv.org/abs/2406.10839) (Jun. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10839)

- **CODE** [CODE: Contrasting Self-generated Description to Combat Hallucination in Large Multi-modal Models](https://arxiv.org/abs/2406.01920v1) (Jun. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01920v1)

- **NoiseBoost** [NoiseBoost: Alleviating Hallucination with Noise Perturbation for Multimodal Large Language Models](https://arxiv.org/abs/2405.20081) (May. 30, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20081)

- **RITUAL** [RITUAL: Random Image Transformations as a Universal Anti-hallucination Lever in LVLMs](https://arxiv.org/abs/2405.17821) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17821)
  [![Star](https://img.shields.io/github/stars/sangminwoo/RITUAL.svg?style=social&label=Star)](https://github.com/sangminwoo/RITUAL)

- **HALVA** [Mitigating Object Hallucination via Data Augmented Contrastive Tuning](https://www.arxiv.org/abs/2405.18654) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.arxiv.org/abs/2405.18654)

- **AvisC** [Don't Miss the Forest for the Trees: Attentional Vision Calibration for Large Vision Language Models](https://arxiv.org/abs/2405.17820) (May. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17820)
  [![Star](https://img.shields.io/github/stars/sangminwoo/AvisC.svg?style=social&label=Star)](https://github.com/sangminwoo/AvisC)

- **RLAIF-V** [RLAIF-V: Aligning MLLMs through Open-Source AI Feedback for Super GPT-4V Trustworthiness](https://arxiv.org/abs/2405.17220) (May. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17220)
  [![Star](https://img.shields.io/github/stars/RLHF-V/RLAIF-V.svg?style=social&label=Star)](https://github.com/RLHF-V/RLAIF-V)

- **HIO** [Alleviating Hallucinations in Large Vision-Language Models through Hallucination-Induced Optimization](https://arxiv.org/abs/2405.15356v1) (May. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15356v1)

- **VDGD** [VDGD: Mitigating LVLM Hallucinations in Cognitive Prompts by Bridging the Visual Perception Gap](https://arxiv.org/abs/2405.15683) (May. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15683)

- **VFC** [Visual Fact Checker: Enabling High-Fidelity Detailed Caption Generation](https://arxiv.org/abs/2404.19752) (Apr. 30, 2024 (CVPR 2024))
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.19752)

- **SoM-LLaVA** [List Items One by One: A New Data Source and Learning Paradigm for Multimodal LLMs](https://arxiv.org/abs/2404.16375) (Apr. 25, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16375)
  [![Star](https://img.shields.io/github/stars/zzxslp/SoM-LLaVA.svg?style=social&label=Star)](https://github.com/zzxslp/SoM-LLaVA)

- **Cantor** [Cantor: Inspiring Multimodal Chain-of-Thought of MLLM](https://arxiv.org/abs/2404.16033) (Apr. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16033)
  [![Star](https://img.shields.io/github/stars/BillChan226/HALC.svg?style=social&label=Star)](https://github.com/ggg0919/cantor)

- **HSA-DPO** [Detecting and Mitigating Hallucination in Large Vision Language Models via Fine-Grained AI Feedback](https://arxiv.org/abs/2404.14233v1) (Apr. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.14233v1)

- **FACT** [Fact :Teaching MLLMs with Faithful, Concise and Transferable Rationales](https://arxiv.org/abs/2404.11129) (Apr. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.11129)

- **SeVa** [Self-Supervised Visual Preference Alignment](https://arxiv.org/abs/2404.10501) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10501)

- **DFTG** [Prescribing the Right Remedy: Mitigating Hallucinations in Large Vision-Language Models via Targeted Instruction Tuning](https://arxiv.org/abs/2404.10332) (Apr. 16, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10332)

- **FGAIF** [FGAIF: Aligning Large Vision-Language Models with Fine-grained AI Feedback](https://arxiv.org/abs/2404.05046) (Apr. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.05046)

- **ICD** [Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding](https://arxiv.org/abs/2403.18715) (ACL 2024, Mar. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.18715)

- **ESREAL** [Exploiting Semantic Reconstruction to Mitigate Hallucinations in Vision-Language Models](https://arxiv.org/abs/2403.16167) (Mar. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.16167)

- **Pensieve** [Pensieve: Retrospect-then-Compare Mitigates Visual Hallucination](https://arxiv.org/abs/2403.14401) (Mar. 21, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14401)

- **M3ID** [Multi-Modal Hallucination Control by Visual Information Grounding](https://arxiv.org/abs/2403.14003) (Mar. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14003)

- **DVP** [What if...?: Counterfactual Inception to Mitigate Hallucination Effects in Large Multimodal Models](https://arxiv.org/abs/2403.13513) (Mar. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.13513)

- **AIT** [Mitigating Dialogue Hallucination for Large Multi-modal Models via Adversarial Instruction Tuning](https://arxiv.org/abs/2403.10492) (Mar. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.10492)

- **HALC** [HALC: Object Hallucination Reduction via Adaptive Focal-Contrast Decoding](https://arxiv.org/abs/2403.00425) (Mar. 01, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.00425)
  [![Star](https://img.shields.io/github/stars/BillChan226/HALC.svg?style=social&label=Star)](https://github.com/BillChan226/HALC)

- **IBD** [IBD: Alleviating Hallucinations in Large Vision-Language Models via Image-Biased Decoding](https://arxiv.org/abs/2402.18476) (Feb. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.18476)

- **CGD** [Seeing is Believing: Mitigating Hallucination in Large Vision-Language Models via CLIP-Guided Decoding](https://arxiv.org/abs/2402.15300) (Feb. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15300)

- **Less is More** [Less is More: Mitigating Multimodal Hallucination from an EOS Decision Perspective](https://arxiv.org/abs/2402.14545) (Feb. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14545)
  [![Star](https://img.shields.io/github/stars/yuezih/less-is-more.svg?style=social&label=Star)](https://github.com/yuezih/less-is-more)

- **LogicCheckGPT** [Logical Closed Loop: Uncovering Object Hallucinations in Large Vision-Language Models](https://arxiv.org/abs/2402.11622) (Feb. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.11622)
  [![Star](https://img.shields.io/github/stars/Hyperwjf/LogicCheckGPT.svg?style=social&label=Star)](https://github.com/Hyperwjf/LogicCheckGPT)

- **POVID** [Aligning Modalities in Vision Large Language Models via Preference Fine-tuning](https://arxiv.org/abs/2402.11411) (Feb. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.11411)
  [![Star](https://img.shields.io/github/stars/YiyangZhou/POVID.svg?style=social&label=Star)](https://github.com/YiyangZhou/POVID)

- **EFUF** [EFUF: Efficient Fine-grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2402.09801) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09801)

- **IDK-Instruction** [Visually Dehallucinative Instruction Generation: Know What You Don't Know](https://arxiv.org/abs/2402.09717) (Feb. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09717)

- **MARINE** [Mitigating Object Hallucination in Large Vision-Language Models via Classifier-Free Guidance](https://arxiv.org/abs/2402.08680) (Feb. 13, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.08680)

- **Skip \n** [Skip \n: A Simple Method to Reduce Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2402.01345) (Feb. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01345)

- **ViGoR** [ViGoR: Improving Visual Grounding of Large Vision Language Models with Fine-Grained Reward Modeling](https://arxiv.org/abs/2402.06118) (Feb. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.06118)

- **LAR-LAF** [Enhancing Multimodal Large Language Models with Vision Detection Models: An Empirical Study](https://arxiv.org/abs/2401.17981) (Jan. 31, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.17981)

- **Silkie** [Silkie: Preference Distillation for Large Visual Language Models](https://arxiv.org/abs/2312.10665) (Dec. 17, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.10665)

- **HACL** [Hallucination Augmented Contrastive Learning for Multimodal Large Language Model](https://arxiv.org/abs/2312.06968) (Dec. 12, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.06968)

- **MOCHa (OpenCHAIR)** [MOCHa: Multi-Objective Reinforcement Mitigating Caption Hallucinations](https://arxiv.org/abs/2312.03631) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03631)
  [![Star](https://img.shields.io/github/stars/assafbk/mocha_code.svg?style=social&label=Star)](https://github.com/assafbk/mocha_code)

- **FGHE** [Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites](https://arxiv.org/abs/2312.01701) (Dec. 04, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.01701)
  [![Star](https://img.shields.io/github/stars/Anonymousanoy/FOHE.svg?style=social&label=Star)](https://github.com/Anonymousanoy/FOHE)

- **HallE-Switch** [HallE-Switch: Controlling Object Hallucination in Large Vision Language Models](https://arxiv.org/abs/2310.01779v2) (Dec. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01779v2)
  [![Star](https://img.shields.io/github/stars/bronyayang/HallE_Switch.svg?style=social&label=Star)](https://github.com/bronyayang/HallE_Switch)

- **RLHF-V** [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849) (Dec. 01, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00849)
  [![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V.svg?style=social&label=Star)](https://github.com/RLHF-V/RLHF-V)

- **OPERA** [OPERA: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation](https://arxiv.org/abs/2311.17911) (Nov. 29, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17911)
  [![Star](https://img.shields.io/github/stars/shikiw/OPERA.svg?style=social&label=Star)](https://github.com/shikiw/OPERA)

- **VCD** [Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding](https://arxiv.org/abs/2311.16922) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16922)
  [![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/VCD.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/VCD)

- **HA-DPO** [Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization](https://arxiv.org/abs/2311.16839) (Nov. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16839)

- **RAH-Bench** [Mitigating Hallucination in Visual Language Models with Visual Supervision](https://arxiv.org/abs/2311.16479) (Nov. 27, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16479)

- **HalluciDoctor** [HalluciDoctor: Mitigating Hallucinatory Toxicity in Visual Instruction Data](https://arxiv.org/abs/2311.13614) (Nov. 22, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.13614)
  [![Star](https://img.shields.io/github/stars/Yuqifan1117/HalluciDoctor.svg?style=social&label=Star)](https://github.com/Yuqifan1117/HalluciDoctor)

- **Volcano** [Volcano: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision](https://arxiv.org/abs/2311.07362) (Nov. 14, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.07362)
  [![Star](https://img.shields.io/github/stars/kaistAI/Volcano.svg?style=social&label=Star)](https://github.com/kaistAI/Volcano)

- **Woodpecker** [Woodpecker: Hallucination Correction for Multimodal Large Language Models](https://arxiv.org/abs/2310.16045) (Oct. 24, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.16045)
  [![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)

- **LURE** [Analyzing and Mitigating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2310.00754) (Oct. 1, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.00754)
  [![Star](https://img.shields.io/github/stars/YiyangZhou/LURE.svg?style=social&label=Star)](https://github.com/YiyangZhou/LURE)

- **LRV-Instruction** [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565) (Sep. 29, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.14565)
  [![Star](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction.svg?style=social&label=Star)](https://github.com/FuxiaoLiu/LRV-Instruction)

- **LLaVA-RLHF** [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2306.14565) (Sep. 25, 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.14525)
  [![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)](https://github.com/llava-rlhf/LLaVA-RLHF)

- **VIGC** [VIGC: Visual Instruction Generation and Correction](https://arxiv.org/abs/2308.12714) (Sep. 11, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.12714)
  [![Star](https://img.shields.io/github/stars/opendatalab/VIGC.svg?style=social&label=Star)](https://github.com/opendatalab/VIGC)

- **HalDectect** [Detecting and Preventing Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2308.06394) (Aug. 18, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.06394)

---

## LLMs for Peer Reviewing

- **Increasing-Use-of-LLMs** [Mapping the Increasing Use of LLMs in Scientific Papers](https://arxiv.org/abs/2404.01268v1) (Apr. 1, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01268v1)[![Star](https://img.shields.io/github/stars/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers.svg?style=social&label=Star)](https://github.com/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers)

- **Can-LLM-Provide-Useful-Feedback?** [Can large language models provide useful feedback on research papers? A large-scale empirical analysis](https://arxiv.org/abs/2310.01783) (Oct. 3, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01783)[![Star](https://img.shields.io/github/stars/weixin-liang/llm-scientific-feedback.svg?style=social&label=Star)](https://github.com/weixin-liang/llm-scientific-feedback)

- **NLP-for-Peer-Review** [What Can Natural Language Processing Do for Peer Review?](https://arxiv.org/abs/2405.06563) (May. 10, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.06563)[![Star](https://img.shields.io/github/stars/OAfzal/nlp-for-peer-review.svg?style=social&label=Star)](https://github.com/OAfzal/nlp-for-peer-review)

- **Monitoring AI-Modified Content** [Monitoring AI-Modified Content at Scale: A Case Study on the Impact of ChatGPT on AI Conference Peer Reviews](https://arxiv.org/abs/2403.07183v2) (Mar. 11, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07183v2)[![Star](https://img.shields.io/github/stars/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers.svg?style=social&label=Star)](https://github.com/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers)

- **Substantiation-Analysis** [Automatic Analysis of Substantiation in Scientific Peer Reviews](https://arxiv.org/abs/2311.11967v1) (Nov. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11967v1) [![Star](https://img.shields.io/github/stars/YanzhuGuo/SubstanReview.svg?style=social&label=Star)](https://github.com/YanzhuGuo/SubstanReview)

- **A Friend of a Foe?** [Artificial Intelligence in Scientific Writing: A Friend or a Foe?](https://pubmed.ncbi.nlm.nih.gov/37142479/) (Apr. 20, 2024)

- **LLM-Review-Sys** [The Emergence of Large Language Models (LLM) as a Tool in Literature Reviews: An LLM Automated Systematic Review](https://arxiv.org/abs/2409.04600v1) (Sep. 6, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04600v1)

- **Emerging Plagiarism** [Emerging Plagiarism in Peer-Review Evaluation Reports: A Tip of the Iceberg?](https://link.springer.com/article/10.1007/s11192-024-04960-1) (Feb. 29, 2024)

- **GPT4-Review-Study** [GPT-4 is Slightly Helpful for Peer-Review Assistance: A Pilot Study](https://arxiv.org/abs/2307.05492) (Jun. 16, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05492)

- **PR4PR** [Peer Reviews of Peer Reviews: A Randomized Controlled Trial and Other Experiments](https://arxiv.org/abs/2311.09497) (Nov. 16, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.09497)

### Automated Peer Reviewing Generation

- **LLM-MetaReview** [Prompting LLMs to Compose Meta-Review Drafts from Peer-Review Narratives of Scholarly Manuscripts](https://arxiv.org/abs/2402.15589v1) (Feb. 23, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15589v1)

- **SWIF2T** [Automated Focused Feedback Generation for Scientific Writing Assistance](https://arxiv.org/abs/2405.20477v2) (May. 30, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20477v2) [![Star](https://img.shields.io/github/stars/ericchamoun/FocusedFeedbackGeneration.svg?style=social&label=Star)](https://github.com/ericchamoun/FocusedFeedbackGeneration)

- **CGI2** [Scientific Opinion Summarization: Paper Meta-Review Generation Dataset, Methods, and Evaluation](https://arxiv.org/abs/2305.14647v3) (May. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14647v3) [![Star](https://img.shields.io/github/stars/mankeerat/orsum-meta-review-generation.svg?style=social&label=Star)](https://github.com/mankeerat/orsum-meta-review-generation)

- **ReviewRobot** [ReviewRobot: Explainable Paper Review Generation Based on Knowledge Synthesis](https://arxiv.org/abs/2010.06119v3) (INLG(ACL)2020) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2010.06119v3) [![Star](https://img.shields.io/github/stars/EagleW/ReviewRobot.svg?style=social&label=Star)](https://github.com/EagleW/ReviewRobot)

- **SEA** [Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis](https://arxiv.org/abs/2407.12857v2) (Jul. 9, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12857v2)[![Star](https://img.shields.io/github/stars/ecnu-sea/SEA.svg?style=social&label=Star)](https://github.com/ecnu-sea/SEA)

- **Reviewer2** [Reviewer2: Optimizing Review Generation Through Prompt Generation](https://arxiv.org/abs/2402.10886v1) (Feb. 16, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10886v1) [![Star](https://img.shields.io/github/stars/zhaolingao/reviewer2.svg?style=social&label=Star)](https://github.com/zhaolingao/reviewer2)

- **MARG** [MARG: Multi-Agent Review Generation for Scientific Papers](https://arxiv.org/abs/2401.04259v1) (Jan. 8, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04259v1) [![Star](https://img.shields.io/github/stars/allenai/marg-reviewer.svg?style=social&label=Star)](https://github.com/allenai/marg-reviewer)

#### Peer Reviewing Tools

- [ScholarGPT](https://chatgpt.com/g/g-kZ0eYXlJe-scholar-gpt)
- [SciSpace](https://typeset.io/)
- [Scite](https://scite.ai/)
- [Semantic Scholar](https://www.semanticscholar.org/)
- [Elicit](https://elicit.com/)
- [Perplexity](https://www.perplexity.ai/)
- [Consensus](https://consensus.app/)
- [Scholarcy](https://www.scholarcy.com/)

### LLM-assisted Peer Reviewing Workflows

- **ChatGPT-Journal-Reviews** [ChatGPT and the Future of Journal Reviews](https://pmc.ncbi.nlm.nih.gov/articles/PMC10524821/#:~:text=Contextual%20Understanding%20and%20Expertise%3A%20ChatGPT,accuracy%20of%20complex%20research%20findings.) (Sep. 29, 2023)

- **HumanInTheLoop-AI-Reviewing** [Human-in-the-loop AI Reviewing: Feasibility, Opportunities, and Risks](https://aisel.aisnet.org/jais/vol25/iss1/7/) (Jan. 1, 2024)

- **AI-Mediated Peer Review** [A Critical Examination of the Ethics of AI-Mediated Peer Review](https://arxiv.org/abs/2309.12356v1) (Sep. 2, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.12356v1)

- **AgentReview** [AGENTREVIEW: Exploring Peer Review Dynamics with LLM Agents](https://arxiv.org/abs/2406.12708v2) (Jun. 18, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12708v2) [![Star](https://img.shields.io/github/stars/ahren09/agentreview.svg?style=social&label=Star)](https://github.com/ahren09/agentreview)

- **PaperMage** [PaperMage: A Unified Toolkit for Processing, Representing, and Manipulating Visually-Rich Scientific Documents](https://aclanthology.org/2023.emnlp-demo.45.pdf) (ACL2023) [![Star](https://img.shields.io/github/stars/allenai/papermage.svg?style=social&label=Star)](https://github.com/allenai/papermage)

- **CocoSciSum** [CocoSciSum: A Scientific Summarization Toolkit with Compositional Controllability](https://aclanthology.org/2023.emnlp-demos.47) (EMNLP2023) [![Star](https://img.shields.io/github/stars/WING-NUS/SciAssist.svg?style=social&label=Star)](https://github.com/WING-NUS/SciAssist/tree/CocoSciSum)
- **ReviewerGPT** [ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing](https://arxiv.org/abs/2306.00622v1) (Jun. 1, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00622v1) [![Star](https://img.shields.io/github/stars/niharshah/ReviewerGPT2023.svg?style=social&label=Star)](https://github.com/niharshah/ReviewerGPT2023)

- **PaperQA2** [Language agents achieve superhuman synthesis of scientific knowledge](https://arxiv.org/abs/2409.13740) (Sep. 10, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13740)[![Star](https://img.shields.io/github/stars/future-house/paper-qa.svg?style=social&label=Star)](https://github.com/future-house/paper-qa)

- **ReviewFlow** [ReviewFlow: Intelligent Scaffolding to Support Academic Peer Reviewing](https://arxiv.org/abs/2402.03530) (Feb. 5, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03530)

- **CARE** [CARE: Collaborative AI-Assisted Reading Environment](https://arxiv.org/abs/2302.12611v1) (Feb. 24, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.12611v1) [![Star](https://img.shields.io/github/stars/UKPLab/CARE.svg?style=social&label=Star)](https://github.com/UKPLab/CARE)

### Benchmarks

- **MOPRD** [MOPRD: A Multidisciplinary Open Peer Review Dataset](https://arxiv.org/abs/2212.04972v2) (Dec. 9, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04972v2)

- **NLPeer** [NLPeer: A Unified Resource for the Computational Study of Peer Review](https://arxiv.org/abs/2211.06651v2) (Nov. 12, 2022) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.06651v2) [![Star](https://img.shields.io/github/stars/ukplab/nlpeer.svg?style=social&label=Star)](https://github.com/ukplab/nlpeer)

- **MReD** [MReD: A Meta-Review Dataset for Structure-Controllable Text Generation](https://arxiv.org/abs/2110.07474v6) (Findings(ACL)2022) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.07474v6) [![Star](https://img.shields.io/github/stars/shen-chenhui/mred.svg?style=social&label=Star)](https://github.com/shen-chenhui/mred)

- **PeerSum** [Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation](https://arxiv.org/abs/2305.01498v4) (May. 2, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.01498v4) [![Star](https://img.shields.io/github/stars/oaimli/peersum.svg?style=social&label=Star)](https://github.com/oaimli/peersum)

- **ORSUM** [Scientific Opinion Summarization: Paper Meta-Review Generation Dataset, Methods, and Evaluation](https://arxiv.org/abs/2305.14647v3) (May. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14647v3) [![Star](https://img.shields.io/github/stars/mankeerat/orsum-meta-review-generation.svg?style=social&label=Star)](https://github.com/mankeerat/orsum-meta-review-generation)

- **ASAP-Review** [Can We Automate Scientific Reviewing?](https://arxiv.org/abs/2102.00176v1) (Jan. 30, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.00176v1) [![Star](https://img.shields.io/github/stars/neulab/ReviewAdvisor.svg?style=social&label=Star)](https://github.com/neulab/ReviewAdvisor)

- **Reviewer2** [Reviewer2: Optimizing Review Generation Through Prompt Generation](https://arxiv.org/abs/2402.10886v1) (Feb. 16, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10886v1) [![Star](https://img.shields.io/github/stars/zhaolingao/reviewer2.svg?style=social&label=Star)](https://github.com/zhaolingao/reviewer2)
- **PeerRead** [A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications](https://arxiv.org/abs/1804.09635v1) (Apr. 25, 2018)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1804.09635v1) [![Star](https://img.shields.io/github/stars/allenai/PeerRead.svg?style=social&label=Star)](https://github.com/allenai/PeerRead)

- **CritiqueReview** [LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing](https://arxiv.org/abs/2406.16253) (Jun. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16253)[![Star](https://img.shields.io/github/stars/jiangshdd/reviewcritique.svg?style=social&label=Star)](https://github.com/jiangshdd/reviewcritique)

- **RR-MCQ** [Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks](https://aclanthology.org/2024.lrec-main.816/) (ACL2024)
