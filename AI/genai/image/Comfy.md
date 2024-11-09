# How to use ComfyUI

Download: https://github.com/comfyanonymous/ComfyUI/releases

Save to F:\Programs and unzip (unrar 'to here').

## Get models

Go to: https://huggingface.co/stabilityai/stable-diffusion-3.5-large-turbo

Download the file `sd3.5_large_turbo.safetensors` and save into:

    F:\Programs\ComfyUI_windows_portable\ComfyUI\models\checkpoints

Go to: `text_encoders` subfolder. 

Download the files:

- clip_l.safetensors
- clip_g.safetensors
- t5xxl_fp16.safetensors

Save to `F:\Programs\ComfyUI_windows_portable\ComfyUI\models\clip`

**Note:**

Text encoder files are these location are the same as 3.5 large-turbo:

- https://huggingface.co/stabilityai/stable-diffusion-3.5-medium/tree/main/text_encoders
- https://huggingface.co/stabilityai/stable-diffusion-3-medium

## Run

In powershell or cmd:

    f:
    cd .\Programs\ComfyUI_windows_portable\
    .\run_nvidia_gpu.bat


