# Audio & Subtitle Localization Toolkit

A robust, Python-based pipeline designed to streamline subtitle processing, AI text-to-speech (TTS) generation, and multi-language media localization workflows.

## 🚀 Features

- **SRT Subtitle Parsing:** Automatically extracts dialogue while handling timestamps and filtering out non-spoken metadata or stage directions.
- **AI Speech Generation:** Integrates with modern neural TTS engines (such as Chatterbox TTS) for high-quality audio synthesis.
- **Automated Workflows:** Batch processes text and audio assets to accelerate media localization and content production.
- **GPU-Ready:** Optimized to run efficiently in cloud environments like Kaggle GPU notebooks.

## 📁 Project Structure

```text
├── src/
│   ├── parser.py         # SRT extraction and text cleaning utilities
│   ├── tts_engine.py     # TTS integration and audio synthesis worker
│   └── pipeline.py       # Main execution script linking parsing to audio output
├── outputs/              # Generated PCM16 WAV and output files
├── requirements.txt      # Project dependencies
└── README.md
# super-duper-rotary-phone
A modular Python toolkit for automated text-to-speech generation, media localization, and subtitle (SRT) processing workflows.
