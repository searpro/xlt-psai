# xlt-psai
Provide information about the repo here

workflow types:
txt2img = Text to image
img2img = Image edit

Proposed structure for files. 

files: {
  diffusion_models: {
    "8.3GB": "http://huggingface.com/model-fp16.safetensors",
    "4.5GB": "http://huggingface.com/model-q4.gguf",
    "2.2GB": "http://huggingface.com/model-q2.gguf"
  }
}

Based on the above, we should provide an indication to the user whether
the model he's going to dowload will run on his machine. 
For this, the app should keep track of available RAM, CPU, VRAM, HDD etc. 
