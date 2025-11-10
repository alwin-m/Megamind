#  Megamind

Megamind is a **lightweight personal AI assistant** powered by **Llama 3 (8B parameters)** and runs completely **offline** using [Ollama](https://ollama.ai).  
It’s designed for developers and AI enthusiasts who want to experience local AI without cloud dependency.

<img width="1200" height="1200" alt="Megamind" src="https://github.com/user-attachments/assets/5a837586-fb14-4be0-a275-844d09e7f3ea" />

---

## ⚙️ System Requirements

To run **Llama 3 (8B)** smoothly, your system should meet the following minimum requirements:

| Component | Minimum Requirement | Recommended |
|------------|--------------------|--------------|
| **CPU** | AMD Ryzen 5 5600 / Intel i5 (6 cores or more) | AMD Ryzen 7 / Intel i7 or above |
| **GPU** | NVIDIA RTX 3050 (6 GB VRAM) | RTX 3060 / 3070 / higher |
| **RAM** | 16 GB | 32 GB+ |
| **Storage** | 10 GB free (for model + cache) | SSD with 20 GB free |
| **Operating System** | Windows 10 / 11 (64-bit) | Windows 11 |
| **Software** | Ollama v0.12.10 or newer | — |
| **Model** | Llama 3 (8B parameters) | — |

> 🧠 *The 8B model runs locally on most modern laptops with a mid-range GPU like the RTX 3050.  
If your system doesn’t have a dedicated GPU, it will still run — just slower.*

---

## 🪄 Setup Guide (Windows)

### 1️⃣ Install Ollama

1. Visit [https://ollama.ai/download](https://ollama.ai/download)  
2. Download **OllamaSetup.exe** for Windows  
3. Run the installer and complete setup  
4. Open **Command Prompt** (`cmd`) and verify your installation:

```bash
ollama --version
