# Test_AI
This repository is used in order to test and practice AI.

**Prerequisite**
- Python - over 3.6, but 3.11 not yet
- Pytorch  - Please visit the pytorch site and follow the install guide
- Nvdia Cuda - install proper version according to Cuda
- Python Packages - pytorch-lightning, transformers, labml
- Download 'sd-v1-4.ckpt' (https://huggingface.co/CompVis/stable-diffusion-v-1-4-original) and save to 'data/stable-diffusion'

**Usage**
python test_txt2img --prompt="a painting of a virus monster playing guitar" --batch_size=2
python test_img2img --orig-img="test.png" --batch_size=2
