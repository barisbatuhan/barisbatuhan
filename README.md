### Hi there 👋

- I am a Research Scientist & Engineer @ [Pixery Labs](https://www.pixerylabs.com/) and currently working on diffusion-based image & character generation and media quality enhancement.
- In September 2022, I graduated from my M.Sc. degree @ Koç University, [KUIS AI Center](https://ai.ku.edu.tr/). I was a member of [Intelligent User Interfaces](https://iui.ku.edu.tr/) lab and worked on deep detection and recognition models on drawings, comic books, cartoons and animations. 

# 📫 Links

[![CV](https://img.shields.io/badge/Personal-CV-green)](https://docs.google.com/document/d/1n1jQHmRx_SDG29gy4IX7imZTzznWo0H5WJ8NzU2BsZo/edit?usp=sharing)
[![LinkedIn](https://img.shields.io/badge/Linked-In-blue)](https://www.linkedin.com/in/barisbatuhan)
[![GoogleScholar](https://img.shields.io/badge/Google-Scholar-purple)](https://scholar.google.com/citations?user=nvt9dGsAAAAJ&hl=en)
[![Website](https://img.shields.io/badge/Personal-Website-red)](https://barisbatuhan.github.io/)

# ⚡ Projects

### 1. Meta-LoRA: Meta-Learning LoRA Components for Domain-Aware ID Personalization 

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2503.22352) [![Code](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/barisbatuhan/Meta-LoRA)

Recent advancements in text-to-image generative models, particularly latent diffusion models (LDMs), have demonstrated remarkable capabilities in synthesizing high-quality images from textual prompts. However, achieving identity personalization-ensuring that a model consistently generates subject-specific outputs from limited reference images-remains a fundamental challenge. To address this, we introduce Meta-Low-Rank Adaptation (Meta-LoRA), a novel framework that leverages meta-learning to encode domain-specific priors into LoRA-based identity personalization. Our method introduces a structured three-layer LoRA architecture that separates identity-agnostic knowledge from identity-specific adaptation. In the first stage, the LoRA Meta-Down layers are meta-trained across multiple subjects, learning a shared manifold that captures general identity-related features. In the second stage, only the LoRA-Mid and LoRA-Up layers are optimized to specialize on a given subject, reducing adaptation time while improving identity fidelity. 

### 2. DASS-Detector: Domain-Adaptive Self-Supervised Pre-Training for Face & Body Detection in Drawings

[![IJCAI 2023](https://img.shields.io/badge/IJCAI_2023-Paper-purple)](https://www.ijcai.org/proceedings/2023/0159.pdf)
[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2211.10641) 
[![Training Code](https://img.shields.io/badge/GitHub-Training_Code-blue)](https://github.com/barisbatuhan/DASS_Detector)
[![Inference Code](https://img.shields.io/badge/GitHub-Inference_Code-orange)](https://github.com/barisbatuhan/DASS_Det_Inference)

Drawing is one of the instruments that people use to convey stories and share their thoughts and feelings. Since the amount of labeled data is limited in the drawings domain, I utilize a wide range of style-transfer techniques (11 styles from 4 studies) on the real-life face and body datasets COCO & WIDER FACE. Furthermore, drawings contain enormous stylistic differences. Thus, I transfer a real-life detector model to this target domain and benefit from a self-supervised teacher-student training structure from raw drawing data. I provide an upper bound by training a fully-supervised detector model with a mixture of all the available labeled data. The supervised model achieves state-of-the-art performance

### 3. SSuperGAN: Face Generation In Golden Age Comics

[![Code](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/barisbatuhan/SSuperGAN)

 Worked on Context-based Face Generation in Golden Age Comics (US Comics between the 1930s-1950s). The model predicts the masked face by giving consecutive comic book panels to the model with a randomly selected face masked at the last frame.
 

### 4. Comic Media Annotator

[![Code](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/barisbatuhan/ComicAnnotator)

An annotator application implemented with Tkinter that is capable of bounding box drawing, character recognition labeling, speech bubble-face-character asssociation, and much more.

<!--

### 4. Multimodal Emotion Recognition in Comics

[![Code](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/inzva/emotion-recognition-drawings)

**barisbatuhan/barisbatuhan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
