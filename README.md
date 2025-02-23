# Docker-Compose to run a GPT-Like

🧠 **compose-gpt-like** is a Docker Compose setup for running [Ollama](https://ollama.com/) with [Open WebUI](https://docs.openwebui.com/), enabling local LLM inference with GPU acceleration.

## 📖 Table of Contents

- 📝 [Synopsis](#synopsis)
- 💖 [Support our *17711* team! Support & Donation](#support-donation)
- ⚙️ [Requirements](#requirements)
  - 🖥️ [Hardware Requirements](#hardware-requirements)
  - [Software Requirements](#software-requirements)
- 🚀 [Getting Started](#getting-started)
  - [Start the Services](#start-the-services)
  - [Stop the Services](#stop-the-services)
  - [Access Open WebUI](#access-open-webui)
- 🛠 [Issues & Contributions](#issues--contributions)
- 👾 [About *17711*](#team17711)
- 🙏 [Crédits](#credits)
  - 🙏 Acknowledgments](#acknowledgments)
  - 🏆 [Attributions](#attributions)
  - 👥 [Contributors](#contributors)
  - 🎖️ [Special Thanks](#special-thanks)
  - 🤯 [Project Initiator](#project-initiator)
     - 💬 [Contact](#project-initiator-contact)
     - 🌍 [Social Networks](#project-initiator-social-networks)
- 📜 [License](#license)

## 📝 <a name="synopsis" /> Synopsis 

This project provides a Docker Compose stack to deploy an **[Ollama](https://ollama.com/) LLM inference server** with an **[Open WebUI](https://docs.openwebui.com/) frontend**. It enables running **GPT-like models** locally with **GPU acceleration** for enhanced performance. 

The setup is ideal for developers, researchers, and AI enthusiasts who want to test and fine-tune LLMs without relying on cloud-based solutions.

## 💖 <a name="support-donation" /> Support our *17711* team! Sponsoring & Donations

Love what we're building? **Support our work and help us grow!** Your contributions allow us to maintain and enhance this project. Every donation helps in developing more open-source AI, blockchain, and tech projects.

- [**Donate Monero ($XMR)**](monero:86MoMUZRKD5He2ufmTpqpyj455aDpWi5N1vPgD9VMFi7Dr1MPY71mfQEMB4Wo49v6eRM6LVyoBaYqe1MsmSbXSEbKkAPWi1?tx_amount=0.1&tx_description=Donation)

## ⚙️ <a name="requirements" /> Requirements

### <a name="hardware-requirements" /> Hardware Requirements

[Ollama](https://ollama.com/) allows you to run large language models efficiently on local hardware. The system requirements depend on the size of the model you intend to use.

#### **Minimum Requirements**

- **CPU**: Any modern multi-core processor (Intel/AMD, 4+ cores recommended)
- **RAM**: At least **16GB** (for small models)
- **GPU**: NVIDIA GPU (RTX 30XX or better recommended)
- **Storage**: SSD with at least **20GB** free space for model storage and caching

#### **Recommended Requirements by Model Size**

##### **1B Models (Small LLMs)**
- **RAM**: **8GB minimum**, **16GB recommended**  
- **GPU (Optional)**: RTX **3060 (12GB VRAM)** or better  
- **VRAM**: **4GB minimum**, **6GB recommended**  
- **Storage**: ~5GB per model  
✅ Runs well on **modern CPUs** (Ryzen 5, i5 10th gen or better)  
✅ Can run **without GPU** but slower  

##### **4B Models (Medium LLMs)**

- **RAM**: **16GB minimum**, **32GB recommended**  
- **GPU**: NVIDIA **RTX 3080 / 4070 (10GB+ VRAM)** or better  
- **VRAM**: **8GB minimum**, **12GB recommended**  
- **Storage**: ~10GB per model  
✅ **GPU acceleration strongly recommended**  
⚠️ Without a GPU, inference will be **very slow** on CPUs  

##### **8B Models (Large LLMs)**

- **RAM**: **32GB minimum**, **64GB recommended**  
- **GPU**: NVIDIA **RTX 3090 / 4080 / A100**  
- **VRAM**: **16GB minimum**, **24GB recommended**  
- **Storage**: ~20GB per model  
✅ Best performance with **CUDA-enabled GPUs**  
⚠️ Running on CPU is **not practical** due to extreme latency

### <a name="software-requirements" /> Sofware Requirements

## <a name="getting-started" /> 🚀 Getting Started

### <a name="start-the-services" /> Start the Services

```sh
docker-compose up -d
```

### <a name="stop-the-services" /> Stop the Services

```sh
docker-compose down
```

### <a name="access-open-webui" /> Access Open WebUI

Once the containers are running, you can access your local Open WebUI from your favorite browser at: [http://localhost:8080](http://localhost:8080)


## <a name="issues-contributions" />🛠 Issues & Contributions

We welcome issues and contributions! If you encounter a bug or have suggestions, feel free to open an issue on our [GitHub repository](https://github.com/m2e-sh/compose-gpt-like/issues). Contributions are highly encouraged—help us build something great together! 🚀

---

## <a name="team17711" /> 👾 About *17711*

We are **passionate about technology, open source, AI (ML, DL, LLMs, and more), blockchain, cryptocurrencies, and digital freedom**. 

**Join us** in shaping the future of decentralized, AI-powered innovations! 🚀

**[17711's WhatsApp group](https://chat.whatsapp.com/BoA3qs7ORHs24MDIzjc2h5)**

## <a name="credits" /> 🙏 Crédits

### <a name="acknowledgments" /> 🙏 Acknowledgments 

### <a name="attributions" /> 🏆 Attributions 

### <a name="contributors" /> 👥 Contributors

### <a name="special-thanks" /> 🎖️ Special Thanks 

### <a name="project-initiator" /> 🤯 Project Initiator

Initially written by [m2€.sh](https://github.com/m2e-sh).

#### <a name="project-initiator-contact" /> 💬 Contact

🔏 Send directly message to [m2€.sh](https://github.com/m2e-sh) using the next recommended encrypted messaging applications:

- **[m2€.sh's Signal](https://signal.me/#eu/EF-TgxysaGuczGODQO_YKVVwmPS_CE1f_3xT4MwDbmKuvxS0JjlK35IRLrH5ZDIf)**
- **[m2€.sh's Telegram](https://t.me/m2e_sh)**

#### <a name="project-initiator-social-networks" /> 🌍 Social Networks

- [m2€.sh's GitHub](https://github.com/m2e-sh)
- [m2€.sh's TikTok](https://www.tiktok.com/@m2e.sh)
- [m2€.sh's Instagram](https://instagram.com/m.2e.sh)

---

## 📜 License

>
> **MIT License** 
> 
> Copyright (c) 2025 [m2€.sh](https://github.com/m2e-sh) for [17711 Team](#) 🇪🇺
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
> 





