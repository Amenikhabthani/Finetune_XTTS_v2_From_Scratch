# 🔈 Fine-Tuning XTTS v2 from Scratch on Custom Dataset (LJSpeech Format)

Welcome to this repository! This notebook walks you step-by-step through **fine-tuning Coqui's XTTS v2 model** from scratch on your own custom dataset in **LJSpeech format**.

> 📓 **[Open Notebook on Google Colab](https://colab.research.google.com/drive/1FN0eOCCgqkdvLq3ii4mlnGZx3Z8K-3-M?usp=sharing)**  

---

## 🧠 About XTTS v2

**XTTS v2** is a multilingual and multi-speaker text-to-speech (TTS) model by [Coqui.ai]([https://coqui.ai](https://coqui-tts.readthedocs.io/en/latest/)), which supports voice cloning and zero-shot synthesis across languages.

---

## 📁 Dataset Format

This notebook supports datasets in **LJSpeech format**, which means:

- Audio files in `wavs/` directory (`.wav` format).
- A metadata file `metadata.csv` with format:  <audio_filename>|<transcription>|<normalized_transcription>

The expected dataset structure:
├── dataset_name/
│   ├── wavs/
│   │   ├── sample1.wav
│   │   ├── sample2.wav
│   └── metadata.csv


