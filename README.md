# Awesome ComfyUI Workflows

<div align="center">

![Workflows](https://img.shields.io/badge/Workflows-1986+-blue?style=for-the-badge)
![Models](https://img.shields.io/badge/Models_Covered-50+-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![ComfyUI](https://img.shields.io/badge/ComfyUI-2025-purple?style=for-the-badge)

**The most comprehensive collection of cutting-edge ComfyUI workflows for video, image, 3D, and audio generation.**

[Explore Workflows](#-workflow-categories) | [Get Started](#-how-to-use) | [Contribute](#-contributing) | [Blog](https://apatero.com/blog)

</div>

---

## What's Inside

This repository contains **1,986+ production-ready workflows** covering the latest AI models:

- **Video Generation** - LTX-2, HunyuanVideo, Wan 2.1/2.2, FramePack, Mochi, CogVideoX, Cosmos
- **Image Generation** - Flux, SD3.5, Lumina 2.0, OmniGen2, SDXL, Illustrious, Pony
- **3D Generation** - Hunyuan3D 2.0/2.1, TRELLIS.2, TripoSG, 3D Gaussian Splatting
- **Audio/Music** - ACE-Step (generate 4 min of music in 20 seconds)
- **Face/Identity** - InstantID, PuLID, FaceID, IP-Adapter
- **And much more...**

---

## Table of Contents

- [Workflow Categories](#-workflow-categories)
  - [Video Generation](#video-generation)
  - [Image Generation](#image-generation)
  - [3D Generation](#3d-generation)
  - [Audio & Music](#audio--music)
  - [Face & Identity](#face--identity)
  - [Utility & Enhancement](#utility--enhancement)
- [Models Covered](#-models-covered)
- [How to Use](#-how-to-use)
- [Contributing](#-contributing)
- [Resources](#-resources)

---

## Workflow Categories

### Video Generation

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**LTX-Video 2**](workflows/ltx-video-2/) | 7 | Lightricks' latest T2V/I2V with LoRA support, distilled models |
| [**HunyuanVideo**](workflows/hunyuan-video/) | 13 | Tencent's 13B video model, I2V, GGUF/FP8 variants |
| [**Wan Video**](workflows/wan-video/) | 55 | Wan 2.1/2.2 T2V, I2V, 14B MoE, Fun Control, GGUF |
| [**FramePack**](workflows/framepack/) | 5 | Stanford's low-VRAM long video (6GB for 60s videos) |
| [**Mochi**](workflows/mochi-video/) | 3 | Genmo's 10B model with fluid 30fps motion |
| [**CogVideoX**](workflows/cogvideox/) | 20 | CogVideoX-5B/1.5, I2V, LoRA training workflows |
| [**Cosmos/Pyramid**](workflows/cosmos-pyramidflow/) | 2 | NVIDIA Cosmos, Pyramid Flow video models |
| [**Video Generation**](workflows/video-generation/) | 80 | SVD, AnimateDiff, general video workflows |
| [**Animation**](workflows/animation/) | 83 | AnimateDiff-Evolved, motion modules, animated content |

### Image Generation

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**Flux Advanced**](workflows/flux-advanced/) | 17 | XLabs ControlNets, Redux, IP-Adapter, All-in-One |
| [**OmniGen/Lumina**](workflows/omnigen-lumina/) | 5 | OmniGen2 editing, Lumina Image 2.0 |
| [**Image Generation**](workflows/image-generation/) | 82 | SDXL, SD3.5, Flux basics, Illustrious, Pony, Kolors |
| [**Inpainting/Outpainting**](workflows/inpainting-outpainting/) | 55 | Flux Fill, Alimama ControlNet, proper compositing |
| [**Style Transfer**](workflows/style-transfer/) | 19 | Artistic style transfer, LoRA-based styling |

### 3D Generation

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**3D Generation**](workflows/3d-generation/) | 73 | Hunyuan3D 2.0/2.1, TRELLIS.2, TripoSG, 3DGS, NeRF |

### Audio & Music

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**ACE-Step Audio**](workflows/audio-ace-step/) | 47 | Music generation (4 min in 20s), 19 languages, LoRA |

### Face & Identity

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**Face ID/Swap**](workflows/face-id-swap/) | 18 | InstantID, PuLID, FaceID, EcomID workflows |
| [**ControlNet/IP-Adapter**](workflows/controlnet-ipadapter/) | 21 | IP-Adapter Plus, FaceID, Kolors, style transfer |

### Utility & Enhancement

| Category | Workflows | Description |
|----------|-----------|-------------|
| [**Upscaling**](workflows/upscaling/) | 36 | ESRGAN, Real-ESRGAN, tiled upscaling, enhancement |
| [**All-in-One Pro**](workflows/all-in-one-pro/) | 130 | KJNodes, d4N87, Black0S professional pipelines |
| [**Official Templates**](workflows/official-templates/) | 287 | Comfy-Org official 2025 workflow templates |
| [**Community Collection**](workflows/community-collection/) | 537 | Best curated workflows from top creators |
| [**Misc**](workflows/misc/) | 391 | Various utility and experimental workflows |

---

## Models Covered

### Video Models
| Model | Type | VRAM | Notes |
|-------|------|------|-------|
| **LTX-Video 2** | T2V/I2V | 12-24GB | Real-time generation, LoRA support |
| **HunyuanVideo** | T2V/I2V | 12-48GB | Tencent's 13B, excellent quality |
| **Wan 2.1/2.2** | T2V/I2V | 8-24GB | Alibaba's MoE, Fun Control |
| **FramePack** | I2V | 6GB+ | 60s videos on RTX 3060 |
| **Mochi 1** | T2V | 24GB | Fluid 30fps, best text consistency |
| **CogVideoX** | T2V/I2V | 12-24GB | Best I2V quality, LoRA training |
| **NVIDIA Cosmos** | T2V/I2V | 12-24GB | World models, 121 frames |
| **Pyramid Flow** | T2V/I2V | 10-12GB | 10s at 768p/24fps |
| **AnimateDiff** | Animation | 8-16GB | Motion modules, infinite length |

### Image Models
| Model | Type | VRAM | Notes |
|-------|------|------|-------|
| **Flux Dev/Schnell** | T2I | 12-24GB | Black Forest Labs, excellent quality |
| **SD3.5 Large** | T2I | 8-16GB | Stability AI latest |
| **Lumina Image 2.0** | T2I | 8-12GB | 2.6B DiT, comparable to Flux |
| **OmniGen2** | T2I/Edit | 12-16GB | 7B multimodal, instruction editing |
| **SDXL** | T2I | 8-12GB | Industry standard |
| **Illustrious/Pony** | T2I | 8-12GB | Anime/stylized specialist |
| **Kolors** | T2I | 8-12GB | Kwai's bilingual model |

### 3D Models
| Model | Type | VRAM | Notes |
|-------|------|------|-------|
| **Hunyuan3D 2.0/2.1** | I2-3D | 6-12GB | Tencent, mini needs only 5GB |
| **TRELLIS.2** | I2-3D | 12-24GB | Microsoft 4B, PBR materials |
| **TripoSG** | I2-3D | 8-16GB | High quality meshes |

### Audio Models
| Model | Type | VRAM | Notes |
|-------|------|------|-------|
| **ACE-Step** | T2-Music | 8-12GB | 4 min in 20s, 19 languages |

### Face/Identity Models
| Model | Type | Notes |
|-------|------|-------|
| **InstantID** | Face swap | SDXL-based, balanced |
| **PuLID** | Face swap | Best quality, more VRAM |
| **FaceID** | Face swap | Fastest, most flexible |
| **IP-Adapter** | Style/Face | Multiple variants available |

---

## How to Use

### Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/Apatero-Org/awesome-comfyui-workflows.git
   ```

2. **Open ComfyUI**

3. **Load a workflow**
   - Drag and drop any `.json` file into ComfyUI
   - Or use `File → Load`

4. **Install required nodes**
   - Use [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager) to auto-install missing nodes
   - Or manually install from the workflow's required nodes list

5. **Download required models**
   - Check the workflow for model requirements
   - Models go in `ComfyUI/models/` subdirectories

### Tips

- **Low VRAM?** Look for GGUF or FP8 variants in workflows
- **First time?** Start with `official-templates/` for well-documented basics
- **Want everything?** Check `all-in-one-pro/` for comprehensive pipelines

---

## Contributing

Contributions are welcome! Here's how you can help:

### Adding Workflows

1. Fork this repository
2. Add your workflow to the appropriate category folder
3. Ensure the workflow is tested and working
4. Submit a pull request with a description

### Guidelines

- **Test your workflows** before submitting
- **Use clear node organization** (left-to-right flow preferred)
- **Include metadata** in the workflow JSON when possible
- **No API keys or personal data** in workflows

### Reporting Issues

Found a broken workflow? [Open an issue](https://github.com/Apatero-Org/awesome-comfyui-workflows/issues) with:
- Workflow name and location
- ComfyUI version
- Error message or description

---

## Resources

### Official Links
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Main ComfyUI repository
- [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager) - Node package manager
- [ComfyUI Examples](https://comfyanonymous.github.io/ComfyUI_examples/) - Official examples

### Learning
- [Apatero Blog](https://apatero.com/blog) - Tutorials and guides
- [ComfyUI Wiki](https://comfyui-wiki.com) - Community documentation
- [r/comfyui](https://reddit.com/r/comfyui) - Reddit community

### Model Sources
- [Hugging Face](https://huggingface.co) - Model downloads
- [CivitAI](https://civitai.com) - Community models and LoRAs
- [OpenArt](https://openart.ai/workflows) - Workflow sharing platform

---

## Credits

This collection includes workflows from amazing creators and repositories:

- [ComfyUI Official Examples](https://github.com/comfyanonymous/ComfyUI_examples)
- [Comfy-Org Workflow Templates](https://github.com/Comfy-Org/workflow_templates)
- [Kijai's Model Wrappers](https://github.com/kijai) - HunyuanVideo, FramePack, CogVideoX, Mochi
- [Lightricks LTX-Video](https://github.com/Lightricks/ComfyUI-LTXVideo)
- [cubiq's IPAdapter & InstantID](https://github.com/cubiq)
- [ComfyUI-3D-Pack](https://github.com/MrForExample/ComfyUI-3D-Pack)
- [ComfyUI Wiki Workflows](https://github.com/comfyui-wiki/workflows)
- And many more community contributors!

---

## License

This collection is released under the **MIT License**. Individual workflows may have their own licenses - please check with original authors for commercial use.

---

<div align="center">

**If you find this useful, please star the repo!**

[![Star History](https://img.shields.io/github/stars/Apatero-Org/awesome-comfyui-workflows?style=social)](https://github.com/Apatero-Org/awesome-comfyui-workflows)

Made with love for the ComfyUI community

</div>
