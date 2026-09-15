<div align="center">

<!-- HERO SECTION -->
<a href="https://github.com/rafay-byte">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=34&duration=2500&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=90&lines=ABDUL+RAFAY+KHALID;AI+%2F+ML+ENGINEER;Building+Intelligent+Autonomous+Systems" alt="Abdul Rafay Khalid - AI / ML Engineer" />
</a>

<p align="center">
  <b>Architecting Production AI Systems Across LLMs, Computer Vision &amp; Generative Intelligence</b>
</p>

<p align="center">
  <a href="https://github.com/rafay-byte"><img src="https://img.shields.io/badge/GitHub-rafay--byte-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Focus-Multi--Agent_AI_%E2%80%A2_LLMs_%E2%80%A2_Vision-1f6feb?style=for-the-badge" alt="Focus"/>
  <img src="https://img.shields.io/badge/Compute-CUDA_Accelerated-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/Status-Actively_Building-3fb950?style=for-the-badge" alt="Status"/>
</p>

</div>

---

### ⚡ AI Engineering Lifecycle

<div align="center">
  <img src="assets/ai-workflow.svg" alt="End-to-End AI Engineering Lifecycle" width="100%"/>
</div>

---

## 🔬 Currently Building: Multi-Agent AI

<div align="center">

### 🛡️ [AlphaGuard AI](https://github.com/rafay-byte/alphaguard) — Autonomous 8-Agent Investment Committee

</div>

AlphaGuard is an autonomous multi-agent options trading platform built for the Alpaca AI Trading Agents Hackathon. Instead of naive LLM decision-making, it implements an **8-agent institutional committee** where specialized agents conduct research, perform adversarial bull-vs-bear thesis debates, and propose trades. Crucially, **zero unrestricted trading authority is given to the LLM** — all orders must pass a hardcoded, deterministic Python risk engine before routing to Alpaca.

<div align="center">
  <img src="assets/alphaguard-architecture.svg" alt="AlphaGuard Architecture" width="100%"/>
</div>

<p align="center">
  <code>Python</code> &bull; <code>Multi-Agent Architecture</code> &bull; <code>Model Context Protocol (MCP)</code> &bull; <code>Alpaca Options API</code> &bull; <code>Flask</code> &bull; <code>Deterministic Risk</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/alphaguard"><b>Explore AlphaGuard Repository &rarr;</b></a>
</div>

---

## 🚀 Visual Project Showcase

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🎬 [Frame2Ghibli](https://github.com/rafay-byte/FRAME2GHIBLI)
**Video-to-Ghibli Style Transfer Pipeline**

Converts raw video into Studio Ghibli-style anime frames using **ControlNet Canny** adaptive edge conditioning and the **MeinaMix V11** diffusion checkpoint, with CUDA-accelerated watermark removal and video reassembly.

<div align="center">
  <img src="assets/frame2ghibli_output.jpg" alt="Frame2Ghibli Visual Output" width="100%"/>
</div>

```
Video ──▶ Adaptive Canny ──▶ ControlNet + MeinaMix ──▶ Stylized Video
```

<p align="center">
  <code>PyTorch</code> &bull; <code>Diffusers</code> &bull; <code>ControlNet</code> &bull; <code>CUDA</code> &bull; <code>OpenCV</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/FRAME2GHIBLI"><b>View Frame2Ghibli &rarr;</b></a>
</div>

</td>
<td width="50%" valign="top">

### 🎭 [SadTalker / AI Avatar Studio](https://github.com/rafay-byte/SadTalker)
**Audio-Driven Talking Head Animation**

Multimodal generative AI system synthesizing realistic facial animations from a single portrait and audio track. Features 3D motion coefficients, **GFPGAN face restoration**, and full Streamlit / Gradio web applications.

<div align="center">
  <img src="assets/sadtalker_ui.jpg" alt="SadTalker Streamlit UI" width="100%"/>
</div>

```
Portrait + Audio ──▶ 3D Motion Coeffs ──▶ GFPGAN Restoration ──▶ Video
```

<p align="center">
  <code>PyTorch</code> &bull; <code>GFPGAN</code> &bull; <code>Streamlit</code> &bull; <code>Wav2Vec</code> &bull; <code>Gradio</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/SadTalker"><b>View SadTalker &rarr;</b></a>
</div>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🐺 [Fenrir](https://github.com/rafay-byte/fenrir) — LLM Fine-Tuning & Evaluation Framework

An end-to-end framework for parameter-efficient fine-tuning (PEFT) on open-source LLMs. Fine-tuned **TinyLlama-1.1B** on domain-specific CLI datasets using **LoRA + QLoRA**, followed by structured side-by-side evaluation against baseline responses.

<div align="center">
  <img src="assets/fenrir-pipeline.svg" alt="Fenrir Fine-Tuning Pipeline" width="100%"/>
</div>

<p align="center">
  <code>Python</code> &bull; <code>PyTorch</code> &bull; <code>HuggingFace Transformers</code> &bull; <code>LoRA / QLoRA</code> &bull; <code>PEFT</code> &bull; <code>RTX 3050 CUDA</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/fenrir"><b>View Fenrir &rarr;</b></a>
</div>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📝 [URDU-OCR](https://github.com/rafay-byte/URDU-OCR)
**Deep Learning OCR for Right-to-Left Urdu Script**

A specialized OCR engine tackling Urdu cursive ligature recognition. Includes custom character-to-index mapping, CUDA training loops, and automated convergence tracking.

<div align="center">
  <img src="assets/urdu_ocr_training.png" alt="Urdu OCR Convergence Graph" width="100%"/>
</div>

```
Urdu Image ──▶ Preprocessing ──▶ PyTorch Model ──▶ Urdu Transcription
```

<p align="center">
  <code>PyTorch</code> &bull; <code>CUDA</code> &bull; <code>OpenCV</code> &bull; <code>Pandas</code> &bull; <code>TSV Dataset</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/URDU-OCR"><b>View URDU-OCR &rarr;</b></a>
</div>

</td>
<td width="50%" valign="top">

### 🌿 [SUGARCANE](https://github.com/rafay-byte/SUGARCANE)
**YOLOv8 Industrial Bud Cutter Vision System**

Precision computer vision pipeline for automated sugarcane bud cutting machinery. Combines a custom-trained **YOLOv8** model (`bud` &amp; `strip` detection) with a **PyQt5** industrial machine control station with motor and cutter timing triggers.

<div align="center">
  <img src="assets/sugarcane_sample.jpg" alt="Sugarcane Detection Sample" width="100%"/>
</div>

```
Camera Feed ──▶ YOLOv8 Detection ──▶ Spatial Coordinates ──▶ PyQt5 Control
```

<p align="center">
  <code>Ultralytics YOLOv8</code> &bull; <code>PyQt5</code> &bull; <code>OpenCV</code> &bull; <code>CUDA</code> &bull; <code>Scikit-learn</code>
</p>

<div align="center">
  <a href="https://github.com/rafay-byte/SUGARCANE"><b>View SUGARCANE &rarr;</b></a>
</div>

</td>
</tr>
</table>

---

## 🧠 AI Domains & Core Specializations

<div align="center">
  <img src="assets/ai-domains.svg" alt="Core AI Domains" width="100%"/>
</div>

---

## 🛠️ Technology Ecosystem

<div align="center">
  <img src="assets/tech-ecosystem.svg" alt="Technology Ecosystem" width="100%"/>
</div>

---

## 📈 Engineering Journey & Progression

<div align="center">
  <img src="assets/ai-timeline.svg" alt="AI Engineering Journey" width="100%"/>
</div>

---

## 📊 GitHub Analytics & Code Activity

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

### 💬 Connect &amp; Collaborate

Interested in collaborating on AI research, multi-agent architectures, or computer vision systems?

<a href="https://github.com/rafay-byte"><img src="https://img.shields.io/badge/GitHub-rafay--byte-181717?style=flat-square&logo=github" alt="GitHub"/></a>
&nbsp;
<a href="https://github.com/rafay-byte?tab=repositories"><img src="https://img.shields.io/badge/All_Repositories-29_Projects-1f6feb?style=flat-square" alt="Repositories"/></a>

<br/><br/>
<sub>Designed &amp; Built with precision by <a href="https://github.com/rafay-byte">Abdul Rafay Khalid</a></sub>

</div>
