
# Image Generation Using Stable Diffusion & ComfyUI

This collection dives into Stable Diffusion, a smart AI tool that can create impressive images, along with ComfyUI, a user-friendly interface that gives you more control over how the images are made.




## System Requirements

Before installing, ensure your system meets the following:

✅ GPU: NVIDIA (RTX 2060 or higher recommended) with CUDA support

✅ VRAM: 4GB+ (8GB+ recommended)

✅ OS: Windows 10/11 or Linux (Ubuntu, Arch, etc.)

✅ Python: Version 3.10+

✅ CUDA & cuDNN: Installed for GPU acceleration

✅ Python and Git extensions


## Installation

Clone ComfyUI Repository
```bash
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI

```
Create and Activate Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# On Windows
venv\Scripts\activate

# On Linux/Mac
source venv/bin/activate

```
Install Dependencies
```bash
pip install -r requirements.txt

#If you encounter issues with missing libraries (like torch, numpy, etc.), you can install them manually

```
Download Stable Diffusion Model
```bash
https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors

#You can download other models from:
#Hugging Face
#CivitAI
```
Place the Stable Diffusion model file (.safetensors or .ckpt)
```bash
ComfyUI/
├── models/
│   └── checkpoints/
│       └── model.ckpt  (the downloaded Stable Diffusion .ckpt file or .safetensors file)
```

```bash

```
    
## Run ComfyUI

Once everything is set up, run the following command inside the ComfyUI folder:

```bash
python main.py

```


This will start ComfyUI, and you can access it in your browser at: 

```bash
http://127.0.0.1:5000

```

```bash
Enter a text prompt into the input field.
Press "Generate" to produce the image based on your prompt.

```






## Credits

 - [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
 - [Stable Diffusion Models](https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)
 - [Python](https://www.python.org/)



[
