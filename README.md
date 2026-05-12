# Awesome World Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A comprehensive, categorized survey of World Model research — covering foundations, video generation, autonomous driving, robotics, gaming, LLMs, 3D/4D generation, physics simulation, efficiency, and more. **This repository is actively maintained and continuously updated with the latest papers.**

**Total: 340+ papers | Last updated: 2026-05-13**

---

## Table of Contents

- [1. Surveys \& Position Papers](#1-surveys-position-papers)
- [2. Blog Posts \& Technical Reports](#2-blog-posts-technical-reports)
- [3. Datasets, Benchmarks \& Evaluation](#3-datasets-benchmarks-evaluation)
- [4. Foundational World Models](#4-foundational-world-models)
- [5. Video Generation as World Simulators](#5-video-generation-as-world-simulators)
- [6. Autoregressive Diffusion \& Forcing Methods](#6-autoregressive-diffusion-forcing-methods)
- [7. Interactive \& Gaming World Models](#7-interactive-gaming-world-models)
- [8. Autonomous Driving World Models](#8-autonomous-driving-world-models)
- [9. Robotics \& Embodied AI World Models](#9-robotics-embodied-ai-world-models)
- [10. LLM \& Language-based World Models](#10-llm-language-based-world-models)
- [11. 3D \& 4D Spatial World Models](#11-3d-4d-spatial-world-models)
- [12. World Model Efficiency \& Acceleration](#12-world-model-efficiency-acceleration)
- [13. Physics-Informed \& Physics-Grounded World Models](#13-physics-informed-physics-grounded-world-models)
- [14. Weather, Climate \& Earth System Models](#14-weather-climate-earth-system-models)
- [15. Learnable Physics Simulators](#15-learnable-physics-simulators)
- [16. Scientific \& Medical World Models](#16-scientific-medical-world-models)
- [17. Long-Horizon \& Memory-Augmented World Models](#17-long-horizon-memory-augmented-world-models)
- [18. Theory \& World Model Explainability](#18-theory-world-model-explainability)
- [Related Resources](#related-resources)

---

## 1. Surveys & Position Papers

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| World Model for Robot Learning: A Comprehensive Survey | [2605.00080](https://arxiv.org/abs/2605.00080) | [GitHub](https://github.com/NTUMARS/Awesome-World-Model-for-Robotics-Policy) | 2026 | arXiv | Survey, Robot Learning |
| Video Generation Models as World Models: Efficient Paradigms, Architectures and Algorithms | [2603.28489](https://arxiv.org/abs/2603.28489) | / | 2026 | arXiv | Efficiency Survey, Video WM |
| Latent World Models for Automated Driving: A Unified Taxonomy | [2603.09086](https://arxiv.org/abs/2603.09086) | / | 2026 | arXiv | Driving WM Taxonomy |
| Agentic World Modeling: Foundations, Capabilities, Laws, and Beyond | [2604.22748](https://arxiv.org/abs/2604.22748) | [GitHub](https://github.com/matrix-agent/awesome-agentic-world-modeling) | 2026 | arXiv | Agentic WM, Foundations |
| Research on World Models Is Not Merely Injecting World Knowledge into Specific Tasks | [2602.01630](https://arxiv.org/abs/2602.01630) | / | 2026 | arXiv position paper | Position Paper, Latent Reasoning |
| A Survey of World Models for Autonomous Driving | [2501.11260](https://arxiv.org/abs/2501.11260) | [GitHub](https://github.com/FengZicai/AwesomeWMAD) | 2025 | arXiv | Survey, Autonomous Driving |
| A Comprehensive Survey on World Models for Embodied AI | [2510.16732](https://arxiv.org/abs/2510.16732) | [GitHub](https://github.com/Li-Zn-H/AwesomeWorldModels) | 2025 | arXiv | Survey, Embodied AI |
| 3D and 4D World Modeling: A Survey | [2509.07996](https://arxiv.org/abs/2509.07996) | [GitHub](https://github.com/worldbench/awesome-3d-4d-world-models) | 2025 | arXiv | Survey, 3D/4D |
| Survey of Video Diffusion Models: Foundations, Implementations, and Applications | [2504.16081](https://arxiv.org/abs/2504.16081) | [GitHub](https://github.com/Eyeline-Research/Survey-Video-Diffusion) | 2025 | arXiv | Video Diffusion Survey |
| Critiques of World Models | [2507.05169](https://arxiv.org/abs/2507.05169) | / | 2025 | arXiv | Critique, Limitations |
| Understanding World or Predicting Future? A Comprehensive Survey of World Models | [2411.14499](https://arxiv.org/abs/2411.14499) | [GitHub](https://github.com/tsinghua-fib-lab/World-Model) | 2024 | ACM CSUR 2025 | Survey, Taxonomy |
| Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond | [2405.03520](https://arxiv.org/abs/2405.03520) | [GitHub](https://github.com/GigaAI-research/General-World-Models-Survey) | 2024 | arXiv | Survey, Sora, AGI |
| World Models for Autonomous Driving: An Initial Survey | [2403.02622](https://arxiv.org/abs/2403.02622) | / | 2024 | arXiv | Survey, Driving, Scene Prediction |
| From Efficient Multimodal Models to World Models: A Survey | [2407.00118](https://arxiv.org/abs/2407.00118) | / | 2024 | arXiv | Survey, Multimodal, JEPA |
| Sora: A Review on Background, Technology, Limitations, and Opportunities | [2402.17177](https://arxiv.org/abs/2402.17177) | [GitHub](https://github.com/lichao-sun/SoraReview) | 2024 | arXiv | Sora Review, DiT |
| Sora as a World Model? A Complete Survey on Text-to-Video Generation | [2403.05131](https://arxiv.org/abs/2403.05131) | / | 2024 | arXiv | T2V Survey, World Modeling |
| Language Models, Agent Models, and World Models: The LAW for Machine Reasoning and Planning | [2312.05230](https://arxiv.org/abs/2312.05230) | / | 2023 | NeurIPS 23 | LAW Framework, Reasoning |
| A Survey on Model-based Reinforcement Learning | [2206.09328](https://arxiv.org/abs/2206.09328) | / | 2022 | SCIS 2024 | Survey, MBRL |

---

## 2. Blog Posts & Technical Reports

Notable blog posts, technical reports, and industry releases that shaped the world model landscape.

| Title | Source | Year | Link |
|-------|--------|------|------|
| Marble: 3D World Generation | World Labs | 2026 | [Link](https://www.worldlabs.ai/) |
| Genie 3: A New Frontier for World Models | Google DeepMind | 2025 | [Link](https://deepmind.google/discover/blog/genie-3/) |
| Cosmos World Foundation Model Platform | NVIDIA | 2025 | [Link](https://www.nvidia.com/en-us/ai/cosmos/) |
| V-JEPA 2 | Meta FAIR | 2025 | [Link](https://ai.meta.com/blog/v-jepa-2-video-model-self-supervised-learning/) |
| Evaluating Gemini Robotics Policies in a Veo World Simulator | Google DeepMind | 2025 | [Link](https://arxiv.org/abs/2512.10675) |
| Video Generation Models as World Simulators | OpenAI (Sora) | 2024 | [Link](https://openai.com/index/video-generation-models-as-world-simulators/) |
| Genie 2: A Large-Scale Foundation World Model | Google DeepMind | 2024 | [Link](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) |
| Oasis: A Universe in a Transformer | Decart / Etched | 2024 | [Link](https://oasis-model.github.io/) |
| A Path Towards Autonomous Machine Intelligence | Yann LeCun | 2022 | [Link](https://openreview.net/pdf?id=BZ5a1r-kVsf) |

---

## 3. Datasets, Benchmarks & Evaluation

Standardized benchmarks, datasets, and evaluation frameworks for world models.

### 3.1 General Video World Model Benchmarks

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| MIND: Benchmarking Memory Consistency and Action Control in World Models | [2602.08025](https://arxiv.org/abs/2602.08025) | [GitHub](https://github.com/CSU-JPG/MIND) | 2026 | arXiv | Memory Consistency, Action |
| WorldMark: A Unified Benchmark Suite for Interactive Video World Models | [2604.21686](https://arxiv.org/abs/2604.21686) | [Website](https://warena.ai/) | 2026 | arXiv | Interactive, WASD Control |
| iWorld-Bench: A Benchmark for Interactive World Models with Unified Action Generation | [2605.03941](https://arxiv.org/abs/2605.03941) | [GitHub](https://github.com/EmbodiedCity/iWorld-Bench) | 2026 | ICML 26 | Interactive, Multi-Perspective |
| WorldModelBench: Judging Video Generation Models As World Models | [2502.20694](https://arxiv.org/abs/2502.20694) | [Website](https://worldmodelbench-team.github.io/) | 2025 | CVPR 25 Workshop | Physics, Human Annotation |
| WorldScore: A Unified Evaluation Benchmark for World Generation | [2504.00983](https://arxiv.org/abs/2504.00983) | [GitHub](https://github.com/haoyi-duan/WorldScore) | 2025 | ICCV 25 | 3D/4D, Controllability |
| VBench-2.0: Advancing Video Generation Benchmark Suite for Intrinsic Faithfulness | [2503.21755](https://arxiv.org/abs/2503.21755) | [GitHub](https://github.com/Vchitect/VBench) | 2025 | arXiv | Physics, Commonsense |
| VideoVerse: Does Your T2V Generator Have World Model Capability? | [2510.08398](https://arxiv.org/abs/2510.08398) | [GitHub](https://github.com/Zeqing-Wang/VideoVerse) | 2025 | arXiv | Temporal Causality, T2V |
| SmallWorlds: Assessing Dynamics Understanding of World Models in Isolated Environments | [2511.23465](https://arxiv.org/abs/2511.23465) | / | 2025 | arXiv | Isolated Dynamics, Gravity |
| Benchmarking World-Model Learning | [2510.19788](https://arxiv.org/abs/2510.19788) | [Website](https://autumn.basis.ai) | 2025 | arXiv | Grid-World, Human Comparison |
| WorldSimBench: Towards Video Generation Models as World Simulators | [2410.18072](https://arxiv.org/abs/2410.18072) | [Website](https://iranqin.github.io/WorldSimBench.github.io/) | 2024 | CVPR 25 Workshop | Perceptual Eval, Embodied |
| VBench: Comprehensive Benchmark Suite for Video Generative Models | [2311.17982](https://arxiv.org/abs/2311.17982) | [GitHub](https://github.com/Vchitect/VBench) | 2023 | CVPR 24 Highlight | Multi-Dim Eval, Human Alignment |

### 3.2 Physics Understanding Benchmarks

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| PhysicsMind: Sim and Real Mechanics Benchmarking for Physical Reasoning | [2601.16007](https://arxiv.org/abs/2601.16007) | / | 2026 | arXiv | Mechanics, Sim-Real |
| WorldBench: Disambiguating Physics for Diagnostic Evaluation of World Models | [2601.21282](https://arxiv.org/abs/2601.21282) | [Website](https://world-bench.github.io/) | 2026 | CVPR 26 | Disentangled Physics, Diagnostic |
| Physics-IQ: Do Generative Video Models Understand Physical Principles? | [2501.09038](https://arxiv.org/abs/2501.09038) | [GitHub](https://github.com/google-deepmind/physics-IQ-benchmark) | 2025 | arXiv | Physics Understanding, DeepMind |
| PhysBench: Benchmarking VLMs for Physical World Understanding | [2501.16411](https://arxiv.org/abs/2501.16411) | [Website](https://physbench.github.io/) | 2025 | ICLR 25 | VLM Evaluation, PhysAgent |
| PhyWorldBench: Comprehensive Evaluation of Physical Realism in T2V Models | [2507.13428](https://arxiv.org/abs/2507.13428) | [GitHub](https://github.com/g-jing/phy-world-bench) | 2025 | arXiv | Physics Realism, NVIDIA |
| Morpheus: Benchmarking Physical Reasoning of Video Models with Real Experiments | [2504.02918](https://arxiv.org/abs/2504.02918) | [Website](https://physics-from-video.github.io/morpheus-bench) | 2025 | arXiv | Conservation Laws, Real Exp |
| LikePhys: Evaluating Intuitive Physics in Video Diffusion via Likelihood Preference | [2510.11512](https://arxiv.org/abs/2510.11512) | [Website](https://yuanjianhao508.github.io/LikePhys/) | 2025 | ICLR 26 | Intuitive Physics, Likelihood |
| PhyGenBench: Crafting Physical Commonsense-Based Benchmark for Video Generation | [2410.05363](https://arxiv.org/abs/2410.05363) | [GitHub](https://github.com/OpenGVLab/PhyGenBench) | 2024 | ICML 25 | Physical Commonsense, T2V |
| How Far is Video Generation from World Model: A Physical Law Perspective | [2411.02385](https://arxiv.org/abs/2411.02385) | [Website](https://phyworld.github.io) | 2024 | ICML 25 | Physical Laws, Scaling |

### 3.3 Embodied AI & Robotics Benchmarks

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| WorldArena: Evaluating Perception and Functional Utility of Embodied World Models | [2602.08971](https://arxiv.org/abs/2602.08971) | [GitHub](https://github.com/tsinghua-fib-lab/WorldArena) | 2026 | arXiv | Embodied, EWMScore |
| Wow, wo, val! A Comprehensive Embodied World Model Evaluation Turing Test | [2601.04137](https://arxiv.org/abs/2601.04137) | [Website](https://unigen-x.github.io/unifolm-world-model-action.github.io/) | 2026 | arXiv | Turing Test, 22 Metrics |
| RoboWM-Bench: Evaluating World Models in Robotic Manipulation | [2604.19092](https://arxiv.org/abs/2604.19092) | [Website](https://robowm-bench.github.io/RoboWM-Bench/) | 2026 | arXiv | Manipulation, Physical Plausibility |
| RBench: Rethinking Video Generation Model for the Embodied World | [2601.15282](https://arxiv.org/abs/2601.15282) | [GitHub](https://github.com/DAGroup-PKU/ReVidgen) | 2026 | ICLR 26 Workshop | Robot Video, RoVid-X |
| EWMBench: Evaluating Scene, Motion, and Semantic Quality in Embodied World Models | [2505.09694](https://arxiv.org/abs/2505.09694) | [GitHub](https://github.com/AgibotTech/EWMBench) | 2025 | arXiv | Embodied, Motion Correctness |

### 3.4 Autonomous Driving Benchmarks

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| DrivingGen: Comprehensive Benchmark for Generative Video World Models in AD | [2601.01528](https://arxiv.org/abs/2601.01528) | [Website](https://drivinggen-bench.github.io/) | 2026 | ICLR 26 | Driving, Visual Realism |
| WorldLens: Full-Spectrum Evaluations of Driving World Models in Real World | [2512.10958](https://arxiv.org/abs/2512.10958) | [GitHub](https://github.com/worldbench/WorldLens) | 2025 | arXiv | Driving, Auto-Evaluator |
| SimWorld: A Unified Benchmark for Simulator-Conditioned Scene Generation | [2503.13952](https://arxiv.org/abs/2503.13952) | [GitHub](https://github.com/Li-Zn-H/SimWorld) | 2025 | arXiv | Simulator Conditioning, Data Gen |
| ACT-Bench: Towards Action Controllable World Models for Autonomous Driving | [2412.05337](https://arxiv.org/abs/2412.05337) | [GitHub](https://github.com/turingmotors/ACT-Bench) | 2024 | arXiv | Action Fidelity, Trajectory |

### 3.5 3D/4D & Domain-Specific Datasets

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| MotionScape: A Large-Scale Real-World Highly Dynamic UAV Video Dataset | [2604.07991](https://arxiv.org/abs/2604.07991) | [GitHub](https://github.com/Thelegendzz/MotionScape) | 2026 | arXiv | UAV Video, 6-DoF |
| EgoVerse: An Egocentric Human Dataset for Robot Learning from Around the World | [2604.07607](https://arxiv.org/abs/2604.07607) | [GitHub](https://github.com/GaTech-RL2/EgoVerse) | 2026 | arXiv | Egocentric, 1362 Hours |
| MicroVerse: A Preliminary Exploration Toward a Micro-World Simulation | [2603.00585](https://arxiv.org/abs/2603.00585) | [GitHub](https://github.com/FreedomIntelligence/MicroVerse) | 2026 | ICLR 26 | Microscale, Biomedical |
| 4DWorldBench: Comprehensive Evaluation Framework for 3D/4D World Generation | [2511.19836](https://arxiv.org/abs/2511.19836) | [Website](https://yeppp27.github.io/4DWorldBench.github.io/) | 2025 | arXiv | 3D/4D, Physical Realism |
| OmniWorld: A Multi-Domain and Multi-Modal Dataset for 4D World Modeling | [2509.12201](https://arxiv.org/abs/2509.12201) | [Website](https://yangzhou24.github.io/OmniWorld/) | 2025 | ICLR 26 | 4D Dataset, 300M+ Frames |
| AeroVerse: UAV-Agent Benchmark Suite for Aerospace Embodied World Models | [2408.15511](https://arxiv.org/abs/2408.15511) | / | 2024 | arXiv | UAV, Aerospace |

### 3.6 Agent & Language World Model Benchmarks

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| World Reasoning Arena | [2603.25887](https://arxiv.org/abs/2603.25887) | [GitHub](https://github.com/MBZUAI-IFM/WR-Arena) | 2026 | arXiv | Simulative Reasoning, Long-Horizon |
| Text2World: Benchmarking LLMs for Symbolic World Model Generation | [2502.13092](https://arxiv.org/abs/2502.13092) | [Website](https://text-to-world.github.io/) | 2025 | ACL 25 | PDDL, Symbolic WM |
| MobileWorldBench: Towards Semantic World Modeling For Mobile Agents | [2512.14014](https://arxiv.org/abs/2512.14014) | [GitHub](https://github.com/jacklishufan/MobileWorld) | 2025 | arXiv | Mobile GUI, VLM |
| PragWorld: Evaluating LLMs' Local World Model under Minimal Linguistic Alterations | [2511.13021](https://arxiv.org/abs/2511.13021) | / | 2025 | AAAI 26 | LLM WM, Pragmatics |
| WorldPrediction: Benchmark for High-level World Modeling and Long-horizon Planning | [2506.04363](https://arxiv.org/abs/2506.04363) | / | 2025 | ICML 25 Workshop | Procedural Planning, Video |
| Target-Bench: Can Video World Models Achieve Mapless Path Planning? | [2511.17792](https://arxiv.org/abs/2511.17792) | [GitHub](https://github.com/TUM-AVS/target-bench) | 2025 | arXiv | Path Planning, Semantic |
| CityBench: Evaluating LLM Capabilities as World Model | [2406.13945](https://arxiv.org/abs/2406.13945) | [GitHub](https://github.com/tsinghua-fib-lab/CityBench) | 2024 | KDD 25 | Urban, LLM |

---

## 4. Foundational World Models

Core works establishing the world model paradigm — from latent imagination to planning to self-supervised prediction.

### 4.1 Pioneering Works & Dreamer Series

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Training Agents Inside of Scalable World Models (Dreamer4) | [2509.24527](https://arxiv.org/abs/2509.24527) | [GitHub](https://github.com/nicklashansen/dreamer4) | 2025 | arXiv | Scalable WM, Shortcut Forcing |
| Mastering Diverse Domains through World Models (DreamerV3) | [2301.04104](https://arxiv.org/abs/2301.04104) | [GitHub](https://github.com/danijar/dreamerv3) | 2023 | Nature 2025 | General RL, Minecraft |
| A Path Towards Autonomous Machine Intelligence | / | / | 2022 | OpenReview position paper | JEPA, World Model Architecture |
| DayDreamer: World Models for Physical Robot Learning | [2206.14176](https://arxiv.org/abs/2206.14176) | [GitHub](https://github.com/danijar/daydreamer) | 2022 | CoRL 22 | Physical Robot, Dreamer |
| Mastering Atari with Discrete World Models (DreamerV2) | [2010.02193](https://arxiv.org/abs/2010.02193) | [GitHub](https://github.com/danijar/dreamerv2) | 2021 | ICLR 21 | Discrete Latents, KL Balancing |
| Dream to Control: Learning Behaviors by Latent Imagination (DreamerV1) | [1912.01603](https://arxiv.org/abs/1912.01603) | / | 2020 | ICLR 20 | Latent Imagination, Actor-Critic |
| Learning Latent Dynamics for Planning from Pixels (PlaNet) | [1811.04551](https://arxiv.org/abs/1811.04551) | [GitHub](https://github.com/google-research/planet) | 2019 | ICML 19 | RSSM, Model-Based Planning |
| World Models | [1803.10122](https://arxiv.org/abs/1803.10122) | [Website](https://worldmodels.github.io/) | 2018 | NeurIPS 18 | VAE+RNN, Latent Imagination |

### 4.2 Planning & Model-Based RL

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| EfficientZero V2: Mastering Discrete and Continuous Control with Limited Data | [2403.00564](https://arxiv.org/abs/2403.00564) | [GitHub](https://github.com/Shengjiewang-Jason/EfficientZeroV2) | 2024 | ICML 24 Spotlight | Discrete+Continuous, MCTS |
| TD-MPC2: Scalable, Robust World Models for Continuous Control | [2310.16828](https://arxiv.org/abs/2310.16828) | [GitHub](https://github.com/nicklashansen/tdmpc2) | 2024 | ICLR 24 | Multi-Task, Continuous Control |
| Temporal Difference Learning for Model Predictive Control (TD-MPC) | [2203.04955](https://arxiv.org/abs/2203.04955) | [Website](https://nicklashansen.github.io/td-mpc) | 2022 | ICML 22 | MPC, Latent Dynamics |
| Mastering Atari Games with Limited Data (EfficientZero) | [2111.00210](https://arxiv.org/abs/2111.00210) | [GitHub](https://github.com/YeWR/EfficientZero) | 2021 | NeurIPS 21 | Sample-Efficient RL, MuZero |
| Mastering Atari, Go, Chess and Shogi by Planning with a Learned Model (MuZero) | [1911.08265](https://arxiv.org/abs/1911.08265) | / | 2020 | Nature 2020 | MCTS, Implicit World Model |

### 4.3 JEPA / Joint-Embedding Predictive Architecture

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning | [2506.09985](https://arxiv.org/abs/2506.09985) | [GitHub](https://github.com/facebookresearch/vjepa2) | 2025 | arXiv | Robot Planning, Self-Supervised |
| Revisiting Feature Prediction for Learning Visual Representations from Video (V-JEPA) | [2404.08471](https://arxiv.org/abs/2404.08471) | [GitHub](https://github.com/facebookresearch/jepa) | 2024 | ICLR 25 poster | Video Prediction, Latent |
| Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture (I-JEPA) | [2301.08243](https://arxiv.org/abs/2301.08243) | [GitHub](https://github.com/facebookresearch/ijepa) | 2023 | CVPR 23 | JEPA, Self-Supervised |

### 4.4 Transformer & Discrete World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Learning to Play Atari in a World of Tokens (DART) | [2406.01361](https://arxiv.org/abs/2406.01361) | [Website](https://pranaval.github.io/DART/) | 2024 | ICML 24 | Discrete Abstract Repr., Atari |
| Efficient World Models with Context-Aware Tokenization (Delta-IRIS) | [2406.19320](https://arxiv.org/abs/2406.19320) | [GitHub](https://github.com/vmicheli/delta-iris) | 2024 | ICML 24 | Delta Tokenization, Autoregressive |
| Transformers are Sample-Efficient World Models (IRIS) | [2209.00588](https://arxiv.org/abs/2209.00588) | [GitHub](https://github.com/eloialonso/iris) | 2023 | ICLR 23 Notable Top 5% | Discrete Autoencoder, Atari |
| Transformer-based World Models Are Happy With 100k Interactions (TWM) | [2303.07109](https://arxiv.org/abs/2303.07109) | [GitHub](https://github.com/jrobine/twm) | 2023 | ICLR 23 | Transformer-XL, Atari 100k |
| STORM: Efficient Stochastic Transformer based World Models for RL | [2310.09615](https://arxiv.org/abs/2310.09615) | [GitHub](https://github.com/weipu-zhang/STORM) | 2023 | NeurIPS 23 | Stochastic Transformer, VAE |
| TransDreamer: Reinforcement Learning with Transformer World Models | [2202.09481](https://arxiv.org/abs/2202.09481) | [GitHub](https://github.com/changchencc/TransDreamer) | 2022 | NeurIPS 21 Workshop | Transformer RSSM, Long-Range |

---

## 5. Video Generation as World Simulators

Large-scale video generation models that serve as or aspire to be world simulators.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Wan: Open and Advanced Large-Scale Video Generative Models | [2503.20314](https://arxiv.org/abs/2503.20314) | [GitHub](https://github.com/Wan-Video/Wan2.1) | 2025 | arXiv | 14B DiT, Open-Source |
| Open-Sora 2.0: Training a Commercial-Level Video Generation Model in $200k | [2503.09642](https://arxiv.org/abs/2503.09642) | [GitHub](https://github.com/hpcaitech/Open-Sora) | 2025 | arXiv | Efficient Training, Open-Source |
| Step-Video-T2V: The Practice, Challenges, and Future of Video Foundation Model | [2502.10248](https://arxiv.org/abs/2502.10248) | [GitHub](https://github.com/stepfun-ai/Step-Video-T2V) | 2025 | arXiv | 30B DiT, Video-DPO |
| MAGI-1: Autoregressive Video Generation at Scale | [2505.13211](https://arxiv.org/abs/2505.13211) | [GitHub](https://github.com/SandAI-org/MAGI-1) | 2025 | arXiv | 24B, Autoregressive, Streaming |
| Cosmos World Foundation Model Platform for Physical AI | [2501.03575](https://arxiv.org/abs/2501.03575) | [GitHub](https://github.com/nvidia-cosmos/cosmos-predict1) | 2025 | arXiv | Physical AI, Video Tokenizer |
| Cosmos-Predict2.5: World Simulation with Video Foundation Models for Physical AI | [2511.00062](https://arxiv.org/abs/2511.00062) | [GitHub](https://github.com/nvidia-cosmos/cosmos-predict2.5) | 2025 | arXiv | Flow Matching, 14B |
| VideoWorld: A Simple Generative Model that Learns from Unlabeled Videos | / | [GitHub](https://github.com/ByteDance-Seed/VideoWorld) | 2025 | CVPR 25 | Unlabeled Video, Latent Dynamics |
| Video Generation Models as World Simulators (Sora) | / | / | 2024 | OpenAI Technical Report | DiT, World Simulator |
| CogVideoX: Text-to-Video Diffusion Models with An Expert Transformer | [2408.06072](https://arxiv.org/abs/2408.06072) | [GitHub](https://github.com/THUDM/CogVideo) | 2024 | ICLR 25 | Expert Transformer, 3D VAE |
| Movie Gen: A Cast of Media Foundation Models | [2410.13720](https://arxiv.org/abs/2410.13720) | [Website](https://go.fb.me/MovieGenResearchVideos) | 2024 | arXiv | 30B, Flow Matching |
| HunyuanVideo: A Systematic Framework For Large Video Generative Models | [2412.03603](https://arxiv.org/abs/2412.03603) | [GitHub](https://github.com/Tencent/HunyuanVideo) | 2024 | arXiv | 13B DiT, Dual-Stream |
| Open-Sora: Democratizing Efficient Video Production for All | [2412.20404](https://arxiv.org/abs/2412.20404) | [GitHub](https://github.com/hpcaitech/Open-Sora) | 2024 | arXiv | STDiT, Open-Source |
| Open-Sora Plan: Open-Source Large Video Generation Model | [2412.00131](https://arxiv.org/abs/2412.00131) | [GitHub](https://github.com/PKU-YuanGroup/Open-Sora-Plan) | 2024 | arXiv | Wavelet-Flow VAE, Open-Source |
| Latte: Latent Diffusion Transformer for Video Generation | [2401.03048](https://arxiv.org/abs/2401.03048) | [Website](https://maxin-cn.github.io/latte_project) | 2024 | TMLR 2025 | Video DiT, Spatiotemporal |
| LTX-Video: Realtime Video Latent Diffusion | [2501.00103](https://arxiv.org/abs/2501.00103) | [GitHub](https://github.com/Lightricks/LTX-Video) | 2024 | arXiv | Realtime, High-Compression VAE |
| VideoPoet: A Large Language Model for Zero-Shot Video Generation | [2312.14125](https://arxiv.org/abs/2312.14125) | [Website](http://sites.research.google/videopoet/) | 2023 | ICML 24 Best Paper | LLM Video Gen, Multimodal |
| Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets | [2311.15127](https://arxiv.org/abs/2311.15127) | [GitHub](https://github.com/Stability-AI/generative-models) | 2023 | arXiv | Image-to-Video, Data Curation |
| VideoLCM: Video Latent Consistency Model | [2312.09109](https://arxiv.org/abs/2312.09109) | / | 2023 | arXiv | Consistency Distillation, Fast |
| Video Diffusion Models | [2204.03458](https://arxiv.org/abs/2204.03458) | [Website](https://video-diffusion.github.io/) | 2022 | NeurIPS 22 | Foundational Video Diffusion |
| Make-A-Video: Text-to-Video Generation without Text-Video Data | [2209.14792](https://arxiv.org/abs/2209.14792) | [Website](https://make-a-video.github.io/) | 2022 | ICLR 23 | T2I-to-T2V, Spatiotemporal |
| Imagen Video: High Definition Video Generation with Diffusion Models | [2210.02303](https://arxiv.org/abs/2210.02303) | [Website](https://imagen.research.google/video/) | 2022 | arXiv | Cascaded Diffusion, HD Video |
| Phenaki: Variable Length Video Generation From Open Domain Textual Description | [2210.02399](https://arxiv.org/abs/2210.02399) | [Website](https://phenaki.github.io/) | 2022 | ICLR 23 | Variable-Length, Masked Transformer |
| MagicVideo: Efficient Video Generation With Latent Diffusion Models | [2211.11018](https://arxiv.org/abs/2211.11018) | [Website](https://magicvideo.github.io/) | 2022 | arXiv | Latent Diffusion, Temporal Attn |
| CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers | [2205.15868](https://arxiv.org/abs/2205.15868) | [GitHub](https://github.com/THUDM/CogVideo) | 2022 | ICLR 23 | Autoregressive, Large-Scale |

---

## 6. Autoregressive Diffusion & Forcing Methods

Methods bridging autoregressive generation and diffusion for world modeling.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Causal Forcing: Autoregressive Diffusion Distillation for Real-Time Interactive Video | [2602.02214](https://arxiv.org/abs/2602.02214) | [Website](https://thu-ml.github.io/CausalForcing.github.io/) | 2026 | arXiv | Causal Distillation, Real-Time |
| Helios: Real Real-Time Long Video Generation Model | [2603.04379](https://arxiv.org/abs/2603.04379) | [Website](http://pku-yuangroup.github.io/Helios-Page) | 2026 | arXiv | Real-Time, Long Video |
| Diagonal Distillation: Streaming Autoregressive Video via Diagonal Distillation | [2603.09488](https://arxiv.org/abs/2603.09488) | [GitHub](https://github.com/Sphere-AI-Lab/diagdistill) | 2026 | ICLR 26 | Streaming, Two-Step |
| SCD: Causality in Video Diffusers is Separable from Denoising | [2602.10095](https://arxiv.org/abs/2602.10095) | / | 2026 | arXiv | Causal Separation, Denoising |
| DFoT: History-Guided Video Diffusion (Diffusion Forcing Transformer) | [2502.06764](https://arxiv.org/abs/2502.06764) | [GitHub](https://github.com/kwsong0113/diffusion-forcing-transformer) | 2025 | ICML 25 | History Guidance, Transformer |
| AR-Diffusion: Asynchronous Video Generation with Auto-Regressive Diffusion | [2503.07418](https://arxiv.org/abs/2503.07418) | [GitHub](https://github.com/iva-mzsun/AR-Diffusion) | 2025 | CVPR 25 | Asynchronous, AR-Diffusion |
| Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion | [2506.08009](https://arxiv.org/abs/2506.08009) | [Website](http://self-forcing.github.io/) | 2025 | NeurIPS 25 Spotlight | Train-Test Gap, AR-Diffusion |
| Vid2World: Crafting Video Diffusion Models to Interactive World Models | [2505.14357](https://arxiv.org/abs/2505.14357) | [Website](http://vid2world.github.io) | 2025 | arXiv | Diffusion-to-Interactive |
| Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion | [2407.01392](https://arxiv.org/abs/2407.01392) | [GitHub](https://github.com/buoyancy99/diffusion-forcing) | 2024 | NeurIPS 24 | AR-Diffusion, Foundational |
| CausVid: From Slow Bidirectional to Fast Autoregressive Video Diffusion Models | [2412.07772](https://arxiv.org/abs/2412.07772) | [Website](https://causvid.github.io/) | 2024 | CVPR 25 | Bidirectional-to-AR, Distillation |
| Ca2-VDM: Efficient Autoregressive Video Diffusion Model with Causal Generation and Cache Sharing | [2411.16375](https://arxiv.org/abs/2411.16375) | [GitHub](https://github.com/Dawn-LX/CausalCache-VDM) | 2024 | ICML 25 | Causal Cache Sharing, AR Video |

---

## 7. Interactive & Gaming World Models

World models for playable environments, game generation, and interactive simulation.

### 7.1 Game-Playing World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Diffusion for World Modeling: Visual Details Matter in Atari (DIAMOND) | [2405.12399](https://arxiv.org/abs/2405.12399) | [Website](https://diamond-wm.github.io) | 2024 | NeurIPS 24 Spotlight | Diffusion WM, Atari |
| iVideoGPT: Interactive VideoGPTs are Scalable World Models | [2405.15223](https://arxiv.org/abs/2405.15223) | [Website](https://thuml.github.io/iVideoGPT) | 2024 | NeurIPS 24 | Autoregressive, Interactive |

### 7.2 Game Generation & Neural Game Engines

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Genie 3: A New Frontier for World Models | / | / | 2025 | DeepMind Blog | Interactive 3D, Playable Worlds |
| GameFactory: Creating New Games with Generative Interactive Videos | [2501.08325](https://arxiv.org/abs/2501.08325) | [Website](https://yujiwen.github.io/gamefactory) | 2025 | ICCV 25 | Scene-Generalizable, Game Creation |
| Genie: Generative Interactive Environments | [2402.15391](https://arxiv.org/abs/2402.15391) | / | 2024 | ICML 24 Oral | Foundation WM, Latent Action |
| Genie 2: A Large-Scale Foundation World Model | / | / | 2024 | DeepMind Technical Report | 3D World Gen, Action-Controllable |
| Diffusion Models Are Real-Time Game Engines (GameNGen) | [2408.14837](https://arxiv.org/abs/2408.14837) | [Website](https://gamengen.github.io) | 2024 | ICLR 25 poster | Neural Game Engine, DOOM |
| GameGen-X: Interactive Open-world Game Video Generation | [2411.00769](https://arxiv.org/abs/2411.00769) | [GitHub](https://github.com/GameGen-X/GameGen-X) | 2024 | ICLR 25 | Open-World Game, DiT |
| Oasis: A Universe in a Transformer | / | [GitHub](https://github.com/etched-ai/open-oasis) | 2024 | Technical Report | Real-Time, Minecraft WM |
| Unbounded: A Generative Infinite Game of Character Life Simulation | [2410.18975](https://arxiv.org/abs/2410.18975) | [Website](https://generative-infinite-game.github.io) | 2024 | ICLR 25 | Infinite Game, LLM Engine |

### 7.3 Interactive World Simulation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Matrix-Game 3.0: Real-Time and Streaming Interactive World Model with Long-Horizon Memory | [2604.08995](https://arxiv.org/abs/2604.08995) | [Website](https://matrix-game-v3.github.io/) | 2026 | arXiv | Streaming, Long-Horizon Memory |
| Solaris: Building a Multiplayer Video World Model in Minecraft | [2602.22208](https://arxiv.org/abs/2602.22208) | [Website](https://solaris-wm.github.io/) | 2026 | arXiv | Multiplayer, Minecraft |
| INSPATIO-WORLD: A Real-Time 4D World Simulator via Spatiotemporal Autoregressive Modeling | [2604.07209](https://arxiv.org/abs/2604.07209) | [GitHub](https://github.com/inspatio/inspatio-world) | 2026 | arXiv | 4D Simulation, Real-Time |
| MultiWorld: Scalable Multi-Agent Multi-View Video World Models | [2604.18564](https://arxiv.org/abs/2604.18564) | [Website](https://multi-world.github.io/) | 2026 | arXiv | Multi-Agent, Multi-View |
| Olaf-World: Orienting Latent Actions for Video World Modeling | [2602.10104](https://arxiv.org/abs/2602.10104) | [GitHub](https://github.com/showlab/Olaf-World) | 2026 | arXiv | Latent Action, Video WM |
| Infinite-World: Scaling Interactive World Models to 1000-Frame Horizons | [2602.02393](https://arxiv.org/abs/2602.02393) | [Website](https://infinite-world-web.github.io) | 2026 | arXiv | 1000-Frame, Hierarchical Memory |
| LIVE: Long-horizon Interactive Video World Modeling | [2602.03747](https://arxiv.org/abs/2602.03747) | [Website](https://junchao-cs.github.io/LIVE-demo/) | 2026 | arXiv | Long-Horizon, Interactive |
| ActionParty: Multi-Subject Action Binding in Generative Video Games | [2604.02330](https://arxiv.org/abs/2604.02330) | [Website](https://actionparty.github.io) | 2026 | arXiv | Multi-Subject, Generative Games |
| MineWorld: A Real-Time and Open-Source Interactive World Model on Minecraft | [2504.08388](https://arxiv.org/abs/2504.08388) | [GitHub](https://github.com/microsoft/mineworld) | 2025 | arXiv | Diagonal Decoding, Minecraft |
| Matrix-Game: Interactive World Foundation Model | [2506.18701](https://arxiv.org/abs/2506.18701) | [GitHub](https://github.com/SkyworkAI/Matrix-Game) | 2025 | arXiv | World Foundation Model, Minecraft |
| WorldPlay: Towards Long-Term Geometric Consistency for Real-Time Interactive World Modeling | [2512.14614](https://arxiv.org/abs/2512.14614) | [GitHub](https://github.com/Tencent-Hunyuan/HY-WorldPlay) | 2025 | arXiv | Geometric Consistency, Streaming |
| PAN: A World Model for General, Interactable, and Long-Horizon World Simulation | [2511.09057](https://arxiv.org/abs/2511.09057) | [GitHub](https://github.com/nvidia-cosmos/cosmos-predict2) | 2025 | arXiv | General-Purpose, Interactable |
| RELIC: Interactive Video World Model with Long-Horizon Memory | [2512.04040](https://arxiv.org/abs/2512.04040) | [Website](https://relic-worldmodel.github.io/) | 2025 | arXiv | Long-Horizon Memory, Interactive |
| Astra: General Interactive World Model with Autoregressive Denoising | [2512.08931](https://arxiv.org/abs/2512.08931) | [GitHub](https://github.com/EternalEvan/Astra) | 2025 | ICLR 26 | General Interactive, AR Denoising |
| Pandora: Towards General World Model with Natural Language Actions and Video States | [2406.09455](https://arxiv.org/abs/2406.09455) | [GitHub](https://github.com/maitrix-org/Pandora) | 2024 | arXiv | Language Action, Hybrid AR-Diffusion |
| WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens | [2401.09985](https://arxiv.org/abs/2401.09985) | [Website](https://world-dreamer.github.io/) | 2024 | arXiv | Masked Token Prediction, General WM |

---

## 8. Autonomous Driving World Models

World models for driving simulation, scene generation, and end-to-end planning.

### 8.1 Foundational Driving World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving | [2503.20523](https://arxiv.org/abs/2503.20523) | / | 2025 | arXiv | Multi-View, Flow Matching |
| Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | [2405.17398](https://arxiv.org/abs/2405.17398) | [GitHub](https://github.com/OpenDriveLab/Vista) | 2024 | NeurIPS 24 | Generalizable, Action Control |
| GenAD: Generalized Predictive Model for Autonomous Driving | [2403.09630](https://arxiv.org/abs/2403.09630) | [GitHub](https://github.com/OpenDriveLab/DriveAGI) | 2024 | CVPR 24 Highlight | Zero-Shot, Driving Foundation |
| GAIA-1: A Generative World Model for Autonomous Driving | [2309.17080](https://arxiv.org/abs/2309.17080) | / | 2023 | arXiv | Generative WM, Action-Conditioned |
| UniSim: A Neural Closed-Loop Sensor Simulator | [2308.01898](https://arxiv.org/abs/2308.01898) | / | 2023 | CVPR 23 Highlight | Closed-Loop, Neural Rendering |
| DriveGAN: Towards a Controllable High-Quality Neural Simulation | [2104.15060](https://arxiv.org/abs/2104.15060) | [GitHub](https://github.com/nv-tlabs/DriveGAN_code) | 2021 | CVPR 21 Oral | GAN, Neural Simulation |

### 8.2 DriveDreamer Series & Scenario Generation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| UniDriveDreamer: A Single-Stage Multimodal World Model for Autonomous Driving | [2602.02002](https://arxiv.org/abs/2602.02002) | / | 2026 | arXiv | Multimodal, LiDAR+Camera |
| DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation | [2403.06845](https://arxiv.org/abs/2403.06845) | [Website](https://drivedreamer2.github.io) | 2024 | AAAI 25 | LLM-Enhanced, Customized |
| DriveDreamer4D: World Models Are Effective Data Machines for 4D Driving Scene | [2410.13571](https://arxiv.org/abs/2410.13571) | [Website](https://drivedreamer4d.github.io) | 2024 | arXiv | 4D Reconstruction, Data Machine |
| MagicDrive-V2: High-Resolution Long Video Generation for Autonomous Driving | [2411.13807](https://arxiv.org/abs/2411.13807) | [Website](https://flymin.github.io/magicdrive-v2/) | 2024 | ICCV 25 | DiT, Adaptive Control |
| SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control | [2403.19438](https://arxiv.org/abs/2403.19438) | [Website](https://subjectdrive.github.io/) | 2024 | arXiv | Data Scaling, Subject Control |
| DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving | [2309.09777](https://arxiv.org/abs/2309.09777) | [Website](https://drivedreamer.github.io) | 2023 | ECCV 24 | Diffusion, Real-World Driving |
| MagicDrive: Street View Generation with Diverse 3D Geometry Control | [2310.02601](https://arxiv.org/abs/2310.02601) | [Website](https://flymin.github.io/magicdrive) | 2023 | ICLR 24 | 3D Geometry, Multi-View |
| Panacea: Panoramic and Controllable Video Generation for Autonomous Driving | [2311.16813](https://arxiv.org/abs/2311.16813) | [Website](https://panacea-ad.github.io/) | 2023 | CVPR 24 | Panoramic, BEV-Conditioned |

### 8.3 3D Occupancy & LiDAR World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| BEVWorld: A Multimodal World Simulator for Autonomous Driving via Scene-Level BEV Latents | [2407.05679](https://arxiv.org/abs/2407.05679) | [GitHub](https://github.com/zympsyche/BevWorld) | 2024 | arXiv | BEV Latent, Scene-Level |
| LidarDM: Generative LiDAR Simulation in a Generated World | [2404.02903](https://arxiv.org/abs/2404.02903) | [GitHub](https://github.com/vzyrianov/LidarDM) | 2024 | ICRA 25 | LiDAR Diffusion, 4D World |
| DynamicCity: Large-Scale 4D Occupancy Generation from Dynamic Scenes | [2410.18084](https://arxiv.org/abs/2410.18084) | [Website](https://dynamic-city.github.io/) | 2024 | ICLR 25 Spotlight | 4D Occupancy, HexPlane |
| OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | [2311.16038](https://arxiv.org/abs/2311.16038) | [GitHub](https://github.com/wzzheng/OccWorld) | 2023 | ECCV 24 | 3D Occupancy, Scene Evolution |
| Copilot4D: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion | [2311.01017](https://arxiv.org/abs/2311.01017) | / | 2023 | ICLR 24 | LiDAR, Discrete Diffusion |
| MUVO: A Multimodal Generative World Model for Autonomous Driving with Geometric Representations | [2311.11762](https://arxiv.org/abs/2311.11762) | [GitHub](https://github.com/fzi-forschungszentrum-informatik/muvo) | 2023 | arXiv | Voxel Occupancy, Sensor Fusion |

### 8.4 Planning-Oriented Driving World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Dream4Drive: Rethinking Driving World Model | / | / | 2026 | ICLR 26 | 3D-Aware Synthesis, Perception |
| X-World: Controllable Ego-Centric Multi-Camera World Models for Scalable End-to-End Driving | [2603.19979](https://arxiv.org/abs/2603.19979) | [Website](https://x-world-1.github.io) | 2026 | arXiv | Multi-Camera, XPENG |
| FAR-Drive: Frame-AutoRegressive Video Generation in Closed-Loop Autonomous Driving | [2603.14938](https://arxiv.org/abs/2603.14938) | / | 2026 | arXiv | Frame-AR, Closed-Loop |
| DrivingGen: A Comprehensive Benchmark for Generative Video World Models in Autonomous Driving | / | / | 2026 | ICLR 26 | Benchmark, Driving WM |
| X-Cache: Cross-Chunk Block Caching for Few-Step Autoregressive World Models Inference | [2604.20289](https://arxiv.org/abs/2604.20289) | [Website](https://x-cache-1.github.io/) | 2026 | arXiv | Cross-Chunk Caching, XPENG |
| WorldRFT: Latent World Model Planning with Reinforcement Fine-Tuning | [2512.19133](https://arxiv.org/abs/2512.19133) | / | 2025 | AAAI 26 | RL Fine-Tuning, Latent Planning |
| FutureX: Enhance End-to-End AD via Latent Chain-of-Thought World Model | [2512.11226](https://arxiv.org/abs/2512.11226) | / | 2025 | arXiv | Chain-of-Thought, Latent WM |
| GeoDrive: 3D Geometry-Informed Driving World Model with Precise Action Control | [2505.22421](https://arxiv.org/abs/2505.22421) | [GitHub](https://github.com/antonioo-c/GeoDrive) | 2025 | arXiv | 3D Geometry, Action Control |
| ProphetDWM: A Driving World Model for Rolling Out Future Actions and Videos | [2505.18650](https://arxiv.org/abs/2505.18650) | / | 2025 | arXiv | Joint Action-Video, POMDP |
| Epona: Autoregressive Diffusion World Model for Autonomous Driving | / | / | 2025 | ICCV 25 | AR-Diffusion, Driving |
| World4Drive: End-to-End Autonomous Driving via Intention-aware Physical Latent World Model | [2507.00603](https://arxiv.org/abs/2507.00603) | [GitHub](https://github.com/ucaszyp/World4Drive) | 2025 | ICCV 25 | Intention-Aware, End-to-End |
| HERMES: A Unified Self-Driving World Model for Simultaneous 3D Scene Understanding and Generation | / | / | 2025 | ICCV 25 | Unified 3D, Understanding+Gen |
| Navigation World Model | / | / | 2025 | CVPR 25 Award Candidate | Navigation, Controllable Video |
| Think2Drive: Efficient RL by Thinking in Latent World Model for Autonomous Driving | [2402.16720](https://arxiv.org/abs/2402.16720) | / | 2024 | ECCV 24 | Model-Based RL, CARLA-v2 |
| DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving | [2405.04390](https://arxiv.org/abs/2405.04390) | / | 2024 | CVPR 24 | 4D Pre-Training, Memory SSM |
| DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT | [2412.19505](https://arxiv.org/abs/2412.19505) | [GitHub](https://github.com/YvanYin/DrivingWorld) | 2024 | arXiv | Spatiotemporal GPT, Long Video |
| DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers | [2412.18607](https://arxiv.org/abs/2412.18607) | [Website](https://rogerchern.github.io/DrivingGPT) | 2024 | ICCV 25 | Unified World+Planning, Multi-Modal |
| LAW: Enhancing End-to-End Autonomous Driving with Latent World Model | [2406.08481](https://arxiv.org/abs/2406.08481) | [GitHub](https://github.com/BraveGroup/LAW) | 2024 | ICLR 25 | Latent WM, End-to-End |
| Drive-WM: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving | [2311.17918](https://arxiv.org/abs/2311.17918) | [GitHub](https://github.com/BraveGroup/Drive-WM) | 2023 | CVPR 24 | Multi-View Forecasting, Planning |
| ADriver-I: A General World Model for Autonomous Driving | [2311.13549](https://arxiv.org/abs/2311.13549) | / | 2023 | arXiv | MLLM+Diffusion, Infinite Driving |
| TrafficBots: Towards World Models for Autonomous Driving Simulation and Motion Prediction | [2303.04116](https://arxiv.org/abs/2303.04116) | [GitHub](https://github.com/zhejz/TrafficBots) | 2023 | ICRA 23 | Multi-Agent, Motion Prediction |
| WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation | [2312.02934](https://arxiv.org/abs/2312.02934) | [GitHub](https://github.com/fudan-zvg/WoVoGen) | 2023 | ECCV 24 | 4D World Volume, Scene Editing |

---

## 9. Robotics & Embodied AI World Models

World models for manipulation, navigation, and embodied decision-making.

### 9.1 Action-Conditioned Video Generation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Ctrl-World: A Controllable Generative World Model for Robot Manipulation | [2510.10125](https://arxiv.org/abs/2510.10125) | [GitHub](https://github.com/Robert-gyj/Ctrl-World) | 2025 | ICLR 26 | Multi-View, Controllable |
| IRASim: A Fine-Grained World Model for Robot Manipulation | [2406.14540](https://arxiv.org/abs/2406.14540) | [Website](https://gen-irasim.github.io) | 2024 | ICCV 25 | Frame-Level Alignment, DiT |
| AVID: Adapting Video Diffusion Models to World Models | [2410.12822](https://arxiv.org/abs/2410.12822) | / | 2024 | RLJ 25 | Video Diffusion Adapter, Frozen |
| UniSim: Learning Interactive Real-World Simulators | [2310.06114](https://arxiv.org/abs/2310.06114) | [Website](https://universal-simulator.github.io) | 2023 | ICLR 24 Oral | Universal Simulator, Interactive |

### 9.2 Compositional & Imagination-based Planning

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| ManipDreamer: Boosting Robotic Manipulation World Model with Action Tree and Visual Guidance | [2504.16464](https://arxiv.org/abs/2504.16464) | / | 2025 | arXiv | Action Tree, Depth-Semantic |
| RoboDreamer: Learning Compositional World Models for Robot Imagination | [2404.12377](https://arxiv.org/abs/2404.12377) | [GitHub](https://github.com/rainbow979/robodreamer) | 2024 | arXiv | Compositional, Language |
| Dream to Manipulate: Compositional World Models Empowering Robot Imitation Learning (DreMa) | [2412.14957](https://arxiv.org/abs/2412.14957) | [Website](https://dreamtomanipulate.github.io/) | 2024 | ICLR 25 | Gaussian Splatting, One-Shot |
| PIVOT-R: Primitive-Driven Waypoint-Aware World Model for Robotic Manipulation | [2410.10394](https://arxiv.org/abs/2410.10394) | [Website](https://octo-models.github.io) | 2024 | NeurIPS 24 poster | Waypoint Prediction, Primitive |

### 9.3 3D/4D Representations for Robotics

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| TesserAct: Learning 4D Embodied World Models | [2504.20995](https://arxiv.org/abs/2504.20995) | [Website](https://tesseractworld.github.io/) | 2025 | ICCV 25 | 4D WM, RGB-Depth-Normal |
| GWM: Towards Scalable Gaussian World Models for Robotic Manipulation | [2508.17600](https://arxiv.org/abs/2508.17600) | [Website](https://gaussian-world-model.github.io/) | 2025 | ICCV 25 | Gaussian Splatting, Neural Sim |
| 3D-VLA: A 3D Vision-Language-Action Generative World Model | [2403.09631](https://arxiv.org/abs/2403.09631) | [GitHub](https://github.com/UMass-Embodied-AGI/3D-VLA) | 2024 | ICML 24 poster | 3D WM, VLA |
| DexSim2Real2: Building Explicit World Model for Precise Articulated Object Dexterous Manipulation | [2409.08750](https://arxiv.org/abs/2409.08750) | [Website](https://jiangtaoran.github.io/dexsim2real2web/) | 2024 | arXiv | Digital Twin, Dexterous Hand |

### 9.4 Foundation-Scale & Embodied World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Causal World Modeling for Robot Control (LingBot-VA) | [2601.21998](https://arxiv.org/abs/2601.21998) | [GitHub](https://github.com/robbyant/lingbot-va) | 2026 | RSS 26 | Causal AR-Diffusion, MoT |
| DreamDojo: A Generalist Robot World Model from Large-Scale Human Videos | [2602.06949](https://arxiv.org/abs/2602.06949) | [Website](https://dreamdojo-world.github.io/) | 2026 | arXiv | Generalist Robot, NVIDIA |
| ABot-PhysWorld: Interactive World Foundation Model for Robotic Manipulation with Physics Alignment | [2602.23376](https://arxiv.org/abs/2602.23376) | [GitHub](https://github.com/amap-cvlab/ABot-PhysWorld) | 2026 | arXiv | Physics Alignment, Interactive |
| Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets | [2504.02792](https://arxiv.org/abs/2504.02792) | [Website](https://weirdlabuw.github.io/uwm/) | 2025 | RSS 25 | Joint Video-Action, Multi-Modal |
| Robotic World Model: A Neural Network Simulator for Robust Policy Optimization in Robotics | [2501.10100](https://arxiv.org/abs/2501.10100) | [GitHub](https://github.com/leggedrobotics/robotic_world_model) | 2025 | arXiv | Dual-AR, Sim-to-Real |
| RoboScape: Physics-informed Embodied World Model | [2506.23135](https://arxiv.org/abs/2506.23135) | [GitHub](https://github.com/tsinghua-fib-lab/RoboScape) | 2025 | NeurIPS 25 Spotlight | Physics-Informed, Temporal Depth |
| DiWA: Diffusion Policy Adaptation with World Models | [2508.03645](https://arxiv.org/abs/2508.03645) | / | 2025 | CoRL 25 | Diffusion Policy, Offline |
| GenRL: Multimodal-Foundation World Models for Generalization in Embodied Agents | [2406.18043](https://arxiv.org/abs/2406.18043) | [Website](https://mazpie.github.io/genrl/) | 2024 | NeurIPS 24 | VLM-Latent, Data-Free Policy |
| WHALE: Towards Generalizable and Scalable World Models for Embodied Decision-making | [2411.05619](https://arxiv.org/abs/2411.05619) | / | 2024 | ICLR 25 | Behavior-Conditioning, Open X |
| EVA: An Embodied World Model for Future Video Anticipation | [2410.15461](https://arxiv.org/abs/2410.15461) | [GitHub](https://github.com/litwellchi/EmbodiedVideoAnticipator) | 2024 | ICML 25 | Video Anticipation, Reflection |
| GenSim: Generating Robotic Simulation Tasks via Large Language Models | [2310.01361](https://arxiv.org/abs/2310.01361) | [GitHub](https://github.com/liruiw/GenSim) | 2023 | ICLR 24 | LLM Task Gen, Sim Curriculum |

---

## 10. LLM & Language-based World Models

Language models as world models — probing emergent representations and enabling planning.

### 10.1 Emergent World Representations in LLMs

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| A Causal World Model Underlying Next Token Prediction: Exploring GPT in a Controlled Environment | [2412.07446](https://arxiv.org/abs/2412.07446) | / | 2024 | arXiv | Causal WM, Othello/Chess |
| Language Models Represent Space and Time | [2310.02207](https://arxiv.org/abs/2310.02207) | [GitHub](https://github.com/wesg52/world-models) | 2023 | ICLR 24 | Spatiotemporal, Linear Probing |
| Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task (Othello-GPT) | [2210.13382](https://arxiv.org/abs/2210.13382) | [GitHub](https://github.com/likenneth/othello_world) | 2022 | ICLR 23 | Othello-GPT, Emergent WM |

### 10.2 LLM Planning with World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Making Large Language Models into World Models with Precondition and Effect Knowledge | [2409.12278](https://arxiv.org/abs/2409.12278) | / | 2024 | arXiv | Precondition-Effect, Action |
| Reasoning with Language Model is Planning with World Model | [2305.14992](https://arxiv.org/abs/2305.14992) | [GitHub](https://github.com/Ber666/llm-reasoners) | 2023 | EMNLP 23 | MCTS Planning, LLM-as-WM |
| Language Models Meet World Models: Embodied Experiences Enhance Language Models | [2305.10626](https://arxiv.org/abs/2305.10626) | [GitHub](https://github.com/szxiangjn/world-model-for-language-model) | 2023 | NeurIPS 23 | Embodied LLM, Grounding |
| SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning | [2307.06135](https://arxiv.org/abs/2307.06135) | [Website](https://sayplan.github.io) | 2023 | CoRL 23 | 3D Scene Graph, Task Planning |
| Voyager: An Open-Ended Embodied Agent with Large Language Models | [2305.16291](https://arxiv.org/abs/2305.16291) | [GitHub](https://github.com/MineDojo/Voyager) | 2023 | arXiv | Minecraft, Lifelong Learning |
| Inner Monologue: Embodied Reasoning through Planning with Language Models | [2207.05608](https://arxiv.org/abs/2207.05608) | [Website](https://innermonologue.github.io) | 2022 | CoRL 22 | Closed-Loop, Embodied Reasoning |

### 10.3 Multimodal & Large World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| WebWorld: A Large-Scale World Model for Web Agent Training | [2602.14721](https://arxiv.org/abs/2602.14721) | [GitHub](https://github.com/QwenLM/WebWorld) | 2026 | arXiv | Web Agent, Large-Scale WM |
| Text2World: Benchmarking Large Language Models for Symbolic World Model Generation | [2502.13092](https://arxiv.org/abs/2502.13092) | [Website](https://text-to-world.github.io/) | 2025 | ACL 25 | PDDL, Symbolic WM |
| Semantic World Models | [2510.19818](https://arxiv.org/abs/2510.19818) | [Website](https://weirdlabuw.github.io/swm) | 2025 | arXiv | VLM-as-WM, Language Output |
| DyMo: World Modelling Improves Language Model Agents | [2506.02918](https://arxiv.org/abs/2506.02918) | / | 2025 | arXiv | Dynamics Modelling, LLM Agent |
| World Model on Million-Length Video and Language with RingAttention (LWM) | [2402.08268](https://arxiv.org/abs/2402.08268) | [GitHub](https://github.com/LargeWorldModel/LWM) | 2024 | arXiv | Million-Token, Video-Language |
| Can Language Models Serve as Text-Based World Simulators? | [2406.06485](https://arxiv.org/abs/2406.06485) | [GitHub](https://github.com/cognitiveailab/GPT-simulator) | 2024 | ACL 24 | Text World Simulator, Evaluation |
| WorldGPT: Empowering LLM as Multimodal World Model | [2404.18202](https://arxiv.org/abs/2404.18202) | [GitHub](https://github.com/DCDmllm/WorldGPT) | 2024 | arXiv | Multimodal LLM, State Transition |
| WebDreamer: Is Your LLM Secretly a World Model of the Internet? | [2411.06559](https://arxiv.org/abs/2411.06559) | [GitHub](https://github.com/OSU-NLP-Group/WebDreamer) | 2024 | arXiv | Web Agent, Model-Based Planning |

---

## 11. 3D & 4D Spatial World Models

Generating and exploring 3D/4D worlds — from single images to unbounded scenes.

### 11.1 Unbounded 3D Scene Generation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| CityDreamer4D: Compositional Generative Model of Unbounded 4D Cities | [2501.08983](https://arxiv.org/abs/2501.08983) | [GitHub](https://github.com/hzxie/CityDreamer4D) | 2025 | TPAMI 26 | 4D City, Dynamic Vehicles |
| WorldGrow: Generating Infinite 3D World | [2510.21682](https://arxiv.org/abs/2510.21682) | [GitHub](https://github.com/world-grow/WorldGrow) | 2025 | arXiv | Infinite 3D, Unbounded |
| SceneDreamer: Unbounded 3D Scene Generation from 2D Image Collections | [2302.01330](https://arxiv.org/abs/2302.01330) | [GitHub](https://github.com/FrozenBurning/SceneDreamer) | 2023 | TPAMI 23 | Unbounded 3D, BEV, Hash Grid |
| CityDreamer: Compositional Generative Model of Unbounded 3D Cities | [2309.00610](https://arxiv.org/abs/2309.00610) | / | 2023 | CVPR 24 | Unbounded City, Compositional |

### 11.2 Explorable & Interactive 3D Worlds

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| MetaEarth3D: Unlocking World-scale 3D Generation with Spatially Scalable Generative Modeling | [2604.22828](https://arxiv.org/abs/2604.22828) | [Website](https://jinqicao.github.io/metaearth3d/) | 2026 | arXiv | Planetary-Scale 3D, Mesh |
| Matrix-3D: Omnidirectional Explorable 3D World Generation | [2508.08086](https://arxiv.org/abs/2508.08086) | [Website](https://matrix-3d.github.io) | 2025 | arXiv | Panoramic 3D, Omnidirectional |
| WonderWorld: Interactive 3D Scene Generation from a Single Image | [2406.09394](https://arxiv.org/abs/2406.09394) | [GitHub](https://github.com/KovenYu/WonderWorld) | 2024 | CVPR 25 | Single-Image, Gaussian Surfels |
| GenEx: Generating an Explorable World | [2412.09624](https://arxiv.org/abs/2412.09624) | [GitHub](https://github.com/GenEx-world/genex) | 2024 | ICLR 25 | Explorable 3D, Embodied Nav |
| Generative World Explorer | [2411.11844](https://arxiv.org/abs/2411.11844) | [Website](http://generative-world-explorer.github.io) | 2024 | ICLR 25 | Mental Exploration, Panoramic |

### 11.3 Gaussian Splatting & Neural Field World Models

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Neural Fields as World Models | [2602.18690](https://arxiv.org/abs/2602.18690) | / | 2026 | arXiv | Neural Fields, Isomorphic WM |
| DreamScene: 3D Gaussian-based Text-to-3D Scene Generation via Formation Pattern Sampling | [2404.03575](https://arxiv.org/abs/2404.03575) | [Website](https://dreamscene-project.github.io) | 2024 | ECCV 24 | Text-to-3D, 3D GS |
| Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics | [2406.10788](https://arxiv.org/abs/2406.10788) | [Website](https://embodied-gaussians.github.io/) | 2024 | arXiv | GS + Physics, Robotics |
| 4D Gaussian Splatting: Modeling Dynamic Scenes with Native 4D Primitives | [2412.20720](https://arxiv.org/abs/2412.20720) | / | 2024 | ICLR 24 | 4D GS, Dynamic Scene |
| LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes | [2311.13384](https://arxiv.org/abs/2311.13384) | [Website](https://luciddreamer-cvlab.github.io/) | 2023 | arXiv | 3D GS, Scene Generation |

### 11.4 4D World Generation & Video-to-3D/4D

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| NeoVerse: Enhancing 4D World Model with in-the-wild Monocular Videos | [2601.00393](https://arxiv.org/abs/2601.00393) | [Website](https://neoverse-4d.github.io) | 2026 | CVPR 26 Highlight | 4D WM, Monocular Video |
| PERSIST: Beyond Pixel Histories -- World Models with Persistent 3D State | [2603.03482](https://arxiv.org/abs/2603.03482) | [Website](https://francelico.github.io/persist.github.io) | 2026 | arXiv | Persistent 3D State, Beyond Pixels |
| Marble: A Multimodal World Model (World Labs) | / | / | 2026 | World Labs | 3D Generation, Gaussian Splatting |
| WorldForge: Taming Video Models for 3D and 4D Generation via Zero-Shot Camera Control | [2509.15130](https://arxiv.org/abs/2509.15130) | [Website](https://worldforge-agi.github.io/) | 2025 | CVPR 26 | Training-Free 3D/4D, Camera |
| TeleWorld: Towards Dynamic Multimodal Synthesis with a 4D World Model | [2601.00051](https://arxiv.org/abs/2601.00051) | / | 2025 | arXiv | 4D WM, Real-Time Multimodal |
| 3D4D: An Interactive, Editable, 4D World Model via 3D Video Generation | [2511.08536](https://arxiv.org/abs/2511.08536) | [Website](https://yunhonghe1021.github.io/NOVA/) | 2025 | AAAI 26 Demo | Interactive 4D, WebGL |
| DeepVerse: 4D Autoregressive Video Generation as a World Model | [2506.01103](https://arxiv.org/abs/2506.01103) | [Website](https://sotamak1r.github.io/deepverse/) | 2025 | arXiv | 4D AR, Geometric Prediction |
| GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control | / | / | 2025 | CVPR 25 | 3D-Consistent, Camera Control |

---

## 12. World Model Efficiency & Acceleration

Caching, pruning, quantization, and distillation techniques for faster world model inference.

### 12.1 Feature & Layer Caching

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| FlowCache: Flow Caching for Autoregressive Video Generation | [2602.10825](https://arxiv.org/abs/2602.10825) | [GitHub](https://github.com/mikeallen39/FlowCache) | 2026 | arXiv | Flow Caching, AR Video |
| Salt: Self-Consistent Distribution Matching with Cache-Aware Training for Fast Video Generation | [2604.03118](https://arxiv.org/abs/2604.03118) | [GitHub](https://github.com/XingtongGe/Salt) | 2026 | arXiv | Cache-Aware Training, Distillation |
| OmniCache: A Trajectory-Oriented Global Perspective on Training-Free Cache Reuse for DiT | [2508.16212](https://arxiv.org/abs/2508.16212) | / | 2025 | ICCV 25 | Trajectory-Oriented, Global |
| FastCache: Fast Caching for Diffusion Transformer Through Learnable Linear Approximation | [2505.20353](https://arxiv.org/abs/2505.20353) | [GitHub](https://github.com/NoakLiu/FastCache-xDiT) | 2025 | arXiv | Linear Approximation, DiT |
| SpeCa: Accelerating Diffusion Transformers with Speculative Feature Caching | [2509.11628](https://arxiv.org/abs/2509.11628) | [GitHub](https://github.com/Shenyi-Z/Cache4Diffusion) | 2025 | ACM MM 25 | Speculative Caching, Forecast |
| Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching | [2406.01733](https://arxiv.org/abs/2406.01733) | [GitHub](https://github.com/horseee/learning-to-cache) | 2024 | NeurIPS 24 | Learnable Caching, Layer-Skip |
| FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality | [2410.19355](https://arxiv.org/abs/2410.19355) | [GitHub](https://github.com/Vchitect/FasterCache) | 2024 | ICLR 25 poster | Feature Caching, Training-Free |
| AdaCache: Adaptive Caching for Faster Video Generation with Diffusion Transformers | [2411.02397](https://arxiv.org/abs/2411.02397) | [Website](https://adacache-dit.github.io) | 2024 | ICCV 25 | Motion Regularization, Adaptive |

### 12.2 World Model-Specific Acceleration

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| WorldCache: Accelerating World Models for Free via Heterogeneous Token Caching | [2603.06331](https://arxiv.org/abs/2603.06331) | [GitHub](https://github.com/FofGofx/WorldCache) | 2026 | arXiv | Curvature-Guided, Heterogeneous |
| WorldCache: Content-Aware Caching for Accelerated Video World Models | [2603.22286](https://arxiv.org/abs/2603.22286) | [Website](https://umair1221.github.io/World-Cache/) | 2026 | arXiv | Motion-Adaptive, Content-Aware |
| Fast Autoregressive Video Diffusion and World Models with Temporal Cache Compression and Sparse Attention | [2602.01801](https://arxiv.org/abs/2602.01801) | [Website](https://dvirsamuel.github.io/fast-auto-regressive-video/) | 2026 | arXiv | KV Cache Compress, Temporal |

### 12.3 Sparse Attention & Pruning

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Light Forcing: Accelerating Autoregressive Video Diffusion via Sparse Attention | [2602.04789](https://arxiv.org/abs/2602.04789) | [GitHub](https://github.com/chengtao-lv/LightForcing) | 2026 | arXiv | Sparse Attention, Acceleration |
| Dummy Forcing: Efficient Autoregressive Video Diffusion with Dummy Head | [2601.20499](https://arxiv.org/abs/2601.20499) | [Website](https://csguoh.github.io/project/DummyForcing/) | 2026 | arXiv | Dummy Head, Efficient |
| TokenTrim: Inference-Time Token Pruning for Autoregressive Long Video Generation | [2602.00268](https://arxiv.org/abs/2602.00268) | [Website](https://arielshaulov.github.io/TokenTrim/) | 2026 | arXiv | Token Pruning, Long Video |
| MonarchRT: Efficient Attention for Real-Time Video Generation | [2602.12271](https://arxiv.org/abs/2602.12271) | / | 2026 | arXiv | Monarch Attention, Real-Time |
| SVOO: Training-Free Sparse Attention for Fast Video Generation via Offline Sparsity Profiling | [2603.18636](https://arxiv.org/abs/2603.18636) | [GitHub](https://github.com/Mutual-Luo/SVOO) | 2026 | ICML 26 | Sparsity Profiling, Training-Free |
| Sparse Forcing: Native Trainable Sparse Attention for Real-time AR Diffusion Video Generation | [2604.21221](https://arxiv.org/abs/2604.21221) | / | 2026 | arXiv | Trainable Sparse, Native |
| Real-Time Video Generation with Pyramid Attention Broadcast (PAB) | [2408.12588](https://arxiv.org/abs/2408.12588) | [GitHub](https://github.com/NUS-HPC-AI-Lab/OpenDiT) | 2024 | ICLR 2025 | Attention Broadcast, Real-Time |

### 12.4 KV Cache & Quantization

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| PaFu-KV: Past- and Future-Informed KV Cache Policy with Salience Estimation in AR Video Diffusion | [2601.21896](https://arxiv.org/abs/2601.21896) | / | 2026 | arXiv | KV Cache Policy, Salience |
| Quant VideoGen: Auto-Regressive Long Video Generation via 2-Bit KV-Cache Quantization | [2602.02958](https://arxiv.org/abs/2602.02958) | [GitHub](https://github.com/svg-project/Quant-VideoGen) | 2026 | ICML 26 | 2-Bit KV, Memory-Efficient |
| KV Cache Quantization for Self-Forcing Video Generation: A 33-Method Empirical Study | [2603.27469](https://arxiv.org/abs/2603.27469) | [GitHub](https://github.com/suraj-ranganath/kv-quant-longhorizon) | 2026 | arXiv | Quantization Benchmark |

### 12.5 Distillation & Speculative Decoding

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| SDVG: Speculative Decoding for Autoregressive Video Generation | [2604.17397](https://arxiv.org/abs/2604.17397) | [GitHub](https://github.com/krea-ai/realtime-video) | 2026 | arXiv | Speculative Decoding, Speedup |
| TurboDiffusion: Accelerating Video Diffusion Models by 100-200 Times | [2512.16093](https://arxiv.org/abs/2512.16093) | [GitHub](https://github.com/thu-ml/TurboDiffusion) | 2025 | arXiv | Step Distillation, Quantization |
| TWIST: Teacher-Student World Model Distillation for Efficient Sim-to-Real Transfer | [2311.03622](https://arxiv.org/abs/2311.03622) | / | 2023 | arXiv | WM Distillation, Sim-to-Real |

---

## 13. Physics-Informed & Physics-Grounded World Models

World models with explicit physics understanding, simulation, and grounding.

### 13.1 Physics-Grounded 3D/4D Generation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Phys4D: Fine-Grained Physics-Consistent 4D Modeling from Video Diffusion | [2603.03485](https://arxiv.org/abs/2603.03485) | / | 2026 | arXiv | 4D Physics, RL |
| PhysGen3D: Crafting a Miniature Interactive World from a Single Image | [2503.20746](https://arxiv.org/abs/2503.20746) | [Website](https://by-luckk.github.io/PhysGen3D) | 2025 | CVPR 25 | Interactive 3D, Physics Sim |
| PhysForge: Generating Physics-Grounded 3D Assets for Interactive Virtual World | [2605.05163](https://arxiv.org/abs/2605.05163) | [Website](https://hku-mmlab.github.io/PhysForge/) | 2025 | ICML 26 | Kinematic Annotation, Virtual |
| PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation | [2404.13026](https://arxiv.org/abs/2404.13026) | [Website](https://physdreamer.github.io/) | 2024 | ECCV 24 | 3D Interaction, Material |
| PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics | [2311.12198](https://arxiv.org/abs/2311.12198) | [Website](https://xpandora.github.io/PhysGaussian/) | 2024 | CVPR 24 Highlight | MPM Physics, 3D GS |
| PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation | [2409.18964](https://arxiv.org/abs/2409.18964) | [Website](https://stevenlsw.github.io/physgen/) | 2024 | ECCV 24 | Rigid Body, Force-Conditioned |
| PhysMotion: Physics-Grounded Dynamics From a Single Image | [2411.17189](https://arxiv.org/abs/2411.17189) | [Website](https://supertan0204.github.io/physmotion_website/) | 2024 | arXiv | Continuum Mechanics, MPM |
| Phys4DGen: Physics-Compliant 4D Generation with Multi-Material Composition | [2411.16800](https://arxiv.org/abs/2411.16800) | [Website](https://jiajinglin.github.io/Phys4DGen) | 2024 | arXiv | 4D Gen, Multi-Material |

### 13.2 Physics-Grounded Video Generation

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| PhysVideoGenerator: Towards Physically Aware Video Generation via Latent Physics Guidance | [2601.03665](https://arxiv.org/abs/2601.03665) | [GitHub](https://github.com/CVFall2025-Project/PhysVideoGenerator) | 2026 | arXiv | V-JEPA Alignment, Latent |
| PhysRVG: Physics-Aware Unified RL for Video Generative Models | [2601.11087](https://arxiv.org/abs/2601.11087) | / | 2026 | arXiv | Physics RL Reward, Collision |
| PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation | [2509.20358](https://arxiv.org/abs/2509.20358) | [Website](https://cwchenwang.github.io/physctrl) | 2025 | NeurIPS 25 | Multi-Material Dynamics |
| PhyT2V: LLM-Guided Iterative Self-Refinement for Physics-Grounded T2V | [2412.00596](https://arxiv.org/abs/2412.00596) | [GitHub](https://github.com/pittisl/PhyT2V) | 2024 | arXiv | LLM-Guided, Prompt Refinement |
| How Far is Video Generation from World Model: A Physical Law Perspective | [2411.02385](https://arxiv.org/abs/2411.02385) | [Website](https://phyworld.github.io) | 2024 | ICML 25 | Physical Laws, Evaluation |
| PhysDiff: Physics-Guided Human Motion Diffusion Model | [2212.02500](https://arxiv.org/abs/2212.02500) | [Website](https://nvlabs.github.io/PhysDiff) | 2023 | ICCV 23 Oral | Human Motion, Physics Sim |

### 13.3 Physics-Informed World Models & Theory

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Interpreting Physics in Video World Models | [2602.07050](https://arxiv.org/abs/2602.07050) | / | 2026 | arXiv | Distributed Repr., Probing |
| PIN-WM: Learning Physics-INformed World Models for Non-Prehensile Manipulation | [2504.16693](https://arxiv.org/abs/2504.16693) | [Website](https://pinwm.github.io) | 2025 | arXiv | Differentiable Physics |
| Four Principles for Physically Interpretable World Models | [2503.02143](https://arxiv.org/abs/2503.02143) | [GitHub](https://github.com/trustworthy-engineered-autonomy-lab/piwm-principles) | 2025 | arXiv | Design Principles, Symbolic |
| Intuitive Physics Understanding Emerges from Self-Supervised Pretraining on Natural Videos | [2502.11831](https://arxiv.org/abs/2502.11831) | [GitHub](https://github.com/facebookresearch/jepa-intuitive-physics) | 2025 | arXiv | V-JEPA, Intuitive Physics |
| Physically Interpretable World Models via Weakly Supervised Representation Learning | [2412.12870](https://arxiv.org/abs/2412.12870) | / | 2024 | arXiv | Physical Interpretability |
| GenPhys: From Physical Processes to Generative Models | [2304.02637](https://arxiv.org/abs/2304.02637) | / | 2023 | arXiv | PDE-to-Generative, Duality |

---

## 14. Weather, Climate & Earth System Models

Neural weather prediction and earth system simulation as world models.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| GenCast: Diffusion-based Ensemble Forecasting for Medium-Range Weather | [2312.15796](https://arxiv.org/abs/2312.15796) | [GitHub](https://github.com/google-deepmind/graphcast) | 2024 | Nature 2024 | Diffusion, Ensemble |
| Aurora: A Foundation Model of the Atmosphere | [2405.13063](https://arxiv.org/abs/2405.13063) | [GitHub](https://github.com/microsoft/aurora) | 2024 | Nature 2025 | Earth System, Air Quality |
| NeuralGCM: Neural General Circulation Models for Weather and Climate | [2311.07222](https://arxiv.org/abs/2311.07222) | [GitHub](https://github.com/google-research/dinosaur) | 2024 | Nature 2024 | Hybrid Physics-ML, GCM |
| Stormer: Scaling Transformer Neural Networks for Skillful Medium-Range Weather Forecasting | [2312.03876](https://arxiv.org/abs/2312.03876) | [GitHub](https://github.com/tung-nd/stormer) | 2024 | NeurIPS 24 | Scalable, WeatherBench 2 |
| WeatherBench 2: A Benchmark for the Next Generation of Data-Driven Global Weather Models | [2308.15560](https://arxiv.org/abs/2308.15560) | [GitHub](https://github.com/google-research/weatherbench2) | 2024 | JAMES 24 | Benchmark, Evaluation |
| GraphCast: Learning Skillful Medium-Range Global Weather Forecasting | [2212.12794](https://arxiv.org/abs/2212.12794) | [GitHub](https://github.com/deepmind/graphcast) | 2023 | Science 2023 | GNN, Weather Forecasting |
| Pangu-Weather: A 3D High-Resolution Model for Fast and Accurate Global Weather Forecast | [2211.02556](https://arxiv.org/abs/2211.02556) | [GitHub](https://github.com/198808xc/Pangu-Weather) | 2023 | Nature 2023 | 3D Transformer, ERA5 |
| ClimaX: A Foundation Model for Weather and Climate | [2301.10343](https://arxiv.org/abs/2301.10343) | [GitHub](https://github.com/microsoft/ClimaX) | 2023 | ICML 23 | Foundation Model, Multi-Task |
| FourCastNet: A Global Data-driven High-resolution Weather Model using Adaptive Fourier Neural Operators | [2202.11214](https://arxiv.org/abs/2202.11214) | [GitHub](https://github.com/NVIDIA/makani) | 2022 | arXiv | FNO, NVIDIA |

---

## 15. Learnable Physics Simulators

Neural surrogates for physical simulation — particles, meshes, fluids, and plasma.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Hybrid Neural-MPM for Interactive Fluid Simulations in Real-Time | [2505.18926](https://arxiv.org/abs/2505.18926) | [Website](https://hybridmpm.github.io/) | 2025 | arXiv | Real-Time Fluid, Hybrid |
| 5D Neural Surrogates for Nonlinear Gyrokinetic Simulations of Plasma Turbulence | [2502.07469](https://arxiv.org/abs/2502.07469) | / | 2025 | arXiv | Nuclear Fusion, 5D |
| Neural SPH: Improved Neural Modeling of Lagrangian Fluid Dynamics | [2402.06275](https://arxiv.org/abs/2402.06275) | [GitHub](https://github.com/tumaer/neuralsph) | 2024 | ICML 24 | SPH, Fluid, GNN |
| Physics-Preserving AI-Accelerated Simulations of Plasma Turbulence | [2309.16400](https://arxiv.org/abs/2309.16400) | / | 2023 | arXiv | Plasma, 1000x Speedup |
| Learning Mesh-Based Simulation with Graph Networks (MeshGraphNets) | [2010.03409](https://arxiv.org/abs/2010.03409) | [GitHub](https://github.com/google-deepmind/deepmind-research/tree/master/meshgraphnets) | 2021 | ICLR 21 Outstanding Paper | Mesh Simulation, Aerodynamics |
| Learning to Simulate Complex Physics with Graph Networks (GNS) | [2002.09405](https://arxiv.org/abs/2002.09405) | [GitHub](https://github.com/google-deepmind/deepmind-research/tree/master/learning_to_simulate) | 2020 | ICML 20 | GNN Simulator, Particle |
| Visual Interaction Networks | [1706.01433](https://arxiv.org/abs/1706.01433) | / | 2017 | arXiv | Visual Physics, Dynamics |
| Interaction Networks for Learning about Objects, Relations and Physics | [1612.00222](https://arxiv.org/abs/1612.00222) | / | 2016 | NeurIPS 16 | Relational Reasoning, Physics |
| A Compositional Object-Based Approach to Learning Physical Dynamics (Neural Physics Engine) | [1612.00341](https://arxiv.org/abs/1612.00341) | [GitHub](https://github.com/mbchang/dynamics) | 2016 | ICLR 17 | Object Dynamics, Compositional |

---

## 16. Scientific & Medical World Models

World models for biological simulation, medical planning, and scientific discovery.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| NeuralOM: Neural Ocean Model for Subseasonal-to-Seasonal Simulation | [2505.21020](https://arxiv.org/abs/2505.21020) | [GitHub](https://github.com/YuanGao-YG/NeuralOM) | 2026 | arXiv | Ocean, Long-Term Stability |
| Medical World Model: Generative Simulation of Tumor Evolution for Treatment Planning | [2506.02327](https://arxiv.org/abs/2506.02327) | / | 2025 | arXiv | Tumor Simulation, Treatment |
| Surgical Vision World Model | [2503.02904](https://arxiv.org/abs/2503.02904) | [GitHub](https://github.com/bhattarailab/Surgical-Vision-World-Model) | 2025 | arXiv | Surgical Simulation, Medical |
| UniSim: A Unified Simulator for Time-Coarsened Dynamics of Biomolecules | [2506.03157](https://arxiv.org/abs/2506.03157) | [GitHub](https://github.com/yaledeus/UniSim) | 2025 | ICML 25 | Molecular Dynamics, Biomolecule |
| VCWorld: A Biological World Model for Virtual Cell Simulation | [2512.00306](https://arxiv.org/abs/2512.00306) | [GitHub](https://github.com/GENTEL-lab/VCWorld) | 2024 | ICLR 26 | Virtual Cell, Drug Perturbation |
| Ola: Coupled Ocean-Atmosphere Dynamics in a Machine Learning Earth System Model | [2406.08632](https://arxiv.org/abs/2406.08632) | / | 2024 | arXiv | Ocean-Atmosphere, ENSO |
| Samudra: An AI Global Ocean Emulator for Climate | [2412.03795](https://arxiv.org/abs/2412.03795) | / | 2024 | arXiv | Century-Scale, Climate |

---

## 17. Long-Horizon & Memory-Augmented World Models

Techniques for maintaining consistency and memory over extended temporal horizons.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Context Forcing: Consistent Autoregressive Video Generation with Long Context | [2602.06028](https://arxiv.org/abs/2602.06028) | [GitHub](https://github.com/TIGER-AI-Lab/Context-Forcing) | 2026 | arXiv | Long-Context, Consistency |
| MosaicMem: Hybrid Spatial Memory for Controllable Video World Models | [2603.17117](https://arxiv.org/abs/2603.17117) | [Website](https://mosaicmem.github.io/mosaicmem/) | 2026 | arXiv | Spatial Memory, Controllable |
| HyDRA: Out of Sight but Not Out of Mind -- Hybrid Memory for Dynamic Video World Models | [2603.25716](https://arxiv.org/abs/2603.25716) | [GitHub](https://github.com/H-EmbodVis/HyDRA) | 2026 | arXiv | Hybrid Memory, Dynamic |
| ViewRope: Geometry-Aware Rotary Position Embedding for Consistent Video World Model | [2602.07854](https://arxiv.org/abs/2602.07854) | / | 2026 | arXiv | Geometry-Aware RoPE |
| UCM: Unifying Camera Control and Memory with Time-Aware Positional Encoding Warping | [2602.22960](https://arxiv.org/abs/2602.22960) | [Website](https://humanaigc.github.io/ucm-webpage/) | 2026 | arXiv | Camera Control, Memory |
| WORLDMEM: Long-term Consistent World Simulation with Memory | [2504.12369](https://arxiv.org/abs/2504.12369) | [Website](https://xizaoqu.github.io/worldmem/) | 2025 | arXiv | Long-Term Memory, Consistency |
| Long-Context State-Space Video World Models | / | / | 2025 | ICCV 25 | SSM, Constant Inference Cost |
| Learning Transformer-Based World Models with Contrastive Predictive Coding | / | / | 2025 | ICLR 25 | Contrastive Prediction, Transformer |

---

## 18. Theory & World Model Explainability

Theoretical foundations, interpretability, and understanding of what world models learn.

| Title | arXiv | GitHub | Year | Venue | Keywords |
|-------|-------|--------|------|-------------|----------|
| Interpreting Physics in Video World Models | [2602.07050](https://arxiv.org/abs/2602.07050) | / | 2026 | arXiv | Distributed Repr., Probing |
| Neural Fields as World Models | [2602.18690](https://arxiv.org/abs/2602.18690) | / | 2026 | arXiv | Neural Fields, Isomorphic WM |
| Intuitive Physics Understanding Emerges from Self-Supervised Pretraining | [2502.11831](https://arxiv.org/abs/2502.11831) | [GitHub](https://github.com/facebookresearch/jepa-intuitive-physics) | 2025 | arXiv | V-JEPA, Intuitive Physics |
| Four Principles for Physically Interpretable World Models | [2503.02143](https://arxiv.org/abs/2503.02143) | [GitHub](https://github.com/trustworthy-engineered-autonomy-lab/piwm-principles) | 2025 | arXiv | Design Principles, Symbolic |
| A Unified Definition of Hallucination, Or: It's the World Model, Stupid | [2512.21577](https://arxiv.org/abs/2512.21577) | [GitHub](https://github.com/DegenAI-Labs/HalluWorld) | 2025 | arXiv | Hallucination, Definition |
| A Causal World Model Underlying Next Token Prediction | [2412.07446](https://arxiv.org/abs/2412.07446) | / | 2024 | arXiv | Causal WM, Chess/Othello |
| Physically Interpretable World Models via Weakly Supervised Representation Learning | [2412.12870](https://arxiv.org/abs/2412.12870) | / | 2024 | arXiv | Physical Interpretability |
| Language Models Represent Space and Time | [2310.02207](https://arxiv.org/abs/2310.02207) | [GitHub](https://github.com/wesg52/world-models) | 2023 | ICLR 24 | Spatiotemporal, Linear Probing |
| GenPhys: From Physical Processes to Generative Models | [2304.02637](https://arxiv.org/abs/2304.02637) | / | 2023 | arXiv | PDE-to-Generative, Duality |
| Emergent World Representations: Exploring a Sequence Model (Othello-GPT) | [2210.13382](https://arxiv.org/abs/2210.13382) | [GitHub](https://github.com/likenneth/othello_world) | 2022 | ICLR 23 | Emergent WM, Probing |

---

## Related Resources

### Key Workshops & Venues (2025-2026)

- **ICLR 2025 Workshop**: "World Models: Understanding, Modelling and Scaling" (Singapore)
- **ICLR 2026 Workshop**: "World Models: Understanding, Modelling and Scaling" 2nd Edition (Rio)
- **CVPR 2025 Tutorial**: "From Video Generation to World Model"
- **CVPR 2025 Workshop**: "World Model Bench"
- **ICML 2025 Workshop**: "Assessing World Models"
- **NeurIPS 2025 Workshop**: "Embodied World Models for Decision Making"
- **ICCV 2025 Workshop**: "Reliable and Interactable World Models"

---

## Contributing

If you find missing papers or errors, please open an issue or submit a pull request.

## Citation

If you find this survey useful, please consider citing:

```bibtex
@misc{awesome-world-models-2026,
  author={Ying Li},
  title={Awesome World Models: A Comprehensive Survey},
  year={2026},
  url={https://github.com/NeuraLiying/Awesome-World-Models}
}
```