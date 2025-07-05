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

## 📄 Citation

If you use this work in your research or find it helpful, please cite our paper:

**IEEE Xplore Link**: [Speech Emotion Recognition: Leveraging LSTM and Change Point Detection for Continuous Emotion Detection](https://ieeexplore.ieee.org/document/11018570)  
Published at the *2025 42nd National Radio Science Conference (NRSC)*

**BibTeX:**
```bibtex
@INPROCEEDINGS{11018570,
  author={Yousef, Sama A. and Ismail, Nada A. and Elshafei, Moustafa},
  booktitle={2025 42nd National Radio Science Conference (NRSC)}, 
  title={Speech Emotion Recognition: Leveraging LSTM and Change Point Detection for Continuous Emotion Detection}, 
  year={2025},
  volume={1},
  number={},
  pages={166-175},
  keywords={Human computer interaction;Deep learning;Emotion recognition;Accuracy;Databases;Speech recognition;Mental health;Motion capture;Long short term memory;Monitoring;Speech Emotion Recognition;Long Short-Term Memory;Change Point Detection;Continuous Emotion Detection},
  doi={10.1109/NRSC65659.2025.11018570}
}

```
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
