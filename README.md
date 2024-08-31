# This is a POC for HF

In this project I'm testing and doing things with HF

## Useful links

- [GPU-Acceleration Comes to PyTorch on M1 Macs](https://towardsdatascience.com/gpu-acceleration-comes-to-pytorch-on-m1-macs-195c399efcc1)
- [Accelerated PyTorch Training on Mac](https://huggingface.co/docs/accelerate/usage_guides/mps)

## Install required libraries

```bash
conda activate hugging-face-poc
pip install -U torch torchvision torchaudio
pip install transformers datasets
pip install huggingface_hub
pip install accelerate -U
pip install scikit-learn
```

## Login into HF

In my computer I was not able to use notebook_login(). I used: huggingface-cli login, which is OK because I'm running it in my computer.

```bash
huggingface-cli login
```
