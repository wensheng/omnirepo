# Using Flux with WebUI

Download webui-forge from:
https://github.com/lllyasviel/stable-diffusion-webui-forge

Just use cmd.exe, no need to use conda.

**Git Update**

    cd F:\Programs\webui_forge_cu121_torch231\
    .\update.bat

This is the same as:

    cd webui
    git pull

**Run:**

    cd F:\Programs\webui_forge_cu121_torch231\
    .\run.bat

Open localhost:7860

## download models

Get model from: https://huggingface.co/ZhenyaYang/flux_1_dev_hyper_8steps_nf4/tree/main

Put `flux_1_dev_hyper_8steps_nf4.safetensors` in `webui/models/Stable-diffusion`

We can also get models from civit, for example:
https://civitai.com/models/226533?modelVersionId=1031531

## Get example prompts from Civitai

model page: https://civitai.com/models/638187/flux1-dev-hyper-nf4-flux1-dev-bnb-nf4-flux1-schnell-bnb-nf4

## Generate

Make sure to save everytime we generate.

The images are generated in webui/outputs/txt2img-images/

The saved images and log file are in webui/log/images/

