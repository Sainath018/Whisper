# Whisper
Detecting AI-generated /human speech
# 🧠 AI-Generated Speech Detection using Whisper

This project uses OpenAI's Whisper model to transcribe audio files and classify them as **real** (human) or **fake** (AI-generated). It was built as part of an internship assessment to explore deep learning approaches for audio classification.

---

## 📂 Dataset

- `real1.zip` and `fake1.zip` contain `.wav` audio samples.
- Each class has 100+ samples.
- Audio files are first transcribed using Whisper.
- Download the dataset by below links

---

## ⚙️ Model Workflow

1. **Audio Preprocessing**  
   - Transcription via [Whisper](https://github.com/openai/whisper) (base model).
   - Each audio file is converted to text.

2. **Feature Extraction**  
   - TF-IDF vectorizer extracts text features from transcriptions.

3. **Classification**  
   - A Logistic Regression model classifies the text as `real` or `fake`.

---

## 🧪 Performance

- **Accuracy:** ~60% (on sample dataset)
- **Classification Report:**


---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/whisper-ai-speech-detector.git
cd whisper-ai-speech-detector

---

###Dataset

[fake1.zip](https://github.com/user-attachments/files/19635048/fake1.zip)
[real1.zip](https://github.com/user-attachments/files/19635046/real1.zip)
