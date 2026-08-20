<div align="center">

<img src="https://user-images.githubusercontent.com/25584861/137609321-0e4265a3-d17d-45f4-ba20-c23ce8bceb5c.gif" width="180"/>

# Neurologist

### **`gradient descent, from ring 0.`**

*I work on the whole stack between the PCIe bus and the attention head.*

[![X](https://img.shields.io/badge/@CryptCanvasArt-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/CryptCanvasArt)
[![Location](https://img.shields.io/badge/Los_Angeles-1a1a2e?style=for-the-badge&logo=googlemaps&logoColor=f0a500)](#)
[![Focus](https://img.shields.io/badge/currently-inference_optimization-0d1117?style=for-the-badge&logo=nvidia&logoColor=76b900)](#)

</div>

<br>

```console
$ cat /proc/neurologist
name        : Neurologist
role        : AI/ML engineer · systems programmer · VFX artist
arch        : x86_64 + CUDA + whatever the problem requires
location    : Los Angeles, CA
languages   : Python, C++, Rust, TypeScript, CUDA C
philosophy  : if it's slow, profile it. if it's magic, disassemble it.
uptime      : shipping since the GTX 900 series
```

<br>

## `/proc/self/maps` — where the work lives

```text
ADDRESS RANGE        PERM   REGION
──────────────────────────────────────────────────────────────────────
0x0000_llm_engines   r-x    LLM inference — vLLM, llama.cpp, KV-cache
                            tricks, speculative decoding, quantization
0x0001_diffusion     r-x    SDXL / Flux pipelines, ComfyUI graph
                            surgery, LoRA training, VFX integration
0x0002_agents        rwx    multi-agent orchestration — AutoGen,
                            LangChain, tool-use protocols, evals
0x0003_dma_systems   r--    direct memory access, PCIe, memory-mapped
                            I/O, depth-buffer extraction, kbd/HID
0x0004_edge          r-x    models on hostile hardware — Pi 5, Jetson,
                            anything with a heatsink and a dream
[heap]               rw-    grows toward whatever's interesting
[stack]              rw-    C++ ↔ Python ↔ Rust, in that order
```

<br>

## Selected work

| | |
|---|---|
| **`Hush-Rivals-DMA`** | DMA-based hardware input pipeline — reading and injecting HID state over PCIe, zero software footprint on the target |
| **`dma-depth-buffer`** | GPU depth-buffer extraction via direct memory access — real-time scene reconstruction without touching the render pipeline |
| **`neural-inference-bench`** | Reproducible LLM inference benchmarking — tokens/sec, TTFT, and memory curves across vLLM, llama.cpp, and TensorRT-LLM |
| **`diffusion-pipeline-utils`** | Production utilities for Stable Diffusion / ComfyUI — latent-space tooling, batch schedulers, VRAM-aware pipeline planning |
| **`Licensing`** | Self-hosted license API + client SDK — HWID binding, offline grace periods, tamper detection |

<br>

## Toolchain

<div align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="cpp" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" alt="rust" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="pytorch" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="docker" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="node" width="40" height="40"/>&nbsp;&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>

<br><br>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat-square&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-4B8BBE?style=flat-square)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![ComfyUI](https://img.shields.io/badge/ComfyUI-1a1a2e?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA/PCIe-B71C1C?style=flat-square)

</div>

<br>

## Signal

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=neurologist&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=c9d1d9&line=58a6ff&point=f0a500&area=true" width="880"/>

</div>

<br>

<div align="center">

```text
opinions held strongly, benchmarked weakly-supervised.
the best abstraction is the one you can still read a hexdump through.
```

<sub>**building things that think — and knowing exactly which registers they think in** · LA</sub>

</div>
