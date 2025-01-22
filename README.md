# [LLM4SR: A Survey on Large Language Models for Scientific Research](https://arxiv.org/abs/2501.04306)
Authors: [Ziming Luo*](https://zimingluo.github.io/), [Zonglin Yang*](https://zongliny.github.io/), [Zexin Xu](https://github.com/du-nlp-lab/LLM4SR/edit/main/README.md), [Wei Yang](https://github.com/du-nlp-lab/LLM4SR/edit/main/README.md), [Xinya Du](https://xinyadu.github.io/)

<!-- ### :star: News! We have released a comprehensive survey. -->

<!-- <p align="center">
  <img src="assets/tax.png" alt="TAX" style="display: block; margin: 0 auto;" />
</p> -->

This is a repository for organizing papres, codes and other resources related to large language models for the scientific research process.
<p align="center">
  <img src="assets/schematic_overview.png" alt="TAX" style="display: block; margin: 0 auto;" />
</p>

#### :books: How to read?
Schematic overview of the scientific research pipeline covered in this survey. This cyclical process begins with scientific hypothesis discovery, followed by experiment planning and implementation, paper writing, and finally peer reviewing of papers. The experiment planning stage consists of optimizing experiment
design and executing research tasks, while the paper writing stage consists of citation text generation, related work generation, and drafting & writing.
Those papers contain both task-specific methods and evaluation benchmarks. Note that there might be some duplicated papers in the two categories.

#### :high_brightness: This project is still on-going, pull requests are welcomed!!

If you have any suggestions (missing papers, new papers, key researchers or typos), please feel free to edit and pull a request. Just letting us know the title of papers can also be a great contribution to us. You can do this by open issue or contact us directly via email.

#### :star: If you find this repo useful, please star it!!! -->

## Table of Contents <!-- omit in toc -->

  * [LLMs for Scientific Hypothesis Discovery](#llms-for-scientific-hypothesis-discovery)
  * [LLMs for Experiment Planning and Implementation](#llms-for-experiment-planning-and-implementation)
    - [Optimizing Experimental Design](#optimizing-experimental-design)
    + [Automating Experimental Processes](#automating-experimental-processes)
      - [Data Preparation](#data-preparation)
      - [Experiment Execution and Workflow Automation](#experiment-execution-and-workflow-automation)
      - [Data Analysis and Interpretation](#data-analysis-and-interpretation)
    + [Benchmarks](#benchmarks)
  * [LLMs for Scientific Paper Writing](#llms-for-scientific-paper-writing)
    + [Citation Text Generation](#citation-text-generation)
    + [Related Work Generation](#related-work-generation)
    + [Drafting andWriting](#drafting-andwriting)
    + [Benchmarks](#benchmarks-1)
  * [LLMs for Peer Reviewing](#llms-for-peer-reviewing)
    + [Automated Peer Reviewing Generation](#automated-peer-reviewing-generation)
      - [Peer Reviewing Tools](#peer-reviewing-tools)
    + [LLM-assisted Peer Reviewing Workflows](#llm-assisted-peer-reviewing-workflows)
    + [Benchmarks](#benchmarks-2)


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

- **MOOSE-Chem** [MOOSE-Chem: Large Language Models for Rediscovering Unseen Chemistry Scientific Hypotheses](https://arxiv.org/abs/2410.07076) (Oct. 9, 2024; ICLR 2025)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07076)
  [![Star](https://img.shields.io/github/stars/ZonglinY/MOOSE-Chem%20)](https://github.com/ZonglinY/MOOSE-Chem)

- **VirSci** [Two Heads Are Better Than One: A Multi-Agent System Has the Potential to Improve Scientific Idea Generation](https://arxiv.org/abs/2410.09403) (Oct. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.09403)

- **CoI** [Chain of Ideas: Revolutionizing Research in Novel Idea Development with LLM Agents](https://arxiv.org/abs/2410.13185) (Oct. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13185)

- **Nova** [Nova: An Iterative Planning and Search Approach to Enhance Novelty and Diversity of LLM Generated Ideas](https://arxiv.org/abs/2410.14255) (Oct. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14255)

---
## LLMs for Experiment Planning and Implementation

### Optimizing Experimental Design

- **Coscientist** [Autonomous chemical research with large language models](https://doi.org/10.1038/s41586-023-06792-0) (Dec. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.1038/s41586-023-06792-0)
  
- **ChemCrow** [Augmenting large language models with chemistry tools](https://doi.org/10.1038/S42256-024-00832-8[) (May. 08, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.1038/S42256-024-00832-8[)
  
- **CRISPR-GPT** [CRISPR-GPT: An LLM Agent for Automated Design of Gene-Editing Experiments](https://doi.org/10.48550/ARXIV.2404.18021) (Arp. 27, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/ARXIV.2404.18021)
  
- **Navigating Complexity** [Navigating Complexity: Orchestrated Problem Solving with Multi-Agent LLMs](https://arxiv.org/abs/2402.16713) (Jul. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.16713)
  
- **HuggingGPT** [HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face](https://arxiv.org/abs/2303.17580) (Dec. 03, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.17580)
  
- **AutoGen** [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://doi.org/10.48550/ARXIV.2308.08155) (Oct. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/ARXIV.2308.08155)
  
- **LLM-RDF** [An automatic end-to-end chemical synthesis development platform powered by large language models](https://www.nature.com/articles/s41467-024-54457-x) (Nov. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.nature.com/articles/s41467-024-54457-x) 
  
- [Simulating Expert Discussions with Multi-agent for Enhanced Scientific Problem Solving](https://aclanthology.org/2024.sdp-1.23/) (Jan. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2024.sdp-1.23/)

### Automating Experimental Processes

#### Data Preparation

- **Data-Juicer** [Data-Juicer: A One-Stop Data Processing System for Large Language Models](https://arxiv.org/abs/2309.02033) (Dec. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.02033)
  
- **Jellyfish** [Jellyfish: A Large Language Model for Data Preprocessing](https://arxiv.org/abs/2312.01678) (Oct. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.01678)
  
- [Can Large Language Models Transform Computational Social Science?](hhttps://arxiv.org/abs/2305.03514) (Feb. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](hhttps://arxiv.org/abs/2305.03514) 
  
- **CAAFE** [Large Language Models for Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering](https://arxiv.org/abs/2305.03403) (Sep. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03403)
  
- [Are you in a Masquerade? Exploring the Behavior and Impact of Large Language Model Driven Social Bots in Online Social Networks.](https://arxiv.org/abs/2307.10337) (Jun. 19, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.10337)
  
- [Training Socially Aligned Language Models in Simulated Human Society](https://arxiv.org/abs/2305.16960) (Oct. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.16960)
  
#### Experiment Execution and Workflow Automation

- **ESM-1b** [Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](https://www.pnas.org/doi/full/10.1073/pnas.2016239118) (Dec. 16, 2020)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.pnas.org/doi/full/10.1073/pnas.2016239118) 
  
- **ESM-2** [Evolutionary-scale prediction of atomic-level protein structure with a language model](https://www.science.org/doi/10.1126/science.ade2574) (Mar. 16, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.science.org/doi/10.1126/science.ade2574)
  
- [Controllable protein design with language models](https://arxiv.org/abs/2201.07338) (Aug. 22, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2201.07338)
  
- **PALM-H3** [De novo generation of SARS-CoV-2 antibody CDRH3 with a pre-trained generative large
  language model](https://www.nature.com/articles/s41467-024-50903-y) (Aug. 10, 2024
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.nature.com/articles/s41467-024-50903-y)
  
- **Coscientist** [Autonomous chemical research with large language models](https://doi.org/10.1038/s41586-023-06792-0) (Dec. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.1038/s41586-023-06792-0)
  
- **ChemCrow** [Augmenting large language models with chemistry tools](https://doi.org/10.1038/S42256-024-00832-8) (May. 08, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.1038/S42256-024-00832-8)
  
- [Efficient Evolutionary Search Over Chemical Space with Large Language Models](https://arxiv.org/abs/2406.16976) (Jul. 02 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16976)

- **ChatDrug** [Conversational Drug Editing Using Retrieval and Domain Feedback](https://arxiv.org/abs/2305.18090) (May. 29, 2023)
  ![arXiv](https://arxiv.org/abs/2305.18090)
  
- **DrugAssist** [DrugAssist: A Large Language Model for Molecule Optimization](https://arxiv.org/abs/2401.10334) (Dec. 28, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.10334)
  
- [Bayesian Optimization of Catalysts With In-context Learning](https://arxiv.org/abs/2304.05341) (Apr. 18, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05341)
  
- [Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design](https://arxiv.org/abs/2310.14420) (Oct. 22, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.14420) 
  
- **ChemReasoner** [CHEMREASONER: Heuristic Search over a Large Language Model’s Knowledge Space using Quantum-Chemical Feedback](https://arxiv.org/abs/2402.10980) (Dec. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10980) 

#### Data Analysis and Interpretation

- [Automated Statistical Model Discovery with Language Models](https://arxiv.org/abs/2402.17879) (Jun. 22, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17879) 

- **MentaLLaMA** [MentaLLaMA: Interpretable Mental Health Analysis on Social Media with Large Language Models](https://arxiv.org/abs/2309.13567) (Feb. 04, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.13567)

- [Can Large Language Models Serve as Data Analysts? A Multi-Agent Assisted Approach for
  Qualitative Data Analysis](https://arxiv.org/abs/2402.01386) (Feb. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01386)

- [Opening a conversation on responsible environmental data science in the age of large language models](https://www.cambridge.org/core/journals/environmental-data-science/article/opening-a-conversation-on-responsible-environmental-data-science-in-the-age-of-large-language-models/95FD09526541A19436F3A18ADE332953) (May. 09, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.cambridge.org/core/journals/environmental-data-science/article/opening-a-conversation-on-responsible-environmental-data-science-in-the-age-of-large-language-models/95FD09526541A19436F3A18ADE332953) 

- **DSBench** [DSBench: How Far Are Data Science Agents to Becoming Data Science Experts?](https://arxiv.org/abs/2409.07703) (Sep. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07703) 

- **AutoGen** [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation Framework](https://doi.org/10.48550/ARXIV.2308.08155) (Oct. 03, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://doi.org/10.48550/ARXIV.2308.08155)

- [LLM-in-the-loop: Leveraging Large Language Model for Thematic Analysis](https://aclanthology.org/2023.findings-emnlp.669/) (Oct. 23, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2023.findings-emnlp.669/)

### Benchmarks

- **SUPER** [SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories](https://arxiv.org/abs/2409.07440) (Sep. 11, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)]((https://arxiv.org/abs/2409.07440)
  
- **MLE-bench** [MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering](https://arxiv.org/abs/2410.07095) (Dec. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.07095)
  
- **ScienceAgentBench** [ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery](https://arxiv.org/abs/2410.05080) (Oct. 07, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.05080) 
  
- **Spider2-V** [Spider2-V: How Far Are Multimodal Agents From Automating Data Science and Engineering Workflows?](https://arxiv.org/abs/2407.10956) (Jul. 15, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10956)
  
- **MLAgentBench** [MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation](https://arxiv.org/abs/2310.03302) (Oct. 05, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.03302)
  
- **DiscoveryWorld** [DiscoveryWorld: A Virtual Environment for Developing and Evaluating Automated Scientific Discovery Agents](https://arxiv.org/abs/2406.06769) (Jun. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06769) 
  
- **DSBench** [DSBench: How Far Are Data Science Agents to Becoming Data Science Experts?](https://arxiv.org/abs/2409.07703) (Sep. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.07703)
  
- **DS-1000** [DS-1000: A Natural and Reliable Benchmark for Data Science Code Generation](https://arxiv.org/abs/2211.11501) (Nov. 18, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.11501)
  
- **LAB-Bench** [LAB-Bench: Measuring Capabilities of Language Models for Biology Research](https://arxiv.org/abs/2407.10362) (Jul. 14, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.10362)
  
- **AgentBench** [AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688) (Aug. 07, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.03688)
  
- **TaskBench** [TaskBench: Benchmarking Large Language Models for Task Automation](https://arxiv.org/abs/2311.18760) (Nov. 30, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.18760) 
  
- **CORE-Bench** [CORE-Bench: Fostering the Credibility of Published Research Through a Computational Reproducibility Agent Benchmark](https://arxiv.org/abs/2409.11363) (Sep. 17, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.11363)

---

## LLMs for Scientific Paper Writing

### Citation Text Generation

* [Automatic Generation of Citation Texts in Scholarly Papers: A Pilot Study](https://aclanthology.org/2020.acl-main.550/) (July. 30, 2020)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2020.acl-main.550/) 
  
* [Explaining Relationships Among Research Papers](https://arxiv.org/abs/2402.13426) (Feb. 20, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.13426)

- **AutoCite** [AutoCite: Multi-Modal Representation Fusion for Contextual Citation Generation](https://dl.acm.org/doi/10.1145/3437963.3441739) (Mar. 08,  2021)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3437963.3441739)

- **BACO** [BACO: A Background Knowledge- and Content-Based Framework for Citing Sentence Generation](https://aclanthology.org/2021.acl-long.116/) (Aug. 1, 2021)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2021.acl-long.116/)

- [Controllable Citation Sentence Generation with Language Models](https://arxiv.org/abs/2211.07066) (Nov. 14, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.07066)

- [Intent-Controllable Citation Text Generation](https://www.mdpi.com/2227-7390/10/10/1763) (May. 21, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.mdpi.com/2227-7390/10/10/1763)

### Related Work Generation

- [Shallow Synthesis of Knowledge in GPT-Generated Texts: A Case Study in Automatic Related Work Composition](https://arxiv.org/abs/2402.12255) (Feb. 19, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.12255)
  
- [Leveraging Large Language Models for Literature Review Tasks - A Case Study Using ChatGPT](https://link.springer.com/chapter/10.1007/978-3-031-48858-0_25) (Dec. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-48858-0_25)
  
- **LitLLM** [LitLLM: A Toolkit for Scientific Literature Review](https://arxiv.org/abs/2402.01788) (Fe. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01788) 
  
- **HiReview** [HiReview: Hierarchical Taxonomy-Driven Automatic Literature Review Generation](https://arxiv.org/abs/2410.03761) (Oct. 02, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.03761) 
  
- [Towards a Unified Framework for Reference Retrieval and Related Work Generation](https://aclanthology.org/2023.findings-emnlp.385) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2023.findings-emnlp.385)
  
- [Automating Research Synthesis with Domain-Specific Large Language Model Fine-Tuning](https://arxiv.org/abs/2404.08680) (Apr. 08, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.08680)
  
- [Reinforced Subject-Aware Graph Neural Network for Related Work Generation](https://link.springer.com/chapter/10.1007/978-981-97-5492-2_16) (Jul. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-981-97-5492-2_16)
  
- [Toward Structured Related Work Generation with Novelty Statements](https://aclanthology.org/2024.sdp-1.5) (Jul. 26, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2024.sdp-1.5)

### Drafting andWriting

- [Generating Scientific Definitions with Controllable Complexity](https://aclanthology.org/2022.acl-long.569) (May. 22, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2022.acl-long.569)

- **SciCap** [SciCap: Generating Captions for Scientific Figures](https://aclanthology.org/2021.findings-emnlp.277) (Nov. 07, 2021)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2021.findings-emnlp.277)

- **CoAuthor** [CoAuthor: Designing a Human-AI Collaborative Writing Dataset for Exploring Language Model Capabilities](https://arxiv.org/abs/2407.02352) (Apr. 29, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.02352) 

- [Autonomous LLM-driven research from data to human-verifiable research papers](https://arxiv.org/abs/2404.17605) (Apr. 24, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.17605)

- **PaperRobot** [PaperRobot: Incremental Draft Generation of Scientific Ideas](https://aclanthology.org/P19-1191) (Jun. 28, 2019)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/P19-1191) 

- **AutoSurvey** [AutoSurvey: Large Language Models Can Automatically Write Surveys](https://arxiv.org/abs/2406.10252) (Jun. 10, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10252) 

- **AI Scientist** [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292) (Aug. 12, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06292)

- **CycleResearcher** [CycleResearcher: Improving Automated Research via Automated Review](https://arxiv.org/abs/2411.00816) (Oct. 28, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.00816) 

### Benchmarks

- [Enabling Large Language Models to Generate Text with Citations](https://aclanthology.org/2023.emnlp-main.398) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2023.emnlp-main.398)
  
- [CiteBench: A Benchmark for Scientific Citation Text Generation](https://aclanthology.org/2023.emnlp-main.455) (Dec. 06, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2023.emnlp-main.455) 
  
- **SciGen** [SciGen: a Dataset for Reasoning-Aware Text Generation from Scientific Tables](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/149e9677a5989fd342ae44213df68868-Abstract-round2.html) (May. 23, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/149e9677a5989fd342ae44213df68868-Abstract-round2.html)
  
- **SciXGen** [SciXGen: A Scientific Paper Dataset for Context-Aware Text Generation](https://aclanthology.org/2021.findings-emnlp.128) (Nov. 7, 2021)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://aclanthology.org/2021.findings-emnlp.128)

---

## LLMs for Peer Reviewing

- **LLM-Review-Sys** [The Emergence of Large Language Models (LLM) as a Tool in Literature Reviews: An LLM Automated Systematic Review](https://arxiv.org/abs/2409.04600v1) (Sep. 6, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04600v1)

- **NLP-for-Peer-Review** [What Can Natural Language Processing Do for Peer Review?](https://arxiv.org/abs/2405.06563) (May. 10, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.06563)[![Star](https://img.shields.io/github/stars/OAfzal/nlp-for-peer-review.svg?style=social&label=Star)](https://github.com/OAfzal/nlp-for-peer-review)

- **A Friend of a Foe?** [Artificial Intelligence in Scientific Writing: A Friend or a Foe?](https://pubmed.ncbi.nlm.nih.gov/37142479/) (Apr. 20, 2024)

- **Increasing-Use-of-LLMs** [Mapping the Increasing Use of LLMs in Scientific Papers](https://arxiv.org/abs/2404.01268v1) (Apr. 1, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01268v1)[![Star](https://img.shields.io/github/stars/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers.svg?style=social&label=Star)](https://github.com/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers)

- **Monitoring AI-Modified Content** [Monitoring AI-Modified Content at Scale: A Case Study on the Impact of ChatGPT on AI Conference Peer Reviews](https://arxiv.org/abs/2403.07183v2) (Mar. 11, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07183v2)[![Star](https://img.shields.io/github/stars/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers.svg?style=social&label=Star)](https://github.com/Weixin-Liang/Mapping-the-Increasing-Use-of-LLMs-in-Scientific-Papers)

- **Emerging Plagiarism** [Emerging Plagiarism in Peer-Review Evaluation Reports: A Tip of the Iceberg?](https://link.springer.com/article/10.1007/s11192-024-04960-1) (Feb. 29, 2024)

- **Substantiation-Analysis** [Automatic Analysis of Substantiation in Scientific Peer Reviews](https://arxiv.org/abs/2311.11967v1) (Nov. 20, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11967v1) [![Star](https://img.shields.io/github/stars/YanzhuGuo/SubstanReview.svg?style=social&label=Star)](https://github.com/YanzhuGuo/SubstanReview)

- **PR4PR** [Peer Reviews of Peer Reviews: A Randomized Controlled Trial and Other Experiments](https://arxiv.org/abs/2311.09497) (Nov. 16, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.09497)

- **Can-LLM-Provide-Useful-Feedback?** [Can large language models provide useful feedback on research papers? A large-scale empirical analysis](https://arxiv.org/abs/2310.01783) (Oct. 3, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.01783)[![Star](https://img.shields.io/github/stars/weixin-liang/llm-scientific-feedback.svg?style=social&label=Star)](https://github.com/weixin-liang/llm-scientific-feedback)

- **GPT4-Review-Study** [GPT-4 is Slightly Helpful for Peer-Review Assistance: A Pilot Study](https://arxiv.org/abs/2307.05492) (Jun. 16, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.05492)

### Automated Peer Reviewing Generation

- **SEA** [Automated Peer Reviewing in Paper SEA: Standardization, Evaluation, and Analysis](https://arxiv.org/abs/2407.12857v2) (Jul. 9, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12857v2)[![Star](https://img.shields.io/github/stars/ecnu-sea/SEA.svg?style=social&label=Star)](https://github.com/ecnu-sea/SEA)

- **SWIF2T** [Automated Focused Feedback Generation for Scientific Writing Assistance](https://arxiv.org/abs/2405.20477v2) (May. 30, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20477v2) [![Star](https://img.shields.io/github/stars/ericchamoun/FocusedFeedbackGeneration.svg?style=social&label=Star)](https://github.com/ericchamoun/FocusedFeedbackGeneration)

- **CGI2** [Scientific Opinion Summarization: Paper Meta-Review Generation Dataset, Methods, and Evaluation](https://arxiv.org/abs/2305.14647v3) (May. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14647v3) [![Star](https://img.shields.io/github/stars/mankeerat/orsum-meta-review-generation.svg?style=social&label=Star)](https://github.com/mankeerat/orsum-meta-review-generation)

- **LLM-MetaReview** [Prompting LLMs to Compose Meta-Review Drafts from Peer-Review Narratives of Scholarly Manuscripts](https://arxiv.org/abs/2402.15589v1) (Feb. 23, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.15589v1)

- **Reviewer2** [Reviewer2: Optimizing Review Generation Through Prompt Generation](https://arxiv.org/abs/2402.10886v1) (Feb. 16, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10886v1) [![Star](https://img.shields.io/github/stars/zhaolingao/reviewer2.svg?style=social&label=Star)](https://github.com/zhaolingao/reviewer2)

- **MARG** [MARG: Multi-Agent Review Generation for Scientific Papers](https://arxiv.org/abs/2401.04259v1) (Jan. 8, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.04259v1) [![Star](https://img.shields.io/github/stars/allenai/marg-reviewer.svg?style=social&label=Star)](https://github.com/allenai/marg-reviewer)

- **ReviewRobot** [ReviewRobot: Explainable Paper Review Generation Based on Knowledge Synthesis](https://arxiv.org/abs/2010.06119v3) (INLG(ACL)2020) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2010.06119v3) [![Star](https://img.shields.io/github/stars/EagleW/ReviewRobot.svg?style=social&label=Star)](https://github.com/EagleW/Review

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

- **AI-Mediated Peer Review** [A Critical Examination of the Ethics of AI-Mediated Peer Review](https://arxiv.org/abs/2309.12356v1) (Sep. 2, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.12356v1)

- **AgentReview** [AGENTREVIEW: Exploring Peer Review Dynamics with LLM Agents](https://arxiv.org/abs/2406.12708v2) (Jun. 18, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12708v2) [![Star](https://img.shields.io/github/stars/ahren09/agentreview.svg?style=social&label=Star)](https://github.com/ahren09/agentreview)

- **ReviewerGPT** [ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing](https://arxiv.org/abs/2306.00622v1) (Jun. 1, 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00622v1) [![Star](https://img.shields.io/github/stars/niharshah/ReviewerGPT2023.svg?style=social&label=Star)](https://github.com/niharshah/ReviewerGPT2023)

- **ReviewFlow** [ReviewFlow: Intelligent Scaffolding to Support Academic Peer Reviewing](https://arxiv.org/abs/2402.03530) (Feb. 5, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03530)

- **HumanInTheLoop-AI-Reviewing** [Human-in-the-loop AI Reviewing: Feasibility, Opportunities, and Risks](https://aisel.aisnet.org/jais/vol25/iss1/7/) (Jan. 1, 2024)

- **CocoSciSum** [CocoSciSum: A Scientific Summarization Toolkit with Compositional Controllability](https://aclanthology.org/2023.emnlp-demos.47) (EMNLP2023) [![Star](https://img.shields.io/github/stars/WING-NUS/SciAssist.svg?style=social&label=Star)](https://github.com/WING-NUS/SciAssist/tree/CocoSciSum)

- **PaperMage** [PaperMage: A Unified Toolkit for Processing, Representing, and Manipulating Visually-Rich Scientific Documents](https://aclanthology.org/2023.emnlp-demo.45.pdf) (ACL2023) [![Star](https://img.shields.io/github/stars/allenai/papermage.svg?style=social&label=Star)](https://github.com/allenai/papermage)

- **PaperQA2** [Language agents achieve superhuman synthesis of scientific knowledge](https://arxiv.org/abs/2409.13740) (Sep. 10, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.13740)[![Star](https://img.shields.io/github/stars/future-house/paper-qa.svg?style=social&label=Star)](https://github.com/future-house/paper-qa)

- **ChatGPT-Journal-Reviews** [ChatGPT and the Future of Journal Reviews](https://pmc.ncbi.nlm.nih.gov/articles/PMC10524821/#:~:text=Contextual%20Understanding%20and%20Expertise%3A%20ChatGPT,accuracy%20of%20complex%20research%20findings.) (Sep. 29, 2023)

- **CARE** [CARE: Collaborative AI-Assisted Reading Environment](https://arxiv.org/abs/2302.12611v1) (Feb. 24, 2023) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.12611v1) [![Star](https://img.shields.io/github/stars/UKPLab/CARE.svg?style=social&label=Star)](https://github.com/UKPLab/CARE)

### Benchmarks

- **CritiqueReview** [LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing](https://arxiv.org/abs/2406.16253) (Jun. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16253)[![Star](https://img.shields.io/github/stars/jiangshdd/reviewcritique.svg?style=social&label=Star)](https://github.com/jiangshdd/reviewcritique)

- **ORSUM** [Scientific Opinion Summarization: Paper Meta-Review Generation Dataset, Methods, and Evaluation](https://arxiv.org/abs/2305.14647v3) (May. 24, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.14647v3) [![Star](https://img.shields.io/github/stars/mankeerat/orsum-meta-review-generation.svg?style=social&label=Star)](https://github.com/mankeerat/orsum-meta-review-generation)

- **RR-MCQ** [Is LLM a Reliable Reviewer? A Comprehensive Evaluation of LLM on Automatic Paper Reviewing Tasks](https://aclanthology.org/2024.lrec-main.816/) (ACL2024)

- **Reviewer2** [Reviewer2: Optimizing Review Generation Through Prompt Generation](https://arxiv.org/abs/2402.10886v1) (Feb. 16, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.10886v1) [![Star](https://img.shields.io/github/stars/zhaolingao/reviewer2.svg?style=social&label=Star)](https://github.com/zhaolingao/reviewer2)

- **ASAP-Review** [Can We Automate Scientific Reviewing?](https://arxiv.org/abs/2102.00176v1) (Jan. 30, 2024) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2102.00176v1) [![Star](https://img.shields.io/github/stars/neulab/ReviewAdvisor.svg?style=social&label=Star)](https://github.com/neulab/ReviewAdvisor)

- **PeerSum** [Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation](https://arxiv.org/abs/2305.01498v4) (May. 2, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.01498v4) [![Star](https://img.shields.io/github/stars/oaimli/peersum.svg?style=social&label=Star)](https://github.com/oaimli/peersum)

- **MOPRD** [MOPRD: A Multidisciplinary Open Peer Review Dataset](https://arxiv.org/abs/2212.04972v2) (Dec. 9, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04972v2)

- **NLPeer** [NLPeer: A Unified Resource for the Computational Study of Peer Review](https://arxiv.org/abs/2211.06651v2) (Nov. 12, 2022) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.06651v2) [![Star](https://img.shields.io/github/stars/ukplab/nlpeer.svg?style=social&label=Star)](https://github.com/ukplab/nlpeer)

- **MReD** [MReD: A Meta-Review Dataset for Structure-Controllable Text Generation](https://arxiv.org/abs/2110.07474v6) (Findings(ACL)2022) [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.07474v6) [![Star](https://img.shields.io/github/stars/shen-chenhui/mred.svg?style=social&label=Star)](https://github.com/shen-chenhui/mred)

- **PeerRead** [A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications](https://arxiv.org/abs/1804.09635v1) (Apr. 25, 2018)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1804.09635v1) [![Star](https://img.shields.io/github/stars/allenai/PeerRead.svg?style=social&label=Star)](https://github.com/allenai/PeerRead)



## Citation

If you find this code useful in your research, please consider citing:

```
@misc{luo2025llm4srsurveylargelanguage,
      title={LLM4SR: A Survey on Large Language Models for Scientific Research}, 
      author={Ziming Luo and Zonglin Yang and Zexin Xu and Wei Yang and Xinya Du},
      year={2025},
      eprint={2501.04306},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2501.04306}, 
}
```
