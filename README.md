# 🧠 Prompt-to-Style Image Generator (ComfyUI + SDXL + LoRA)

This project demonstrates a simple and efficient generative AI workflow built using **ComfyUI**, leveraging the **SDXL 1.0 base model** and a **Cyberpunk-style LoRA** to generate stunning stylized images from text prompts.

---

## 🚀 Project Overview

- 🔗 Built a prompt-to-image pipeline using **ComfyUI**
- 🧩 Integrated **SDXL 1.0 checkpoint** with a LoRA for stylistic enhancement
- 📥 Exported the workflow in JSON format for easy reproducibility
- 🖼️ Generated images from prompts in a **local ComfyUI setup (Mac M1)**

---

## 🧰 Tools & Technologies

- 🧠 **ComfyUI** (Visual Workflow Interface for Stable Diffusion)
- 🖼️ **SDXL 1.0** (Stable Diffusion model by StabilityAI)
- 🎨 **LoRA** (Low-Rank Adaptation model for visual style transfer)
- 🖥️ **Mac M1 (local run)**  
- 🐍 Python backend

---

## 💡 Key Features

- Text-to-image generation using **custom prompts**
- LoRA-based **style adaptation** (Cyberpunk theme)
- Clean and modular workflow saved as `.json`
- Output automatically saved to local output directory

---

## 🧩 How to Run This

1. Clone 
2. Place the `comfyui_workflow.json` file in:
ComfyUI/workflows/
3. Launch ComfyUI:
bash:
cd ComfyUI
python3 main.py

	4.	Load the workflow in the browser (http://127.0.0.1:8188)
	5.	Run with your desired text prompt

📸 Sample Output:
Prommt Used: (two prompts used what we want and what we didn't)
Positive Prompt: masterpiece, highly detailed, cinematic lighting, portrait of a cyberpunk horse in neon city
Negative Prompt: blurry, low quality, deformed, distorted


Here is a screenshot of how the workflow looks like:

<img width="1403" alt="Screenshot 2025-05-26 at 2 56 40 AM" src="https://github.com/user-attachments/assets/8ca7cafc-7147-41b4-aca0-84d45c76ef2b" />

Here is the output we got:
![output](https://github.com/user-attachments/assets/a53f4bf4-3a20-4d50-912c-8c960ab1cc01)



Why This Project?

This project showcases practical understanding of:
	•	Prompt engineering
	•	LoRA integration with SDXL
	•	Generative AI workflows using ComfyUI
	•	Local deployment of AI pipelines for fast experimentation




---

### ✅ What’s Next?

Once this file is saved into your GitHub folder:
> Let me know, and I’ll walk you through the **GitHub push** commands line by line.

Let’s make sure you submit with the best impression possible. Ready to push?


Author:
Akshat Sagar
