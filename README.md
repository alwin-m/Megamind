# Megamind
Megamind is a lightweight personal AI assistant powered by **Llama 3 (8B model)**. It is designed to run **locally** on your computer using [Ollama](https://ollama.ai/).

<img width="1200" height="1200" alt="Megamind" src="https://github.com/user-attachments/assets/5a837586-fb14-4be0-a275-844d09e7f3ea" />

---

## Overview
Megamind runs on **Llama 3 (8 billion parameters)**. This is one of the latest open-weight large language models from Meta. It is optimized for **local inference** through **Ollama**.  
This setup lets you use AI without an internet connection and keeps your data private.

---

## Minimum Hardware Requirements

### For Quantized Versions (Recommended)
This setup is for general users and developers who want reasonable speed and efficiency:

| Component | Minimum Requirement |
|------------|--------------------|
| **GPU (VRAM)** | 6–8 GB (e.g., NVIDIA GTX 1060 6GB or RTX 3060 Ti 8GB) |
| **System RAM** | 16 GB (minimum) |
| **CPU** | Intel Core i5/i7 or AMD Ryzen 5/7 |
| **Storage** | 10–20 GB of free SSD space |

> Tip: Quantized models (e.g., 4-bit or 5-bit) lower VRAM usage with only a slight accuracy drop. They are ideal for laptops and mid-range desktops.

---

### For Full Model (FP16 Precision)
If you want to run the complete, uncompressed FP16 model:

| Component | Minimum Requirement |
|------------|--------------------|
| **GPU (VRAM)** | 16–20 GB (e.g., RTX 4080/4090 or Apple M3 Max) |
| **System RAM** | 32 GB or higher |
| **Storage** | 20–30 GB SSD |

---

### Running on CPU Only
If you don’t have a dedicated GPU, you can still run it completely on CPU:

| Component | Minimum Requirement |
|------------|--------------------|
| **CPU** | Intel Core i7 or AMD Ryzen 7 (8+ cores recommended) |
| **System RAM** | 16 GB (minimum) — 32 GB preferred |
| **Performance** | Slower inference speeds, but fully functional |

> Note: For best performance, using a GPU or Apple Silicon (M1/M2/M3) is strongly recommended.

---

## Operating System Compatibility

| OS | Status | Notes |
|----|---------|-------|
| **Windows 10/11 (64-bit)** | ✅ Supported | Native Ollama app available |
| **macOS (Apple Silicon or Intel)** | ✅ Supported | Runs efficiently on M1/M2/M3 chips |
| **Linux (Ubuntu/Debian/Fedora)** | ✅ Supported | CLI-based installation; same commands apply |

---

## Installation Guide

### Step 1: Install Ollama
Download and install Ollama from the official site:  
👉 [https://ollama.ai/download](https://ollama.ai/download)

Choose the version for your operating system (Windows, macOS, or Linux).

---

### Step 2: Verify Installation
After installation, open your terminal (or Command Prompt on Windows) and check:

```bash
ollama --version
```
