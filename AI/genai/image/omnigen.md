# Omnigen

**setup**:

    conda create -n omnigen-py3.10 python=3.10
    conda activate omnigen-py3.10
    pip install torch==2.3.1 --index-url https://download.pytorch.org/whl/cu121
    git clone https://github.com/VectorSpaceLab/OmniGen.git
    cd OmniGen
    pip install -r requirements.txt
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
    pip uninstall torch

**Run**:

    python .\omnigen_sample.py
