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

**[Hugging Face](https://huggingface.co/Aynursusuz)** &nbsp; / &nbsp; **[LinkedIn](https://www.linkedin.com/in/aynur-susuz/)** &nbsp; / &nbsp; **[Email](mailto:aynursusuz@gmail.com)**

## Synthetic speech

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>~4M English clips</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-EN/qwen-clones-4m-en">Qwen3-TTS voice clones ↗</a></strong>
      <p>Conversational speech synthesis.</p>
    </td>
    <td width="50%" valign="top">
      <h3>~3.98M English clips</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-EN/echo-clones-4m-en">EchoTTS voice clones ↗</a></strong>
      <p>4,000 reference speakers.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>3.29M Japanese clips</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-JA/irodori-clones-3m-v2-no-emoji">Irodori TTS v2 ↗</a></strong>
      <p>10,000 reference voices.</p>
    </td>
    <td width="50%" valign="top">
      <h3>~2.97M scored speech clips</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-EN/tts-pretrain-clones-3m-mos">English speech with DNSMOS ↗</a></strong>
      <p>Per-utterance audio-quality estimates.</p>
    </td>
  </tr>
</table>

**Also published:** [Irodori Japanese voice clones — 2.99M clips ↗](https://huggingface.co/datasets/SynDataLab-JA/irodori-clones-3m)

### Text for speech synthesis

| Dataset | Language | Text rows |
| :--- | :--- | ---: |
| **[Mandarin conversational text ↗](https://huggingface.co/datasets/SynDataLab-EN/chinese-tts-text-10m)** | Chinese | ~5.8M |
| **[EchoTTS source text ↗](https://huggingface.co/datasets/SynDataLab-EN-Refs/echo-4m-text-en)** | English | 4M |
| **[DeepSeek Flash Japanese ↗](https://huggingface.co/datasets/SynDataLab-JA-Refs/DeepSeekFlash-3M-ja)** | Japanese | ~2.80M |
| **[DeepSeek Flash English ↗](https://huggingface.co/datasets/SynDataLab-EN-Refs/DeepSeekFlash-3M-en)** | English | ~2.70M |
| **[DeepSeek Pro English ↗](https://huggingface.co/datasets/SynDataLab-EN-Refs/DeepSeekPro-1M-en)** | English | 1M |

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
