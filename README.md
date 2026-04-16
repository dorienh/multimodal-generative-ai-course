# Multimodal Generative AI

**Graduate Course (Master's / PhD level) at SUTD**

**Instructor:** Assoc. Prof Dorien Herremans

This repository contains course materials for a graduate-level course on multimodal generative AI. The course covers foundational vision and audio models, multimodal alignment, retrieval-augmented generation, and agentic AI systems — combining lectures, hands-on labs, and seminar paper discussions.

Note: Prof. Wenxuan teaches the NLP part of this course, that part is not included in this repo. 

---

## Course Overview

| # | Topic | Slides | iPython Notebook | Papers |
|---|-------|--------|----------|--------|
| 1 | [Foundational Vision Models](#1-foundational-vision-models) | [PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/01-foundational-vision/Lecture-Foundational-Vision-Models.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10cVmXCVKmWn1OFgwqJnz2l6ZZkEMCODO) part 1 · [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10_xZUvAlMaUltccCfrE-XCEcJPG3mkGe) part 2 | — |
| 2 | [Foundational Audio Models](#2-foundational-audio-models) | [PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/02-foundational-audio/Lecture-Foundational-Generative-Audio-Models.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1whh2du8Br5X0DNiUwmV03VBNFbUJnxuH) | — |
| 3 | [Multimodal Models & Alignment](#3-multimodal-models--alignment) | [PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/03-multimodal-alignment/Lecture-Multimodal-Alignment.pdf) | — | [5 papers](#topic-3-reading-list) |
| 4 | [Retrieval-Augmented Generation (RAG)](#4-retrieval-augmented-generation) | [PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/04-retrieval-augmented-generation/Lecture-Grounding-and-RAG-Systems.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I0ZIL6JTdMihfhjwaHqWKMuBua_px3pN) | [5 papers](#topic-4-reading-list) |
| 5 | [Agentic AI & Tool-Using Systems](#5-agentic-ai--tool-using-systems) | — | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VON_Hv16y3lcy-sLy733GQ6hKTfBb6xw) | — |

---

## Topic Details

### 1. Foundational Vision Models

From convolutional networks to modern vision transformers and generative models.

**Topics covered:**
- CNNs to Vision Transformers (ViT)
- Self-supervised visual representations: SimCLR, DINOv2
- Generative models for vision: DALL·E, Stable Diffusion
- Diffusion models: core concepts and training

**Materials:** [Slides PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/01-foundational-vision/Lecture-Foundational-Vision-Models.pdf) · [Slides (interactive)](https://gamma.app/docs/Foundational-Vision-Models-n2y73wny11mzx4w) · Lab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10cVmXCVKmWn1OFgwqJnz2l6ZZkEMCODO) part 1 · [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10_xZUvAlMaUltccCfrE-XCEcJPG3mkGe) part 2

---

### 2. Foundational Audio Models

From signal representations to neural audio generation.

**Topics covered:**
- Spectrograms and audio tokenization
- Neural audio encoders: EnCodec, VQ-VAE
- Autoregressive models: WaveNet, Jukebox, AudioLM
- Diffusion for audio: Stable Audio

**Materials:** [Slides PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/02-foundational-audio/Lecture-Foundational-Generative-Audio-Models.pdf) · [Slides (interactive)](https://gamma.app/docs/Foundational-Generative-Audio-Models-010yv5v09ynk2k5) · Lab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1whh2du8Br5X0DNiUwmV03VBNFbUJnxuH)

---

### 3. Multimodal Models & Alignment

Connecting modalities through shared representations and cross-modal learning.

**Topics covered:**
- Multimodal representations: CLIP, CLAP, MuLAN
- Architectures for merging modalities
- Seminar: discussion of 5 foundational papers

**Materials:** [Slides PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/03-multimodal-alignment/Lecture-Multimodal-Alignment.pdf) · [Slides (interactive)](https://gamma.app/docs/Multimodal-Alignment-535epu986nuq07z)

#### Topic 3 Reading List

| Paper | Link |
|-------|------|
| Rombach et al. (2022). High-resolution image synthesis with latent diffusion models. *[Stable Diffusion]* | [arXiv:2112.10752](https://arxiv.org/abs/2112.10752) |
| Radford et al. (2021). Learning transferable visual models from natural language supervision. *[CLIP]* | [arXiv:2103.00020](https://arxiv.org/abs/2103.00020) |
| Borsos et al. (2022). AudioLM: A language modeling approach to audio generation. | [arXiv:2209.03143](https://arxiv.org/abs/2209.03143) |
| Copet et al. (2023). Simple and controllable music generation. *[MusicGen]* | [arXiv:2306.05284](https://arxiv.org/abs/2306.05284) |
| Liu et al. (2023). Visual instruction tuning. *[LLaVA]* | [arXiv:2304.08485](https://arxiv.org/abs/2304.08485) |

---

### 4. Retrieval-Augmented Generation

Grounding large generative models with external knowledge.

**Topics covered:**
- RAG pipeline architecture and components
- Vector databases and similarity metrics
- Grounding strategies: prompt patterns, multimodal RAG
- Hands-on lab

**Materials:** [Slides PDF](https://github.com/dorienh/multimodal-generative-ai-course/raw/main/04-retrieval-augmented-generation/Lecture-Grounding-and-RAG-Systems.pdf) · [Slides (interactive)](https://gamma.app/docs/Grounding-and-RAG-Systems-jwy6khm9f7wpnub) · Lab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1I0ZIL6JTdMihfhjwaHqWKMuBua_px3pN)

#### Topic 4 Reading List

| Paper | Link |
|-------|------|
| Girdhar et al. (2023). ImageBind: One embedding space to bind them all. | [arXiv:2305.05665](https://arxiv.org/abs/2305.05665) |
| Wu et al. (2022). CLAP: Learning audio concepts from natural language supervision. | [arXiv:2206.04769](https://arxiv.org/abs/2206.04769) |
| Ramesh et al. (2022). Hierarchical text-conditional image generation with CLIP latents. *[DALL·E 2]* | [arXiv:2204.06125](https://arxiv.org/abs/2204.06125) |
| Rafailov et al. (2023). Direct preference optimization: Your language model is secretly a reward model. *[DPO]* | [arXiv:2305.18290](https://arxiv.org/abs/2305.18290) |
| Kondratyuk et al. (2023). VideoPoet: A large language model for zero-shot video generation. | [arXiv:2312.14125](https://arxiv.org/abs/2312.14125) |

---

### 5. Agentic AI & Tool-Using Systems

Building and evaluating AI systems that reason, plan, and use tools.

**Topics covered:**
- Scratchpads and chain-of-thought reasoning
- Tool use and function calling
- Model Context Protocol (MCP)
- Workflow orchestration with LangGraph
- Safety evaluation with NVIDIA Garak
- Multi-agent coordination patterns

**Materials:** Lab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VON_Hv16y3lcy-sLy733GQ6hKTfBb6xw)

---

## Repository Structure

```
.
├── 01-foundational-vision/          # Foundational Vision Models
│   ├── Lecture-Foundational-Vision-Models.pdf
│   └── lab_01-foundational-vision/lab_Foundational_vision_part_I.ipynb
│   └── lab_01-foundational-vision/lab_Foundational_vision_part_II.ipynb
├── 02-foundational-audio/          # Foundational Audio Models
│   ├── Lecture-Foundational-Generative-Audio-Models.pdf
│   └── lab_foundational_audio.ipynb
├── 03-multimodal-alignment/          # Multimodal Models & Alignment
│   └── Lecture-Multimodal-Alignment.pdf
├── 04-retrieval-augmented-generation/          # Retrieval-Augmented Generation
│   ├── Lecture-Grounding-and-RAG-Systems.pdf
│   └── lab_RAG.ipynb
└── 05-agentic-ai/          # Agentic AI & Tool-Using Systems
    └── lab_agentic_AI_MCP_LangGraph.ipynb
```

---

## Prerequisites

Students are expected to have:
- Familiarity with deep learning fundamentals (transformers, backpropagation)
- Python proficiency
- Basic experience with PyTorch or a similar framework

---

## License

© Dorien Herremans. CC BY-NC 4.0 licence.

---

## Citation

If you use or adapt these materials, please cite:

```bibtex
@misc{herremans2025multimodal,
  author    = {Dorien Herremans},
  title     = {Multimodal Generative AI: Graduate Course Materials},
  year      = {2026},
  publisher = {GitHub},
  url       = {https://github.com/dorienh/multimodal-generative-ai}
}
```

---

*Questions or feedback? Open an issue or reach out via dorienherremans.com.*
