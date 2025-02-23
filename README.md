# Docker-Compose to run a GPT-Like

🧠 compose-gpt-like is a Docker Compose setup for running [Ollama](https://ollama.com/) with [Open WebUI](https://docs.openwebui.com/), enabling local LLM inference with GPU acceleration. 

## Requirements

### Hardware Requirements

[Ollama](https://ollama.com/) allows you to run large language models efficiently on local hardware. The system requirements depend on the size of the model you intend to use.

#### Minimum Requirements

CPU: Any modern multi-core processor (Intel/AMD, 4+ cores recommended)
RAM: At least 16GB (for small models)
GPU: NVIDIA GPU (RTX 30XX or better recommended)
Storage: SSD with at least 20GB free space for model storage and caching

#### Recommended Requirements by Model Size

##### 1B Models (Small LLMs)
RAM: 8GB minimum, 16GB recommended
GPU (Optional): RTX 3060 (12GB VRAM) or better
VRAM: 4GB minimum, 6GB recommended
Storage: ~5GB per model
✅ Runs well on modern CPUs (Ryzen 5, i5 10th gen or better)
✅ Can run without GPU but slower

##### 4B Models (Medium LLMs)

RAM: 16GB minimum, 32GB recommended
GPU: NVIDIA RTX 3080 / 4070 (10GB+ VRAM) or better
VRAM: 8GB minimum, 12GB recommended
Storage: ~10GB per model
✅ GPU acceleration strongly recommended
⚠️ Without a GPU, inference will be very slow on CPUs

##### 8B Models (Large LLMs)

RAM: 32GB minimum, 64GB recommended
GPU: NVIDIA RTX 3090 / 4080 / A100
VRAM: 16GB minimum, 24GB recommended
Storage: ~20GB per model
✅ Best performance with CUDA-enabled GPUs
⚠️ Running on CPU is not practical due to extreme latency

#### Notes on Performance

More VRAM = Faster inference, as LLMs are memory-intensive
If running multiple instances, increase RAM and VRAM accordingly
Apple M1/M2 chips can run small models efficiently using Metal acceleration
AMD GPUs (ROCm support) are still experimental with Ollama
💡 For serious LLM applications, use a dedicated AI workstation or cloud instances with A100/H100 GPUs 🚀


### Software requirements

- [Docker](https://www.docker.com)
- [Docker Compose](https://docs.docker.com/compose/)

## Credits

Thanks to:

- [Sarah from TikTok](https://www.tiktok.com/@sarah_blog8)

## Team & author(s)

### [17711 team](https://chat.whatsapp.com/BoA3qs7ORHs24MDIzjc2h5)

- [17711's WhatsApp group](https://chat.whatsapp.com/BoA3qs7ORHs24MDIzjc2h5)

### Author(s)

#### [m2€.sh](https://github.com/m2e-sh)

- [m2€.sh's Signal](https://signal.me/#eu/EF-TgxysaGuczGODQO_YKVVwmPS_CE1f_3xT4MwDbmKuvxS0JjlK35IRLrH5ZDIf)
- [m2€.sh's Telegram](https://t.me/m2e_sh)
- [m2€.sh's GitHub](https://github.com/m2e-sh)
- [m2€.sh's TikTok](https://www.tiktok.com/@m2e.sh)
- [m2€.sh's Instagram](https://instagram.com/m.2e.sh)

## Support & donation

- [Monero ($XMR)](monero:86MoMUZRKD5He2ufmTpqpyj455aDpWi5N1vPgD9VMFi7Dr1MPY71mfQEMB4Wo49v6eRM6LVyoBaYqe1MsmSbXSEbKkAPWi1?tx_amount=0.1&tx_description=Donation)

## License

> 
> MIT License
> 
> Copyright (c) 2025 [m2€.sh](https://github.com/m2e-sh) for [17711 Team](#)
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.
> 
