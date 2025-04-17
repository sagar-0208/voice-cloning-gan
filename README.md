# AI-Generated Voice Cloning Using GANs

This repository contains the Mini Project Report (MPR) notebook for **"AI-Generated Voice Cloning Using GANs"**, focused on developing a system that synthesizes human-like voices using Generative Adversarial Networks (GANs). The project utilizes the Mozilla Common Voice dataset to train and evaluate the generative model on diverse speech samples.

## 🎯 Project Objective

To build an AI system capable of cloning human voices by training a GAN architecture on real-world multilingual voice data. The aim is to replicate the natural tone, pitch, and speaking style of a given speaker through synthesized speech samples.

## 🧠 Key Components

- **Generative Adversarial Network (GAN) Architecture**:
  - Custom generator and discriminator models tailored for raw audio signal generation.
  - Feature extraction techniques applied before feeding audio into GAN.

- **Voice Preprocessing & Feature Engineering**:
  - Audio normalization, silence trimming, and spectrogram generation.
  - Conversion to Mel spectrograms for stable GAN training.

- **Training Loop**:
  - Balanced generator-discriminator training cycle.
  - Loss functions customized for speech signal characteristics.

- **Voice Cloning Evaluation**:
  - Comparison of real vs. synthesized audio using waveform visualization and audio output.
  - Metric evaluation (e.g., Spectral Convergence, Signal-to-Noise Ratio).

## 📦 Dataset

This project uses the [Mozilla Common Voice Dataset](https://commonvoice.mozilla.org/cv/datasets):

- Open-source, multilingual dataset of speech samples.
- Provides thousands of validated clips across multiple speakers, languages, and accents.
- Used for both training and evaluation phases.

## 🗂️ File Structure

```
voice-cloning-gan/
├── AAI MPR.ipynb      # Main project notebook
└── README.md          # Project documentation
```

## ⚙️ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/voice-cloning-gan.git
   cd voice-cloning-gan
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download dataset**:
   - Visit [Common Voice](https://commonvoice.mozilla.org/cv/datasets) and download your preferred language version.
   - Extract and place the audio files inside a `data/` directory (if using externally).

4. **Run the notebook**:
   ```bash
   jupyter notebook "AAI MPR.ipynb"
   ```

## 🧪 Results Preview

- Synthesized voice samples generated after each training epoch.
- Visual comparison between input voice spectrograms and generated outputs.
- Evaluation through waveform plots and perceptual listening.

## 📌 Status

✅ Core GAN architecture implemented  
🚧 Currently testing across multiple speakers and languages  
📊 Future improvements include attention layers and multi-speaker conditioning
