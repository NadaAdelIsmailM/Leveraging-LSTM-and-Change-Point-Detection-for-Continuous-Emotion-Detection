# Speech Emotion Recognition using LSTM and Change Point Detection

Welcome to our Speech Emotion Recognition project! This research combines LSTM networks with change point detection to create a powerful system for recognizing emotions in continuous speech.

## 🎯 What Does This Project Do?

We've built a dual-stage system that:
- Detects emotional transitions using PELT algorithm
- Classifies emotions using LSTM networks
- Processes speech using MFCC features

## 📁 What's Inside

- `Notebooks/`: Implementation and experiments
- `iemocap_full_dataset.csv`: IEMOCAP dataset
- `lstm_80Epoch_Imocap.h5`: Trained LSTM model
- `merged_emotions.csv`: Combined emotions dataset
- `segmentationPredictions.csv`: Model predictions
- `notebook links.docx`: Reference documentation

## 📊 Results

Our model achieved impressive results across different datasets:

### Combined Dataset
- Training: 99.43% accuracy (0.0216 loss)
- Validation: 88.64% accuracy
- Test: 89.74% accuracy

### IEMOCAP Dataset
- Training: 98.01% accuracy (0.0665 loss)
- Validation: 81.37% accuracy
- Test: 92.34% accuracy

## 🔑 Key Features

- Real-time emotion detection in speech
- Accurate emotional transition detection
- Robust LSTM classification
- Support for multiple datasets

## 📜 License

MIT License

Copyright (c) 2024 Nada Adel Ismail

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.