# My Local AI Setup

<div>
<video src='./media/LocalAIDemoAryan.mp4' width=180/>
</div>

### Models to run:

- UI Dashboard: Open WebUI (as docker container) talking to Ollama on the host machine
  - 🐋 Runs via docker container
- Speech-to-Text: openai/whisper 
  - 🐋 Runs via docker container
- Text-to-Speech: hexgrad/Kokoro-82M
  - 🐋 Runs via docker container (you should set it up in open-webui)
- Ollama models: gemma3:4b (multimodal text and vision), qwen2.5-coder (text only, code-specific)
  - Use `install-ollama.ps` and `install-ollama-models.psq`
- Image generation: stabilityai/stable-diffusion-2-1
  - Follow the install guide: [AUTOMATIC1111/stable-diffusion-webui :: Installation on Windows 10/11 with NVidia-GPUs using release package](https://github.com/AUTOMATIC1111/stable-diffusion-webui#installation-on-windows-1011-with-nvidia-gpus-using-release-package)
