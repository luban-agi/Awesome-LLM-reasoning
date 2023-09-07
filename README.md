# Awesome LLM reasoning

<!-- <div style="text-align: center;">

    <h1><img src="assets/logo.png" height="28px" /> Awesome-LLM-reasoning </h1>

</div> -->



[![Awesome](https://awesome.re/badge.svg)](https://github.com/luban-agi/Awesome-LLM-reasoning) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/badge/PRs-Welcome-red)
<!---![](https://img.shields.io/github/last-commit/luban-agi/Awesome-LLM-reasoning) -->


Awesome papers on LLM reasoning.

## 📜 Table of Contents

- [📚 Papers](#-papers)
  - [📑 Survey](#-survey)
  - [🌟 Graph of Thought](#-graph-of-thought)
  - [📌 Backward Reasoning ](#-backward-reasoning)
    - [Backward Chaining](#backward-chaining)
    - [Question Decomposition](#question-decomposition)
  - [💪 Reasoning Enhancement for Small LM ](#-reasoning-enhancement-for-small-lm)
    - [Distillation](#distillation)
    - [Step-aware Reasoning](#step-aware-reasoning)
    - [Self-Training](#self-training)
<!--- [📱 Applications](#-applications)  -->
<!--- [🎉 Contributors](#-contributors) -->

## 📚 Papers

### 📑 Survey

- **Reasoning with Language Model Prompting: A Survey**, 2022.12 <br />
*Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen* [[abs](https://arxiv.org/abs/2212.09597)]

- **Towards Reasoning in Large Language Models: A Survey**, 2022.12 <br />
*Jie Huang, Kevin Chen-Chuan Chang* [[abs](https://arxiv.org/abs/2212.10403)]

- **A Survey of Deep Learning for Mathematical Reasoningy**, 2022.12 <br />
*Pan Lu, Liang Qiu, Wenhao Yu, Sean Welleck, Kai-Wei Chang* [[abs](https://arxiv.org/abs/2212.10535)]

- **Natural Language Reasoning, A Survey**, 2023.03 <br />
*Fei Yu, Hongbo Zhang, Prayag Tiwari, Benyou Wang* [[abs](https://arxiv.org/abs/2303.14725)]

### 🌟 Graph of Thought
- **Thinking Like an Expert:Multimodal Hypergraph-of-Thought (HoT) Reasoning to boost Foundation Modals**, 2023.08 <br />
*Fanglong Yao, Changyuan Tian, Jintao Liu, Zequn Zhang, Qing Liu, Li Jin, Shuchao Li, Xiaoyu Li, Xian Sun* [[abs](https://arxiv.org/abs/2308.06207)]

- **Beyond Chain-of-Thought, Effective Graph-of-Thought Reasoning in Large Language Models**, 2023.05 <br />
*Yao Yao, Zuchao Li, Hai Zhao* [[abs](https://arxiv.org/abs/2305.16582)]

- **Graph of Thoughts: Solving Elaborate Problems with Large Language Models**, 2023.08 <br />
*Maciej Besta, Nils Blach, Ales Kubicek, Robert Gerstenberger, Lukas Gianinazzi, Joanna Gajda, Tomasz Lehmann, Michal Podstawski, Hubert Niewiadomski, Piotr Nyczyk, Torsten Hoefler* [[abs](https://arxiv.org/abs/2308.09687)]

- **Boosting Logical Reasoning in Large Language Models through a New Framework: The Graph of Thought** 2023.08 <br />
*Bin Lei, pei-Hung Lin, Chunhua Liao, Caiwen Ding* [[abs](https://arxiv.org/abs/2308.08614)]

- **MindMap: Knowledge Graph Prompting Sparks Graph of Thoughts in Large Language Models** 2023.08 <br />
*Yilin Wen, Zifeng Wang, Jimeng Sun* [[abs](https://arxiv.org/abs/2308.09729)]
### 💡 With Graph
- **Structure-Aware Abstractive Conversation Summarization via Discourse and Action Graphs** 2021.04 <br />
*Jiaao Chen, Diyi Yang* [[abs](https://arxiv.org/abs/2308.06207)]

### 📌 Backward Reasoning 
#### Backward Chaining
- **METGEN: A module-based entailment tree generation framework for answer explanation** 2022.05 <br />
*Ruixin Hong, Hongming Zhang, Xintong Yu, Changshui Zhang* [[abs](https://arxiv.org/abs/2205.02593)]

- **LAMBADA: backward chaining for automated reasoning in natural language** 2022.12 <br />
*Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran* [[abs](https://arxiv.org/abs/2212.13894)]

- **Entailer: Answering questions with faithful and truthful chains of reasoning** 2022.10 <br />
*Oyvind Tafjord, Bhavana Dalvi Mishra, Peter Clark* [[abs](https://arxiv.org/abs/2210.12217)]

- **Interpretable proof generation via iterative backward reasoning** 2022.05 <br />
*Hanhao Qu, Yu Cao, Jun Gao, Liang Ding, Ruifeng Xu* [[abs](https://arxiv.org/abs/2205.10714)]

#### Question Decomposition
- **Multi-hop Reading Comprehension through Question Decomposition and Rescoring** 2019.06 <br />
*Sewon Min, Victor Zhong, Luke Zettlemoyer, Hannaneh Hajishirzi* [[abs](https://arxiv.org/abs/1906.02916)]

- **Is a question decomposition unit all we need** 2022.05 <br />
*Pruthvi Patel, Swaroop Mishra, Mihir Parmar, Chitta Baral* [[abs](https://arxiv.org/abs/2205.12538)]

- **Unsupervised question decomposition for question answering** 2020.02 <br />
*Ethan Perez, Patrick Lewis, Wen-tau Yih, Kyunghyun Cho, Douwe Kiela* [[abs](https://arxiv.org/abs/2002.09758)]

- **Text modular networks: Learning to decompose tasks in the language of existing models** 2021.04 <br />
*Tushar Khot, Daniel Khashabi, Kyle Richardson, Peter Clark, Ashish Sabharwal* [[abs](https://arxiv.org/abs/2009.00751)]

- **Measuring and narrowing the compositionality gap in language models** 2022.10 <br />
*Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis*  [[abs](https://arxiv.org/abs/2210.03350)]

- **Least-to-most prompting enables complex reasoning in large language models** 2022.05 <br />
  *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi*  [[abs](https://arxiv.org/abs/2205.10625)]

- **Learning to decompose: Hypothetical question decomposition based on comparable texts** 2022.10 <br />
*Ben Zhou, Kyle Richardson, Xiaodong Yu, Dan Roth* [[abs](https://arxiv.org/abs/2210.16865)]

### 💪 Reasoning Enhancement for Small LM
Objective: Enhance the Reasoning capability of small-scale LM models (<10B) and improve their performance on tasks such as mathematical reasoning, symbolic reasoning, common-sense reasoning, and task planning to achieve a level comparable to that of large-scale models (>100B).

#### Distillation
- **Symbolic Chain-of-Thought Distillation: Small Models Can Also “Think” Step-by-Step** 2023.06 <br />
*Liunian Harold Li, Jack Hessel, Youngjae Yu, Xiang Ren, Kai-Wei Chang, Yejin Choi* [[abs](https://arxiv.org/abs/2306.14050)]

- **Large Language Models Are Reasoning Teachers** 2023.06 <br />
*Namgyu Ho, Laura Schmid, Se-Young Yun* [[abs](https://arxiv.org/abs/2212.10071)]

- **Distilling Step-by-Step! Outperforming Larger Language Models with Less Training Data and Smaller Model Sizes** 2023.05 <br />
*Cheng-Yu Hsieh, Chun-Liang Li, Chih-Kuan Yeh, Hootan Nakhost, Yasuhisa Fujii, Alexander Ratner, Ranjay Krishna, Chen-Yu Lee, Tomas Pfister* [[abs](https://arxiv.org/abs/2305.02301)]

- **Distilling reasoning capabilities into smaller language models** 2023.07 <br />
*Shridhar K, Stolfo A, Sachan M. Distilling * [[abs](https://aclanthology.org/2023.findings-acl.441.pdf)]

- **Teaching Small Language Models to Reason** 2023.11 <br />
*Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn* [[abs](https://arxiv.org/abs/2212.08410)]

- **Explanations from Large Language Models Make Small Reasoners Better** 2022.10 <br />
*Shiyang Li, Jianshu Chen, Yelong Shen, Zhiyu Chen, Xinlu Zhang, Zekun Li, Hong Wang, Jing Qian, Baolin Peng, Yi Mao, Wenhu Chen, Xifeng Yan* [[abs](https://arxiv.org/abs/2210.06726)]

- **PINTO: Faithful Language Reasoning Using Prompt-Generated Rationales** 2022.11 <br />
*Peifeng Wang, Aaron Chan, Filip Ilievski, Muhao Chen, Xiang Ren* [[abs](https://arxiv.org/abs/2211.01562)]

#### Step-aware Reasoning
- **Training Verifiers to Solve Math Word Problems** 2021.10 <br />
*Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman* [[abs](https://arxiv.org/abs/2110.14168)]

- **Solving Math Word Problems via Cooperative Reasoning induced Language Models** 2022.10 <br />
*Xinyu Zhu, Junjie Wang, Lin Zhang, Yuxiang Zhang, Yongfeng Huang, Ruyi Gan, Jiaxing Zhang, Yujiu Yang* [[abs](https://arxiv.org/abs/2210.16257)]

- **Making Large Language Models Better Reasoners with Step-Aware Verifier** 2022.06 <br />
*Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen* [[abs](https://arxiv.org/abs/2206.02336)]


####  Self-Training

- **STaR: Bootstrapping Reasoning With Reasoning** 2022.03 <br />
*Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman* [[abs](https://arxiv.org/abs/2203.14465)]


- **Large Language Models Can Self-improve** 2022.10 <br />
*Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han* [[abs](https://arxiv.org/abs/2210.11610)]




<!---
## 🎉 Contributors
<a href="https://github.com/luban-agi/Awesome-Tool-Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=luban-agi/Awesome-Tool-Learning"/>

</a>
-->
