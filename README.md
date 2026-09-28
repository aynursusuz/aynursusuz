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

I'm an **AI Engineer at Vyvo Labs** with **one year of hands-on experience in text-to-speech**. I build speech synthesis tools, adapt models to new languages, and develop the data and evaluation pipelines around them.

**[Hugging Face](https://huggingface.co/Aynursusuz)** &nbsp; / &nbsp; **[LinkedIn](https://www.linkedin.com/in/aynur-susuz/)** &nbsp; / &nbsp; **[Email](mailto:aynursusuz@gmail.com)**

## Selected work

| Project | Engineering focus |
| :--- | :--- |
| **[UNITTS ↗](https://github.com/aynursusuz/UNITTS)** | One Python interface for open-source TTS engines, voice cloning integrations, and inference benchmarks. |
| **[micrograd ↗](https://github.com/aynursusuz/micrograd)** | A scalar-valued autograd engine and neural network library, built while following Andrej Karpathy's course. |
| **[build-nanogpt ↗](https://github.com/aynursusuz/build-nanogpt)** | GPT language model training from scratch, following Andrej Karpathy's nanoGPT tutorial. |

**More speech AI work:** [Audio Quality Pipeline](https://github.com/aynursusuz/audio-quality-pipeline) for speech dataset filtering and evaluation, and [TTS Dataset Pipeline](https://github.com/aynursusuz/tts-text-pipeline) for text generation, voice design, speech synthesis, and publishing.

## Synthetic speech & datasets

I build and publish multilingual synthetic speech datasets, covering voice design, voice cloning, conversational text generation, and automated audio-quality scoring.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>~4M English speech clips</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-EN/qwen-clones-4m-en">Qwen3-TTS voice clones ↗</a></strong>
      <p>Conversational English speech synthesized with Qwen3-TTS-12Hz-1.7B-Base.</p>
    </td>
    <td width="50%" valign="top">
      <h3>3.29M Japanese utterances</h3>
      <strong><a href="https://huggingface.co/datasets/SynDataLab-JA/irodori-clones-3m-v2-no-emoji">Irodori TTS voice clones ↗</a></strong>
      <p>Conversational Japanese speech across 10,000 reference voices, with emoji-cleaned transcripts.</p>
    </td>
  </tr>
</table>

| Dataset | Scale | Focus |
| :--- | :--- | :--- |
| **[EchoTTS English clones ↗](https://huggingface.co/datasets/SynDataLab-EN/echo-clones-4m-en)** | ~3.98M audio clips | English speech synthesis using 4,000 reference speakers. |
| **[Speech with DNSMOS scores ↗](https://huggingface.co/datasets/SynDataLab-EN/tts-pretrain-clones-3m-mos)** | ~2.97M audio clips | Synthetic English speech with per-utterance quality estimates. |
| **[Mandarin conversational text ↗](https://huggingface.co/datasets/SynDataLab-EN/chinese-tts-text-10m)** | ~5.8M text rows | Emotion labels and style prompts for expressive TTS. |
| **[Japanese–English code-switching ↗](https://huggingface.co/datasets/Aynursusuz/jaen-codeswitch-tts)** | 10K audio clips | Mixed-language conversational speech with a single cloned voice. |

<sub>Dataset sizes reflect published rows as of September 2026.</sub>

## Models & evaluation

- **[Italian Qwen3-TTS ↗](https://huggingface.co/Aynursusuz/Qwen-TTS-Best-Model)** — Fine-tuned Qwen3-TTS-12Hz-1.7B-Base on **115K Italian audio samples**; includes training configuration and an inference example.
- **[Multilingual voice-cloning benchmark ↗](https://huggingface.co/datasets/Aynursusuz/tts-multiling-clone-6model)** — Comparison of **6 TTS models** across English, Japanese, and Chinese, with DNSMOS and speaker-similarity scores.

**[Try Audio Quality Assessment ↗](https://huggingface.co/spaces/Aynursusuz/Audio-Quality-Assessment)** — An interactive demo for inspecting loudness, clipping, silence, waveforms, and spectrograms.

## Hugging Face organizations

- **Synthetic speech:** [SynDataLab-EN](https://huggingface.co/SynDataLab-EN) · [SynDataLab-JA](https://huggingface.co/SynDataLab-JA)
- **Reference voices & text:** [SynDataLab-EN-Refs](https://huggingface.co/SynDataLab-EN-Refs) · [SynDataLab-JA-Refs](https://huggingface.co/SynDataLab-JA-Refs)
- **Audio datasets:** [AIGenLab](https://huggingface.co/AIGenLab) · [yt-data-1](https://huggingface.co/yt-data-1)
- **Team research:** [Vyvo](https://huggingface.co/Vyvo) · [Vyvo-Research](https://huggingface.co/Vyvo-Research)

## Tools

`Python` · `PyTorch` · `Transformers` · `Hugging Face Datasets` · `CUDA` · `Gradio` · `librosa`
