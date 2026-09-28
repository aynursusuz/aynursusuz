<picture>
  <source media="(max-width: 600px)" srcset="./assets/header-mobile.svg">
  <img src="./assets/header.svg" width="100%" alt="Aynur Susuz — AI Engineer, Speech AI & Text-to-Speech. Building the systems behind the voice.">
</picture>

<p>
  <img src="./assets/multilingual-tts.svg" height="30" alt="Multilingual TTS">
  <img src="./assets/voice-cloning.svg" height="30" alt="Voice Cloning & Design">
  <img src="./assets/fine-tuning.svg" height="30" alt="Model Fine-Tuning">
  <img src="./assets/evaluation.svg" height="30" alt="Speech Evaluation">
</p>

**AI Engineer at Vyvo Labs** · One year building text-to-speech systems.

**[Hugging Face](https://huggingface.co/Aynursusuz)** &nbsp; / &nbsp; **[LinkedIn](https://www.linkedin.com/in/aynur-susuz/)** &nbsp; / &nbsp; **[Email](mailto:aynur.susuz.5561@gmail.com)**

## Synthetic speech

<div align="center">
<a href="https://huggingface.co/datasets/SynDataLab-EN/qwen-clones-4m-en"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/dataset-qwen-dark.svg?v=2"><img src="./assets/dataset-qwen-light.svg?v=2" width="346" align="top" alt="~4M English speech clips — Qwen3-TTS voice clones. Conversational speech synthesis."></picture></a><a href="https://huggingface.co/datasets/SynDataLab-EN/echo-clones-4m-en"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/dataset-echo-dark.svg?v=2"><img src="./assets/dataset-echo-light.svg?v=2" width="346" align="top" alt="~3.98M English speech clips — EchoTTS voice clones. 4,000 reference speakers."></picture></a><br><a href="https://huggingface.co/datasets/SynDataLab-JA/irodori-clones-3m-v2-no-emoji"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/dataset-irodori-dark.svg?v=2"><img src="./assets/dataset-irodori-light.svg?v=2" width="346" align="top" alt="3.29M Japanese speech clips — Irodori TTS v2. 10,000 reference voices."></picture></a><a href="https://huggingface.co/datasets/SynDataLab-EN/tts-pretrain-clones-3m-mos"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/dataset-dnsmos-dark.svg?v=2"><img src="./assets/dataset-dnsmos-light.svg?v=2" width="346" align="top" alt="~2.97M English speech clips with DNSMOS per-utterance quality estimates."></picture></a>
</div>

**Also published:** [Irodori Japanese voice clones — 2.99M clips ↗](https://huggingface.co/datasets/SynDataLab-JA/irodori-clones-3m)

### Text for speech synthesis

| Dataset | Language | Text rows |
| :--- | :---: | ---: |
| **[Mandarin conversations](https://huggingface.co/datasets/SynDataLab-EN/chinese-tts-text-10m)** | <img src="./assets/language-zh.svg" width="86" height="26" align="center" alt="Chinese"> | **~5.8M** |
| **[EchoTTS source text](https://huggingface.co/datasets/SynDataLab-EN-Refs/echo-4m-text-en)** | <img src="./assets/language-en.svg" width="86" height="26" align="center" alt="English"> | **4M** |
| **[DeepSeek Flash](https://huggingface.co/datasets/SynDataLab-JA-Refs/DeepSeekFlash-3M-ja)** | <img src="./assets/language-ja.svg" width="86" height="26" align="center" alt="Japanese"> | **~2.80M** |
| **[DeepSeek Flash](https://huggingface.co/datasets/SynDataLab-EN-Refs/DeepSeekFlash-3M-en)** | <img src="./assets/language-en.svg" width="86" height="26" align="center" alt="English"> | **~2.70M** |
| **[DeepSeek Pro](https://huggingface.co/datasets/SynDataLab-EN-Refs/DeepSeekPro-1M-en)** | <img src="./assets/language-en.svg" width="86" height="26" align="center" alt="English"> | **1M** |

<sub>Sizes from dataset cards and Hub metadata · September 2026</sub>

## Models & evaluation

- **[Italian Qwen3-TTS ↗](https://huggingface.co/Aynursusuz/Qwen-TTS-Best-Model)** — Fine-tuned on 115K audio samples.
- **[Voice-cloning benchmark ↗](https://huggingface.co/datasets/Aynursusuz/tts-multiling-clone-6model)** — 6 models · 3 languages.
- **[Audio Quality Assessment ↗](https://huggingface.co/spaces/Aynursusuz/Audio-Quality-Assessment)** — Live demo.

<details>
<summary>Hugging Face organizations</summary>

- **Synthetic speech:** [SynDataLab-EN](https://huggingface.co/SynDataLab-EN) · [SynDataLab-JA](https://huggingface.co/SynDataLab-JA)
- **Reference voices & text:** [SynDataLab-EN-Refs](https://huggingface.co/SynDataLab-EN-Refs) · [SynDataLab-JA-Refs](https://huggingface.co/SynDataLab-JA-Refs)
- **Audio datasets:** [AIGenLab](https://huggingface.co/AIGenLab) · [yt-data-1](https://huggingface.co/yt-data-1)
- **Team research:** [Vyvo](https://huggingface.co/Vyvo) · [Vyvo-Research](https://huggingface.co/Vyvo-Research)

</details>

`Python` · `PyTorch` · `Transformers` · `CUDA`
