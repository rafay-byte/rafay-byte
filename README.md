<div align="center">

<!-- HERO SYSTEM BANNER -->
<img src="assets/hero-system.svg" alt="Abdul Rafay Khalid - AI / ML Engineer" width="100%" />

<p align="center">
  <a href="https://github.com/rafay-byte"><img src="https://img.shields.io/badge/GitHub-rafay--byte-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <a href="https://github.com/rafay-byte?tab=repositories"><img src="https://img.shields.io/badge/Repositories-29_Public_Projects-1f6feb?style=for-the-badge" alt="Repositories"/></a>
  <img src="https://img.shields.io/badge/Specialization-Multi--Agent_%E2%80%A2_LLMs_%E2%80%A2_Vision-8957e5?style=for-the-badge" alt="Specialization"/>
  <img src="https://img.shields.io/badge/Hardware-CUDA_Acceleration-76b900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
</p>

</div>

---

### ⚡ AI Engineering Lifecycle

<div align="center">
  <img src="assets/ai-workflow.svg" alt="AI Engineering Lifecycle" width="100%"/>
</div>

---

## 🛡️ CURRENTLY BUILDING: [AlphaGuard AI](https://github.com/rafay-byte/alphaguard)

> **Autonomous 8-Agent Investment Committee & Options Trading Platform with Deterministic Risk Controls**

<div align="center">
  <img src="assets/alphaguard-architecture.svg" alt="AlphaGuard 8-Agent Architecture" width="100%"/>
</div>

<br/>

| Metric / Dimension | Production Specification |
|:---|:---|
| **Agent Architecture** | **8 Specialized Agents** (Macro Research, Fundamental, Bull & Bear Adversaries, Synthesizer) |
| **Reasoning Engine** | Adversarial Bull vs. Bear debate synthesis to isolate bias and downside tail-risk |
| **Risk Control** | **Deterministic Python Engine (Zero-LLM Authority)** — Strict 2% portfolio limits, Greeks caps, stop-loss |
| **Execution Broker** | **Alpaca API** paper options routing with automated post-mortem learning loop |
| **Tech Stack** | `Python 3.10+` &bull; `Multi-Agent Systems` &bull; `Model Context Protocol (MCP)` &bull; `Alpaca Trading API` &bull; `Flask` |

<div align="center">
  <a href="https://github.com/rafay-byte/alphaguard"><b>Explore AlphaGuard Architecture &amp; Code &rarr;</b></a>
</div>

---

## 🚀 FEATURED SYSTEMS SHOWCASE

### Tier 1 &bull; Flagship Engineering

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🐺 [Fenrir](https://github.com/rafay-byte/fenrir)
**Parameter-Efficient LLM Fine-Tuning Framework**

End-to-end framework fine-tuning open-source LLMs on specialized domain datasets using LoRA adapters, followed by rigorous baseline-vs-adapter comparative benchmarking.

<div align="center">
  <img src="assets/fenrir-pipeline.svg" alt="Fenrir LoRA Pipeline" width="100%"/>
</div>

| Parameter | Verified Specification |
|:---|:---|
| **Base Model** | TinyLlama-1.1B-Chat-v1.0 |
| **Tuning Method** | LoRA + QLoRA (PEFT, $r=8$, $\alpha=16$) |
| **Dataset** | 150+ CLI Q&A Pairs (Git, Bash, Tar, Grep) |
| **Evaluation** | Automated dual benchmark suite (`report.md`) |
| **Hardware** | NVIDIA RTX 3050 6GB (~20 min training) |

<div align="center">
  <a href="https://github.com/rafay-byte/fenrir"><b>View Fenrir Repository &rarr;</b></a>
</div>

</td>
<td width="50%" valign="top">

### 📝 [URDU-OCR](https://github.com/rafay-byte/URDU-OCR)
**Deep Learning OCR for Right-to-Left Urdu Script**

Specialized deep learning OCR engine built to recognize cursive, context-dependent Urdu script characters from raw image inputs with GPU-accelerated training.

<div align="center">
  <img src="assets/urdu_ocr_training.png" alt="URDU-OCR Convergence Plot" width="100%"/>
</div>

| Parameter | Verified Specification |
|:---|:---|
| **Architecture** | Deep Learning OCR with CUDA acceleration |
| **Vocabulary** | Custom character-to-index mapping for Urdu |
| **Dataset** | `final_main_dataset.tsv` (~5MB image-text pairs) |
| **Monitoring** | Automated loss/accuracy curve generator |
| **Tech Stack** | `PyTorch` &bull; `CUDA` &bull; `OpenCV` &bull; `Pandas` |

<div align="center">
  <a href="https://github.com/rafay-byte/URDU-OCR"><b>View URDU-OCR Repository &rarr;</b></a>
</div>

</td>
</tr>
</table>

---

### Tier 2 &bull; Visual AI &amp; Generative Media

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🎬 [Frame2Ghibli](https://github.com/rafay-byte/FRAME2GHIBLI)
**Video-to-Ghibli Style Transfer Pipeline**

Neural video stylization transforming raw video frames into Studio Ghibli aesthetics using **ControlNet Canny** adaptive edge conditioning and the **MeinaMix V11** diffusion checkpoint.

<div align="center">
  <img src="assets/frame2ghibli_comparison.jpg" alt="Frame2Ghibli Comparison" width="100%"/>
</div>

| Parameter | Verified Specification |
|:---|:---|
| **Conditioning** | Adaptive Canny edge thresholding (median-based) |
| **Diffusion** | MeinaMix V11 / Anything-V5 (`Diffusers`) |
| **Post-Process** | CUDA watermark removal &amp; frame stacking (`STACK.py`) |
| **Tech Stack** | `PyTorch` &bull; `Stable Diffusion` &bull; `ControlNet` &bull; `CUDA` |

<div align="center">
  <a href="https://github.com/rafay-byte/FRAME2GHIBLI"><b>View Frame2Ghibli Repository &rarr;</b></a>
</div>

</td>
<td width="50%" valign="top">

### 🎭 [SadTalker / AI Avatar Studio](https://github.com/rafay-byte/SadTalker)
**Audio-Driven Talking Head Animation**

Generative multimodal system synthesizing conversational talking avatars from a single portrait and audio track with 3D head motion coefficients and **GFPGAN face restoration**.

<div align="center">
  <img src="assets/sadtalker_ui.jpg" alt="SadTalker UI" width="100%"/>
</div>

| Parameter | Verified Specification |
|:---|:---|
| **Resolution** | 256&times;256 and 512&times;512 output generation |
| **Enhancement** | GFPGAN facial restoration super-resolution |
| **Interfaces** | Dual web apps: Streamlit (`launcher.py`) &amp; Gradio |
| **Tested Config** | Intel i7-14700KF &bull; RTX 3080 10GB &bull; 16GB DDR5 |

<div align="center">
  <a href="https://github.com/rafay-byte/SadTalker"><b>View SadTalker Repository &rarr;</b></a>
</div>

</td>
</tr>
</table>

---

### Tier 3 &bull; Applied Computer Vision &amp; Robotics

<table width="100%">
<tr>
<td width="100%" valign="top">

### 🌿 [SUGARCANE](https://github.com/rafay-byte/SUGARCANE) — Industrial YOLOv8 Bud Cutter Control Station

Applied agricultural computer vision and hardware automation. Combines a custom-trained **YOLOv8** model (`bud` and `strip` classes) with an industrial desktop control application (**PyQt5**) for automated sugarcane cutting machinery.

<div align="center">
  <img src="assets/sugarcane_sample.jpg" alt="Sugarcane Detection Sample" width="45%"/>
</div>

```
Camera Stream ──▶ YOLOv8 Detection ──▶ Spatial Coordinates ──▶ Pneumatic Cutter Triggers (PyQt5)
```

| Parameter | Verified Specification |
|:---|:---|
| **Model** | Ultralytics YOLOv8 (`yolov8n.pt`) with CUDA acceleration |
| **Detection Targets** | Classes: `0: bud`, `1: strip` (sugarcane node &amp; cutting margins) |
| **Control Software** | PyQt5 Desktop UI (`UI3.py`) with motor speed, rotation, and pneumatic cutter delay |
| **Dataset Pipeline** | Automated train/val/test splitting across varied background illumination |
| **Tech Stack** | `Python` &bull; `Ultralytics YOLOv8` &bull; `PyQt5` &bull; `OpenCV` &bull; `PyTorch CUDA` |

<div align="center">
  <a href="https://github.com/rafay-byte/SUGARCANE"><b>View SUGARCANE Repository &rarr;</b></a>
</div>

</td>
</tr>
</table>

---

## 🧠 AI DOMAINS &amp; SPECIALIZATIONS

<div align="center">
  <img src="assets/ai-domains.svg" alt="Core AI Domains" width="100%"/>
</div>

---

## 🛠️ TECHNOLOGY ECOSYSTEM

<div align="center">
  <img src="assets/tech-ecosystem.svg" alt="Technology Ecosystem" width="100%"/>
</div>

---

## 📈 ENGINEERING TRAJECTORY

<div align="center">
  <img src="assets/ai-timeline.svg" alt="Engineering Timeline" width="100%"/>
</div>

---

## 📊 ENGINEERING ACTIVITY &amp; ANALYTICS

<div align="center">

<table border="0">
<tr>
<td align="center" valign="middle">
  <img src="https://github-readme-stats.vercel.app/api?username=rafay-byte&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=8B949E" alt="GitHub Stats" width="410"/>
</td>
<td align="center" valign="middle">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rafay-byte&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=8B949E" alt="Top Languages" width="370"/>
</td>
</tr>
</table>

</div>

---

<div align="center">

### 🤝 Connect &amp; Collaborate

Open to discussions on **Multi-Agent Systems**, **LLM Fine-Tuning**, and **Applied Computer Vision**.

<a href="https://github.com/rafay-byte"><img src="https://img.shields.io/badge/GitHub-rafay--byte-181717?style=flat-square&logo=github" alt="GitHub"/></a>
&nbsp;
<a href="https://github.com/rafay-byte?tab=repositories"><img src="https://img.shields.io/badge/All_Repositories-29_Projects-1f6feb?style=flat-square" alt="Repositories"/></a>

<br/><br/>
<sub>Designed &amp; Architected by <a href="https://github.com/rafay-byte">Abdul Rafay Khalid</a> &bull; AI / ML Engineer</sub>

</div>
