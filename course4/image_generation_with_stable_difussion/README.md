## Dependencies

```bash
micromamba create -n automatic1111 python=3.10 -c conda-forge -y
```

## Setup

First terminal:  
```bash
git clone --branch dev --depth 1 https://github.com/AUTOMATIC1111/stable-diffusion-webui.git
cd stable-diffusion-webui
micromamba activate automatic1111
./webui.sh
```

Another terminal:  
```bash
wget https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/resolve/main/sd_xl_base_1.0.safetensors -O ./stable-diffusion-webui/models/Stable-diffusion/sd_xl_base_1.0.safetensors
```
