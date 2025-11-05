# ComfyUI Workflows Collection - Complete Catalog

This repository contains **415+ ComfyUI workflows** from the most popular and active community sources!

## 📊 Overview

All workflows are organized into the following categories:

- **Image Generation** (70 workflows) - Text-to-image, img2img, SDXL, Flux, Stable Cascade
- **Video Generation** (55 workflows) - WAN 2.1/2.2, Stable Video Diffusion, LTX Video
- **Animation** (79 workflows) - AnimateDiff, prompt travel, video-to-video animation
- **Upscaling** (33 workflows) - Image enhancement, super resolution, detail refinement
- **Style Transfer** (19 workflows) - ControlNet, IPAdapter, artistic styles, composition
- **Misc** (159 workflows) - 3D generation, audio, inpainting, face workflows, LLM integration, utilities

**Total: 415 workflows** ready to use!

---

## 🎨 Image Generation (70 workflows)

### Location: `workflows/image-generation/`

#### Latest Models (2025):
- `wan2_2_T2I.json` - WAN 2.2 text-to-image (August 2025)
- `SDXL-ULTIMATE-WORKFLOW-v3_2.json` - Complete SDXL workflow with LoRAs, ControlNets, upscaling
- `native-hidream-i1-dev-fp8.json` - HiDream I1 FP8 model
- `gguf-hidream-i1.json` - HiDream I1 GGUF format

#### Flux Workflows:
- `flux_kontext_Ultimate.json` - Flux Kontext Ultimate workflow
- `flux_lora.json` - Flux with LoRA support
- `flux_lora_autoprompt.json` - Flux with LLM auto-prompting
- `flux_character_sheet.json` - Character sheet generator

#### SDXL & Speed Models:
- `comfyui_sdxl_lightning_workflow_full_1step.json` - SDXL Lightning 1-step
- `sdxl-lightning-ipadapter-plus-umezf.json` - SDXL Lightning + IPAdapter
- `comfyui_Hyper-SD15-1step-unified-lora-workflow.json` - Hyper-SD 1-step

#### Stable Cascade:
- `stable-cascade-txt2img.json` - Text-to-image
- `Stable-Cascade-image-to-image.json` - Image-to-image
- `Stable-Cascade-Image-Prompt.json` - Image prompting

#### Educational Workflows (cubiq):
- `SDXL_base_only.json` - Basic SDXL generation
- `clip_skip.json` - CLIP skip examples
- `word_weighting.json` - Prompt weighting techniques
- `embeddings.json` - Textual embeddings
- `gligen_box.json` - GLIGEN positioning
- `conditioning_area.json` - Area conditioning
- `conditioning_concat.json` - Concatenate conditioning
- `conditioning_average.json` - Average conditioning
- `timestepping.json` - Timestep control

#### Other Workflows:
- `txt2img.json` - Basic text-to-image
- `img2img_stablecascade.json` - Stable Cascade img2img
- `imgprompt_stablecascade.json` - Image prompt workflow
- `imagemerge_unclip.json` - Image merging with UNCLIP
- `ollama-txt2img-workflow.json` - Ollama LLM integration
- `updated_artistic_images_workflow.json` - Artistic generation
- `updated_artistic_backgrounds_workflow.json` - Background generation

#### Experiments:
- See `workflows/image-generation/experiments/` for advanced experimental workflows

---

## 🎬 Video Generation (55 workflows)

### Location: `workflows/video-generation/`

#### Latest 2025 Workflows:
- `wan22_lx2v_gguf.json` - WAN 2.2 + LightX2V (August 2025)
- `video_interpolate.json` - Frame interpolation GIMM-VFI (August 2025)
- `video_upscale.json` - Video upscaling (August 2025)

#### WAN 2.1 Workflows:
- `wan2.1_t2v.json` - Text-to-video
- `wan2.1_i2v_720P.json` - Image-to-video 720P
- `wan2.1_i2v_480P.json` - Image-to-video 480P
- `wan2.1_T2V.json` - T2V (city96 implementation)
- `wan2.1_I2V_gguf_720P.json` - I2V GGUF 720P
- `wan2.1_I2V_gguf_480P.json` - I2V GGUF 480P
- `wan2.1_I2V_720P.json` - I2V (kijai implementation)
- `wan2.1_T2V_2.json` - T2V variant 2

#### WAN Fun Control:
- `wan2.1_fun_control.json` - Native fun control
- `wan2.1_fun_control_with_custom_nodes.json` - With custom nodes
- `Wan_fun_control_i2v.json` - Image-to-video with control
- `Wan_fun_control_t2v.json` - Text-to-video with control

#### Other Video Models:
- `ltxvideo-i2v.json` - LTX Video image-to-video
- `SDV - img2vid.json` - Stable Video Diffusion
- `workflow-text-to-video-svd-*.json` - SVD text-to-video
- `workflow_txt_to_img_to_video.json` - Complete T2I2V pipeline
- Various other SVD and video generation workflows

---

## 🎭 Animation (79 workflows)

### Location: `workflows/animation/`

#### AnimateDiff Collection:
- `AnimateDiff Prompt Travel ControlNets and Video to Video.json` - Advanced prompt travel
- `AnimateDiff cn-2images.json` - ControlNet 2-image animation
- `AnimateDiff_Vid2Vid.json` - Video-to-video animation
- `animateDiff_OldShip.json` - Example animation
- `animatelcm_advanced.json` - AnimateLCM advanced
- `animatelcm-hfr-video-to-video-ikqxg.json` - High frame rate V2V

#### Specialized Animation:
- `workflow-animatediff-controlnet-lcm-flicker-free-*.json` - Flicker-free animation
- `workflow-animatediff-with-ipadator-control-*.json` - IPAdapter control
- `workflow-longanimatediff-*.json` - Long animations
- `workflow-rave-animatediff-animation-*.json` - Character consistency
- `animatediff_lightning_v2v_openpose_workflow.json` - Lightning V2V with OpenPose
- `stitch-2loopmotion-stablevideo.json` - Loop motion stitching

---

## ⬆️ Upscaling (33 workflows)

### Location: `workflows/upscaling/`

#### From cubiq (Educational):
- Various upscaling techniques and models
- Latent upscaling methods
- Ultimate SD Upscale workflows

#### From Community:
- `Photo Upscaling.json` - Photo enhancement
- `workflow-ez-upscale-anything-fast-*.json` - Fast upscaling (no prompt needed)
- `SD15-ControlNet-UltimateSDUpscaler.json` - Ultimate SD upscaler with ControlNet

#### Experiments:
- See `workflows/upscaling/experiments/` for experimental upscaling techniques

---

## 🎨 Style Transfer (19 workflows)

### Location: `workflows/style-transfer/`

#### Image Conditioning (cubiq):
- ControlNet workflows
- IPAdapter workflows
- T2I-Adapter workflows
- Pose and composition control

#### From Community:
- `resadapter_ipadapter_workflow.json` - ResAdapter + IPAdapter
- Various style transfer and artistic style workflows
- Background and character styling

---

## 🔧 Misc (159 workflows)

### Location: `workflows/misc/`

This category includes specialized workflows that don't fit into other categories:

#### 3D Generation:
- `single_view.json` - Hunyuan3D 2.0 single view
- `mutiview.json` - Hunyuan3D 2.0 multi-view
- `triposr-starter-rkxvq.json` - TripoSR 3D generation
- `workflow_rembg_crm_cuda.json` - Background removal + 3D
- `200524_Mickmumpitz_3D-RENDERING_*.json` - 3D rendering

#### Audio & TTS:
- `F5TTS.json` - F5 text-to-speech
- `latentsync.json` - Latent audio sync
- `ace-step-v1-t2a.json` - Text-to-audio
- `ace-step-v1-a2a.json` - Audio-to-audio
- `ace-step-v1-lora.json` - ACE-Step with LoRA
- `Watermark.json` - Audio watermarking

#### Inpainting/Outpainting:
- `inpaint.json` - Basic inpainting
- `outpaint.json` - Basic outpainting
- `SDXL_inpaint_SD15.json` - SDXL inpaint with SD1.5
- `Inpainting Advanced.json` - Advanced inpainting
- `inpainting.json` - Basic inpainting workflow

#### Face Workflows:
- `facedetailer.json` - Face detail enhancement
- `workflow-instantid-faceswap-*.json` - InstantID face swap
- `ip-adapter-faceid-sdxl.json` - FaceID IPAdapter

#### ControlNet & IPAdapter:
- `ipadapter.json` - IPAdapter workflow
- Multiple IPAdapter variations
- Various ControlNet implementations

#### LLM Integration:
- `llava_batch_questionphoto.json` - Batch photo questioning
- `llava_file_namer.json` - AI file naming

#### Real-time & Live:
- `Live LCM Olivio.json` - Live LCM generation
- `luciano_santa_br_gida__lucianosb__lcm_sd_1_5_webcam_*.json` - Webcam LCM
- `workflow-lcm-sampling-real-time-capture-*.json` - Real-time window capture
- Various LCM workflows

#### Utilities:
- `promptsfromfile.json` - Load prompts from file
- `instructpix2pix.json` - InstructPix2Pix editing
- `workflow-lesson-7-live-model-merge-*.json` - Live model merging
- `human_workflow_with_params_v2.json` - Parameterized workflows
- `LBM_Relighting_*.json` - Image relighting

#### Experiments:
- See `workflows/misc/experiments/` for experimental workflows

---

## 📚 Sources

All workflows are sourced from the most popular and active ComfyUI repositories:

1. **cubiq/ComfyUI_Workflows** - Educational, well-documented workflows
2. **pwillia7/Basic_ComfyUI_Workflows** - Active 2025 with latest models (WAN 2.2, Flux)
3. **BeTheRobotSD/sdxl-comfyui-ultimate-workflow** - Complete SDXL workflow
4. **aimpowerment/comfyui-workflows** - Large community collection (423 workflows)
5. **comfyui-wiki/workflows** - Official ComfyUI Wiki workflows
6. **comfyanonymous/ComfyUI_examples** - Official ComfyUI examples

All workflows are free to use under their respective licenses.

---

## 🚀 How to Use

1. **Load a workflow:**
   - Download any `.json` file
   - Open ComfyUI
   - Drag and drop the workflow file into ComfyUI
   - Or use File → Load and select the workflow

2. **Install required nodes:**
   - ComfyUI will prompt you for any missing custom nodes
   - Use ComfyUI Manager to install missing nodes automatically
   - See individual workflow documentation for specific requirements

3. **Get required models:**
   - Check the workflow for model requirements
   - Download models from HuggingFace, CivitAI, or other sources
   - Place models in the appropriate ComfyUI directories

---

## ⭐ Recommended Workflows to Start

### Beginners:
1. `workflows/image-generation/txt2img.json` - Basic text-to-image
2. `workflows/image-generation/SDXL_base_only.json` - Simple SDXL workflow
3. `workflows/upscaling/Photo Upscaling.json` - Basic upscaling

### Intermediate:
1. `workflows/image-generation/SDXL-ULTIMATE-WORKFLOW-v3_2.json` - Complete SDXL workflow
2. `workflows/video-generation/wan2.1_t2v.json` - Video generation
3. `workflows/animation/AnimateDiff_Vid2Vid.json` - Video animation

### Advanced:
1. `workflows/video-generation/wan22_lx2v_gguf.json` - Latest video generation (2025)
2. `workflows/image-generation/flux_kontext_Ultimate.json` - Advanced Flux workflow
3. `workflows/misc/single_view.json` - 3D generation

---

## 🎯 Categories at a Glance

```
workflows/
├── image-generation/     # 70 workflows - T2I, SDXL, Flux, Stable Cascade
│   └── experiments/      # Advanced experimental image workflows
├── video-generation/     # 55 workflows - WAN 2.1/2.2, SVD, video models
├── animation/           # 79 workflows - AnimateDiff, V2V, animations
├── upscaling/           # 33 workflows - Image enhancement & upscaling
│   └── experiments/      # Experimental upscaling techniques
├── style-transfer/      # 19 workflows - ControlNet, IPAdapter, styling
└── misc/                # 159 workflows - 3D, audio, inpainting, utilities
    └── experiments/      # Experimental misc workflows
```

---

## 📖 Documentation

For detailed tutorials and guides on using these workflows, check out:
- [apatero.com/blog](https://apatero.com/blog) - In-depth tutorials and tips
- Individual workflow README files (where available)
- ComfyUI documentation at [ComfyUI Wiki](https://comfyui-wiki.com)

---

## 🆘 Need Help?

- Email: contact@apatero.com
- Check workflow-specific documentation in source repositories
- Visit ComfyUI community forums and Discord

---

## 🙏 Credits

Huge thanks to the ComfyUI community and these amazing creators:
- cubiq - Educational workflows
- pwillia7 - Latest 2025 workflows
- BeTheRobot - Ultimate SDXL workflow
- aimpowerment - Community collection
- ComfyUI Wiki team - Official workflows
- comfyanonymous - Official examples

---

## 📄 License

These workflows are free to use. Please check individual workflow sources for specific license information.

**Don't forget to star this repo if you find it useful!** ⭐
