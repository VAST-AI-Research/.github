<div align="center">

# VAST AI Research · Generative 3D & World Models

**Open models from the team behind [Tripo](https://www.tripo3d.ai): generative 3D, 3D intelligence and interactive world models, built for creators, developers and AI agents.**

[![Tripo Studio](https://img.shields.io/badge/Tripo-Studio-black)](https://studio.tripo3d.ai/) [![Tripo API](https://img.shields.io/badge/Tripo-API-blue)](https://developers.tripo3d.ai/) [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97-VAST--AI-yellow)](https://huggingface.co/VAST-AI) [![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white)](https://discord.com/invite/tripoai) [![X](https://img.shields.io/badge/@VastAIResearch-black?logo=x)](https://x.com/VastAIResearch)

</div>

VAST builds **Tripo**, an AI 3D platform used through [Tripo Studio](https://studio.tripo3d.ai/), the [Tripo API](https://developers.tripo3d.ai/), and by coding agents through the [Tripo CLI](#-tripo-for-agents--developers). This organization holds the open code, weights and demos from our [research team](https://www.tripo3d.ai/research), with papers at SIGGRAPH, SIGGRAPH Asia, CVPR, ICCV, ICLR and NeurIPS.

**What we work on:** 3D foundation models · animation-ready assets & auto-rigging · part-aware, editable 3D · 3D Gaussians · agentic materials & shaders · single-image 3D scenes · world models & real-time generative rendering ([Project Eden](https://vast-eden.ai/))

## 🧭 What are you building?

| Goal | Start with |
|---|---|
| Let Claude Code, Codex or Cursor generate 3D assets | [**Tripo CLI**](#-tripo-for-agents--developers) |
| A detailed 3D mesh from one image | [**TripoSG**](https://github.com/VAST-AI-Research/TripoSG) · [TripoSR](https://github.com/VAST-AI-Research/TripoSR) (under 0.5 s on an A100) |
| 3D Gaussians with a controllable splat budget | [**TripoSplat**](https://github.com/VAST-AI-Research/TripoSplat) |
| Characters that are ready to animate | [**AniGen**](https://github.com/VAST-AI-Research/AniGen) · [SkinTokens](https://github.com/VAST-AI-Research/SkinTokens) · [UniRig](https://github.com/VAST-AI-Research/UniRig) |
| Editable 3D, split into complete parts | [**HoloPart**](https://github.com/VAST-AI-Research/HoloPart) · [GeoSAM2](https://github.com/VAST-AI-Research/GeoSAM2) |
| A 3D scene from a single photo | [**Mira-Scene**](https://github.com/VAST-AI-Research/Mira-Scene) · [MIDI-3D](https://github.com/VAST-AI-Research/MIDI-3D) |
| Textures, or Blender shaders written by an agent | [**SeqTex**](https://github.com/VAST-AI-Research/SeqTex) · [ShaderAgent](https://github.com/VAST-AI-Research/ShaderAgent) |
| Real-time generative rendering for a game or simulation | [**EdenLive**](https://github.com/VAST-AI-Research/EdenLive) |
| Stereo or multi-view video for world models | [**StereoWorld**](https://github.com/VAST-AI-Research/StereoWorld) · [MultiLive](https://github.com/VAST-AI-Research/MultiLive) |

## 🔥 News

- **2026-10** · [EdenLive](https://github.com/VAST-AI-Research/EdenLive) open-sourced: real-time generative rendering from any visual reference, 24+ FPS on a single consumer GPU.
- **2026-09** · [Mira-Scene](https://github.com/VAST-AI-Research/Mira-Scene) released with code, checkpoints and fine-tuning data.
- **2026** · [TripoSplat](https://github.com/VAST-AI-Research/TripoSplat) and [AniGen](https://github.com/VAST-AI-Research/AniGen) at SIGGRAPH 2026; [ShaderAgent](https://github.com/VAST-AI-Research/ShaderAgent) at SIGGRAPH Asia 2026; [GeoSAM2](https://github.com/VAST-AI-Research/GeoSAM2) and [StereoWorld](https://github.com/VAST-AI-Research/StereoWorld) at CVPR 2026.

## 🧊 Open models

### 3D generation

| Project | Description | Venue | Links |
|---|---|---|---|
| [**TripoSG**](https://github.com/VAST-AI-Research/TripoSG)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/TripoSG?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | High-fidelity image-to-3D shape generation with large-scale rectified flow transformers | TPAMI | [Paper](https://arxiv.org/abs/2502.06608) · [Model](https://huggingface.co/VAST-AI/TripoSG) · [Demo](https://huggingface.co/spaces/VAST-AI/TripoSG) |
| [**TripoSR**](https://github.com/VAST-AI-Research/TripoSR)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/TripoSR?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Fast feed-forward 3D reconstruction from a single image, built with Stability AI | arXiv 2024 | [Paper](https://arxiv.org/abs/2403.02151) · [Model](https://huggingface.co/stabilityai/TripoSR) · [Demo](https://huggingface.co/spaces/stabilityai/TripoSR) |
| [**TripoSplat**](https://github.com/VAST-AI-Research/TripoSplat)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/TripoSplat?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Single image to 3D Gaussians with learned density control and a controllable splat budget | SIGGRAPH 2026 | [Paper](https://arxiv.org/abs/2605.16355) · [Model](https://huggingface.co/VAST-AI/TripoSplat) · [Demo](https://huggingface.co/spaces/VAST-AI/TripoSplat) · [ComfyUI](https://docs.comfy.org/tutorials/3d/triposplat) |
| [**TripoSF**](https://github.com/VAST-AI-Research/TripoSF)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/TripoSF?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | SparseFlex: high-resolution (up to 1024³), arbitrary-topology 3D shape modeling | ICCV 2025 | [Paper](https://arxiv.org/abs/2503.21732) · [Model](https://huggingface.co/VAST-AI/TripoSF) |
| [**DetailGen3D**](https://github.com/VAST-AI-Research/DetailGen3D)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/DetailGen3D?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Adds fine geometric detail to coarse generated 3D shapes | 3DV 2026 | [Paper](https://arxiv.org/abs/2411.16820) · [Model](https://huggingface.co/VAST-AI/DetailGen3D) · [Demo](https://huggingface.co/spaces/VAST-AI/DetailGen3D) |
| [**TriplaneGaussian**](https://github.com/VAST-AI-Research/TriplaneGaussian)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/TriplaneGaussian?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Hybrid triplane + Gaussian splatting for fast single-view 3D reconstruction | CVPR 2024 | [Paper](https://arxiv.org/abs/2312.09147) · [Model](https://huggingface.co/VAST-AI/TriplaneGaussian) · [Demo](https://huggingface.co/spaces/VAST-AI/TriplaneGaussian) |
| [**Deformable Radial Kernel Splatting**](https://github.com/VAST-AI-Research/Deformable-Radial-Kernel-Splatting)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/Deformable-Radial-Kernel-Splatting?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Generalizes Gaussian splatting with learnable radial kernels for sharper primitives | CVPR 2025 | [Paper](https://arxiv.org/abs/2412.11752) · [Project](https://yihua7.github.io/DRK-web/) |

### Animation-ready assets

| Project | Description | Venue | Links |
|---|---|---|---|
| [**SkinTokens**](https://github.com/VAST-AI-Research/SkinTokens)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/SkinTokens?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | TokenRig: skeleton and skin weights generated as one autoregressive token sequence | ACM TOG 2026 | [Paper](https://arxiv.org/abs/2602.04805) · [Model](https://huggingface.co/VAST-AI/SkinTokens) · [Demo](https://huggingface.co/spaces/VAST-AI/SkinTokens) |
| [**UniRig**](https://github.com/VAST-AI-Research/UniRig)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/UniRig?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | One model to auto-rig diverse 3D characters, creatures and objects | SIGGRAPH 2025 | [Paper](https://arxiv.org/abs/2504.12451) · [Model](https://huggingface.co/VAST-AI/UniRig) · [Project](https://zjp-shadow.github.io/works/UniRig/) |
| [**AniGen**](https://github.com/VAST-AI-Research/AniGen)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/AniGen?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Animate-ready 3D assets (shape + skeleton + skin) from a single image | SIGGRAPH 2026 | [Paper](https://arxiv.org/abs/2604.08746) · [Model](https://huggingface.co/VAST-AI/AniGen) · [Demo](https://huggingface.co/spaces/VAST-AI/AniGen) |

### Parts, scenes & editable 3D

| Project | Description | Venue | Links |
|---|---|---|---|
| [**HoloPart**](https://github.com/VAST-AI-Research/HoloPart)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/HoloPart?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Generative 3D part amodal segmentation: decomposes a shape into complete parts | ICLR 2026 | [Paper](https://arxiv.org/abs/2504.07943) · [Model](https://huggingface.co/VAST-AI/HoloPart) · [Demo](https://huggingface.co/spaces/VAST-AI/HoloPart) |
| [**GeoSAM2**](https://github.com/VAST-AI-Research/GeoSAM2)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/GeoSAM2?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Interactive 3D part segmentation of meshes by lifting SAM2 to 3D | CVPR 2026 | [Paper](https://arxiv.org/abs/2508.14036) · [Model](https://huggingface.co/VAST-AI/GeoSAM2) |
| [**Mira-Scene**](https://github.com/VAST-AI-Research/Mira-Scene)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/Mira-Scene?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Editable 3D scene reconstruction from a single image with pixel-aligned layouts | arXiv 2026 | [Paper](https://arxiv.org/abs/2609.23796) · [Model](https://huggingface.co/Yang-Tian/Mira-Scene) · [Project](https://sunyangtian.github.io/Mira-Scene-web/) |
| [**MIDI-3D**](https://github.com/VAST-AI-Research/MIDI-3D)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/MIDI-3D?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Multi-instance diffusion for single image to compositional 3D scene generation | CVPR 2025 | [Paper](https://arxiv.org/abs/2412.03558) · [Model](https://huggingface.co/VAST-AI/MIDI-3D) · [Demo](https://huggingface.co/spaces/VAST-AI/MIDI-3D) |
| [**LegoACE**](https://github.com/VAST-AI-Research/LegoACE)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/LegoACE?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Autoregressive generation of buildable LEGO® assemblies from text or images | SIGGRAPH Asia 2025 | [Paper](https://doi.org/10.1145/3757377.3763881) · [Model](https://huggingface.co/VAST-AI/LegoACE) |

### Textures & materials (incl. agentic)

| Project | Description | Venue | Links |
|---|---|---|---|
| [**SeqTex**](https://github.com/VAST-AI-Research/SeqTex)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/SeqTex?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | End-to-end mesh UV texture generation using video diffusion priors | SIGGRAPH Asia 2025 | [Paper](https://arxiv.org/abs/2507.04285) · [Model](https://huggingface.co/VAST-AI/SeqTex-Transformer) · [Demo](https://huggingface.co/spaces/VAST-AI/SeqTex) |
| [**ShaderAgent**](https://github.com/VAST-AI-Research/ShaderAgent)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/ShaderAgent?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Agentic generation of editable Blender procedural materials from a photo | SIGGRAPH Asia 2026 | [Paper](https://github.com/VAST-AI-Research/ShaderAgent/releases/latest/download/ShaderAgent.pdf) |

### World models & generative video ([Project Eden](https://vast-eden.ai/))

| Project | Description | Venue | Links |
|---|---|---|---|
| [**EdenLive**](https://github.com/VAST-AI-Research/EdenLive)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/EdenLive?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Real-time generative renderer for interactive worlds, driven by any visual reference | Tech report 2026 | [Paper](https://assets.vast-eden.ai/assets/edenlive/EdenLive-tech-report.pdf) · [Model](https://huggingface.co/VAST-AI/EdenLive) · [Project](https://vast-eden.ai/?p=edenlive) |
| [**StereoWorld**](https://github.com/VAST-AI-Research/StereoWorld)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/StereoWorld?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Camera-guided stereo video generation from a single image | CVPR 2026 | [Paper](https://arxiv.org/abs/2603.17375) · [Model](https://huggingface.co/Yang-Tian/StereoWorld) · [Project](https://sunyangtian.github.io/StereoWorld-web/) |
| [**MultiLive**](https://github.com/VAST-AI-Research/MultiLive)<br><img src="https://img.shields.io/github/stars/VAST-AI-Research/MultiLive?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Synchronized multi-view video generation via on-policy distillation (code coming soon) | 2026 | [Project](https://vast-eden.ai/?p=multilive) |

## 🤖 Tripo for agents & developers

- **[Tripo CLI](https://studio.tripo3d.ai/cli)**: prompt or image to engine-ready 3D from the terminal. `npm install -g tripo-cli`, or paste the one-line setup prompt from [developers.tripo3d.ai](https://developers.tripo3d.ai/) into Claude Code, Codex or Cursor.
- **[Tripo API](https://developers.tripo3d.ai/)**: text, image and multi-view to 3D, texturing, segmentation, retopology, auto-rigging and animation.
- **SDKs**: [Python](https://github.com/Tripo-Developer/tripo-python-sdk) · [JavaScript / TypeScript](https://github.com/Tripo-Developer/tripo-js-sdk)
- **Integrations**: [ComfyUI](https://github.com/Tripo-Developer/ComfyUI-Tripo) · [Blender](https://github.com/Tripo-Developer/tripo-3d-for-blender) · [MCP server](https://github.com/Tripo-Developer/tripo-mcp) · [DeepSeek Harness](https://github.com/Tripo-Developer/Tripo3D-Plugin-dsh) · more in [Tripo-Developer](https://github.com/Tripo-Developer)

## 🌐 Affiliated projects

Open-source work by VAST researchers and academic collaborators, hosted outside this organization.

| Project | What it is |
|---|---|
| [**threestudio**](https://github.com/threestudio-project/threestudio)<br><img src="https://img.shields.io/github/stars/threestudio-project/threestudio?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Unified framework for 3D content generation (text-to-3D, image-to-3D) |
| [**Wonder3D**](https://github.com/xxlong0/Wonder3D)<br><img src="https://img.shields.io/github/stars/xxlong0/Wonder3D?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Single image to 3D via cross-domain diffusion · CVPR 2024 Highlight |
| [**MV-Adapter**](https://github.com/huanngzh/MV-Adapter)<br><img src="https://img.shields.io/github/stars/huanngzh/MV-Adapter?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Multi-view consistent image generation adapter · ICCV 2025 · [ComfyUI nodes](https://github.com/huanngzh/ComfyUI-MVAdapter) |
| [**CharacterGen**](https://github.com/zjp-shadow/CharacterGen)<br><img src="https://img.shields.io/github/stars/zjp-shadow/CharacterGen?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | 3D character generation from a single image · SIGGRAPH 2024 |
| [**SC-GS**](https://github.com/CVMI-Lab/SC-GS)<br><img src="https://img.shields.io/github/stars/CVMI-Lab/SC-GS?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Editable dynamic scenes with sparse-controlled Gaussian splatting · CVPR 2024 |
| [**SAMPart3D**](https://github.com/Pointcept/SAMPart3D)<br><img src="https://img.shields.io/github/stars/Pointcept/SAMPart3D?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Segment any part in 3D objects |
| [**TEXGen**](https://github.com/CVMI-Lab/TEXGen)<br><img src="https://img.shields.io/github/stars/CVMI-Lab/TEXGen?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Generative diffusion model for mesh textures · SIGGRAPH Asia 2024 Best Paper Honorable Mention |
| [**TopoCap**](https://github.com/czpcf/TopoCap)<br><img src="https://img.shields.io/github/stars/czpcf/TopoCap?style=flat&logo=github&label=&labelColor=24292f&color=ffc83d" alt="GitHub stars"> | Video-to-animation for characters with any skeleton topology · SIGGRAPH 2026 |

## 🤝 Community

- **Questions & bugs:** open an issue in the project's repo with your OS, GPU, CUDA/PyTorch versions and the full error log.
- **Contributions:** pull requests for fixes, docs and integrations are welcome.
- **Follow along:** [Discord](https://discord.com/invite/tripoai) · [X @VastAIResearch](https://x.com/VastAIResearch) · [X @tripoai](https://x.com/tripoai) · [Hugging Face](https://huggingface.co/VAST-AI) · [ModelScope](https://modelscope.cn/organization/VAST-AI-Research)
- **Papers:** [all publications](https://www.tripo3d.ai/research/publications); each repo's README has a BibTeX entry.
- **Licenses:** most projects are MIT or Apache-2.0; some have their own terms, so check each repo's LICENSE before commercial use.
- **Join us:** we hire research scientists, engineers and interns globally. See [open roles](https://www.tripo3d.ai/research).
