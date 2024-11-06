# Awesome AI in Game

**Note:** A daily compilation of fascinating AI insights, perfect for enhancing game development or gameplay to meet personal requirements. 🎮🤖 (Generated by Microsoft Copilot 😊)

**Feel free to open an issue or shoot me an email if you come across any interesting papers, projects, researchers, or if you find that my understanding is not correct.**

## Table of Contents
### Paper
- [Awesome AI in Game](#awesome-ai-in-game)
  - [Table of Contents](#table-of-contents)
    - [Paper](#paper)
    - [Environment](#environment)
    - [Project](#project)
  - [Paper](#paper-1)
    - [Survey](#survey)
    - [Game Making](#game-making)
      - [Animation](#animation)
    - [Game Environment](#game-environment)
      - [PCG (Procedural Content Generation)](#pcg-procedural-content-generation)
      - [Playable Video Generation](#playable-video-generation)
    - [Game Agent](#game-agent)
      - [Text-based](#text-based)
      - [FPS](#fps)
    - [Misc](#misc)
  - [Environment](#environment-1)
    - [RPG](#rpg)
  - [Project](#project-1)
    - [LLM](#llm)
  - [Acknowledgement](#acknowledgement)
### Environment
- [RPG](#rpg)
### Project
- [LLM](#llm-1)

## Paper
### Survey
> [!NOTE]
> **Highlight Authors**
> - Julian Togelius [Homepage](http://julian.togelius.com/) [Google Scholar](https://scholar.google.com/citations?user=lr4I9BwAAAAJ&hl=en)


- **Large Language Models and Games: A Survey and Roadmap** [Arxiv](https://arxiv.org/html/2402.18659v1)
  - Roberto Gallotta, Graham Todd, Marvin Zammit, Sam Earle, Antonios Liapis, Julian Togelius, Georgios N. Yannakakis
  - 28 Feb 2024
### Game Making
#### Animation
> [!NOTE]
> **Highlight Authors**
> - Xue Bin (Jason) Peng [Homepage](https://xbpeng.github.io/) [Google Scholar](https://scholar.google.ca/citations?user=FwxfQosAAAAJ&hl=en)
> - Michiel van de Panne [Homepage](https://www.cs.ubc.ca/~van/) [Google Scholar](https://scholar.google.ca/citations?user=lJwPbcUAAAAJ&hl=en)
> - C. Karen Liu [Lab Page](https://tml.stanford.edu/) [Google Scholar](https://scholar.google.com/citations?user=i28fU0MAAAAJ&hl=en)
> - Zhaoming Xie [Homepage](https://zhaomingxie.github.io/) [Google Scholar](https://scholar.google.ca/citations?user=qDsqFkMAAAAJ&hl=en)
> - Sebastian Starke [Homepage](https://www.sebastianxstarke.com/) [Google Scholar](https://scholar.google.com/citations?user=ScpOkvAAAAAJ&hl=en) **Super cool Homepage!!!**


- **Interactive Character Control with Auto-Regressive Motion Diffusion Models** [Arxiv](https://arxiv.org/abs/2306.00416), [Project](https://yi-shi94.github.io/amdm_page/)
  - Yi Shi, Jingbo Wang, Xuekun Jiang, Bingkun Lin, Bo Dai, Xue Bin Peng
  - **Date**: 16 Aug 2024
  - **Summary**: (AMDM) Propose an auto-regressive diffusion model for kinematic motion synthesis and conduct extensive experiments and comparisons to demonstrate the superiority of this method.
  - **Data**: 100STYLE, AMASS, LaFAN1
  - **Metrics**: APD(Average Pairwise Distance), ADE(Average Displacement Error), FDE(Final Displacement Error), Bone Length Error, Pen.Freq(foot penetration frequency), Pen.Dist(average foot penetration distance), FS(foot sliding), Jnt.Accel(joint acceleration)


- **PADL: Language-Directed Physics-Based Character Control** [Arxiv](https://arxiv.org/abs/2408.14837)
  - Jordan Juravsky, Yunrong Guo, Sanja Fidler, Xue Bin Peng
  - 30 Nov 2022

- **A Survey on Reinforcement Learning Methods in Character Animation** [Arxiv](https://arxiv.org/abs/2203.04735)
  - Kwiatkowski, Ariel and Alvarado, Eduardo and Kalogeiton, Vicky and Liu, C. Karen and Pettré, Julien and van de Panne, Michiel and Cani, Marie‐Paule
  - 7 Mar 2022

- **AMP: Adversarial Motion Priors for Stylized Physics-Based Character Control** [Arxiv](https://arxiv.org/abs/2104.02180)
  - Xue Bin Peng, Ze Ma, Pieter Abbeel, Sergey Levine, Angjoo Kanazawa
  - 5 Apr 2021

- **DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills** [Arxiv](https://arxiv.org/abs/1804.02717)
  - Peng, Xue Bin and Abbeel, Pieter and Levine, Sergey and van de Panne, Michiel
  - 27 Jul 2018

### Game Environment
#### PCG (Procedural Content Generation)
- **Procedural Content Generation via Machine Learning (PCGML)** [Arxiv](https://arxiv.org/abs/1702.00539)
  - Adam Summerville, Sam Snodgrass, Matthew Guzdial, Christoffer Holmgård, Amy K. Hoover, Aaron Isaksen, Andy Nealen, Julian Togelius
  - **Date**: 7 May 2018
  - **Summary**: Survey paper on procedural content generation via machine learning, including traditional methods, machine learning methods, use cases and open problems.
#### Playable Video Generation
- **Diffusion Models Are Real-Time Game Engines** [Arxiv](https://arxiv.org/abs/2408.14837), [Project](https://gamengen.github.io/)
  - Dani Valevski, Yaniv Leviathan, Moab Arar, Shlomi Fruchter
  - **Date**: 27 Aug 2024
  - **Summary**: GameNGen, the first game engine powered entirely by a neural model that enables real-time interaction with a complex environment over long trajec- tories at high quality.
  - **Data**: VisDoom + RL
  - **Metrics**: PSNR, LPIPS, Human Eval

- **Genie: Generative Interactive Environments** [Arxiv](https://arxiv.org/abs/2402.15391), [Project](https://sites.google.com/view/genie-2024/home)
  - Jake Bruce, Michael Dennis, Ashley Edwards, Jack Parker-Holder, Yuge (Jimmy) Shi and more (DeepMind, UBC)
  - **Date**: 23 Feb 2024
  - **Summary**: The first generative interactive environment trained in an unsupervised manner from unlabelled Internet videos. The model can be prompted to generate an endless variety of action-controllable virtual worlds described through text, synthetic images, photographs, and even sketches.
  - **Data**: Platformer game videos from Youtube; Robotics datasets used in RT1
  - **Metrics**
    - FVD
    - delta-t PSNR: PSNR(x_t, x_t_hat) - PSNR(x_t, x_t_random)

### Game Agent
> To be a better man
#### Text-based
- **Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf** [Arxiv](https://arxiv.org/abs/2309.04658)
  - Yuzhuang Xu, Shuo Wang, Peng Li, Fuwen Luo, Xiaolong Wang, Weidong Liu, Yang Liu
  - 9 Sep 2023

#### FPS
- **Counter-Strike Deathmatch with Large-Scale Behavioural Cloning** [Arxiv](https://arxiv.org/abs/2104.04258v2), [Code](https://github.com/TeaPearce/Counter-Strike_Behavioural_Cloning)
  - Tim Pearce, Jun Zhu
  - 9 Apr 2021

- **Will GPT-4 Run DOOM?** [Arxiv](https://arxiv.org/abs/2403.05468), [Project](https://adewynter.github.io/Doom), [Code](https://github.com/adewynter/Doom)
  - Adrian de Wynter
  - 8 Mar 2024

- **Diplomacy Cicero and Diplodocus** [Code](https://github.com/facebookresearch/diplomacy_cicero?tab=readme-ov-file), [Blog](https://ai.meta.com/research/cicero/)
  - **Human-level play in the game of Diplomacy by combining language models with strategic reasoning** [Paper](https://noambrown.github.io/papers/22-Science-Diplomacy-TR.pdf)
    - Meta, CMU, Stanford, MIT, Columbia University, UCB, Harvard
    - 22 Nov 2022
    - [Zhihu Blog about this paper](https://zhuanlan.zhihu.com/p/683329373)
  - **Mastering the Game of No-Press Diplomacy via Human-Regularized Reinforcement Learning and Planning** [Arxiv](https://arxiv.org/abs/2210.05492)
    - Anton Bakhtin, David J Wu, Adam Lerer, Jonathan Gray, Athul Paul Jacob, Gabriele Farina, Alexander H Miller, Noam Brown
    - 11 Oct 2022


### Misc
- **Choose Your Weapon: Survival Strategies for Depressed AI Academics**
[Arxiv](https://arxiv.org/abs/2304.06035)
  - Julian Togelius, Georgios N. Yannakakis
  - 8 Feb 2024

## Environment
### RPG
- **PokemonRedExperiments**
  - Github: [link](https://github.com/PWhiddy/PokemonRedExperiments)
  - An awesome youtube video about this project by the author: [link](https://www.youtube.com/watch?v=DcYLT37ImBY&t=895s)

## Project
### LLM
- **LLM Riddles**
  - blog from the author: [大模型解谜游戏 LLM Riddles的历程
](https://zhuanlan.zhihu.com/p/665393240)
  - gradio demo by ModelScope: [link](https://modelscope.cn/studios/LLMRiddles/LLMRiddles/summary)
  - opensource implementation by OpenDILab: [link](https://github.com/opendilab/LLMRiddles)

## Acknowledgement
- [Multimodal & Large Language Models](https://github.com/Yangyi-Chen/Multimodal-AND-Large-Language-Models/tree/main): The structure of our page is organized according to the layout of this page.