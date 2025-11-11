# Megamind 🦙
Megamind is a lightweight personal AI assistant powered by **Llama 3 (8B model)**. It is designed to run **locally** on your computer using [Ollama](https://ollama.ai/).


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

# Installation Guide

Step 1: Install Ollama

Download and install Ollama from the official site:
👉 https://ollama.ai/download

Choose the version for your operating system (Windows, macOS, or Linux).
For Windows users, simply run the downloaded installer and follow the on-screen setup instructions.

---

Step 2: Verify Installation

After installation, open your terminal (or Command Prompt on Windows) and check:

ollama --version


If a version number appears, it means Ollama has been successfully installed and is ready to use.

---

Step 3: Pull the Llama 3 Model

Next, download the Llama 3 (8B) model by running:

ollama pull llama3:8b


This will download the model files and prepare them for local inference.

---

Step 4: Run the Model Locally

Once the model is downloaded, you can start using it directly on your machine:

ollama run llama3:8b


After running this command, Ollama will launch the Llama 3 (8B) model locally.
You can now chat, test prompts, or integrate it with your local applications — all without needing an internet connection.

<img width="1427" height="1061" alt="Screenshot 2025-11-11 014525" src="https://github.com/user-attachments/assets/c3197107-2e65-4797-b0ee-4816a90a7f32" />




