# Dental-Caries-Detection-CNN

An automated system for detecting tooth decay (caries) from intraoral images using Convolutional Neural Networks (CNN) and TensorFlow.

## Features
- **Deep Learning Model**: CNN architecture optimized for dental image classification (Healthy vs. Caries).
- **Automated Pipeline**: Includes preprocessing and training workflows.
- **Dataset Support**: Structured for training on intraoral image datasets.

## Tech Stack
- **Language**: Python 3.8+
- **Framework**: TensorFlow, Keras
- **Libraries**: OpenCV, Pandas, Matplotlib

## Project Structure
```
├── README.md
├── LICENSE
├── src/                # (Placeholder for future scripts)
├── notebooks/          # Training and EDA notebooks
│   ├── Tooth_Decay_CNN_Training.ipynb
│   └── hackdata.ipynb
├── data/               # teeth_dataset storage
├── models/             # Saved model weights
└── results/            # Performance metrics
```

## Getting Started

### Prerequisites
- Python 3.8+
- TensorFlow, Keras, OpenCV

### Installation
```bash
git clone https://github.com/DinhLucent/Tooth-decay-project.git
cd Tooth-decay-project
# (Add requirements.txt if needed)
```

### Usage
Open `notebooks/Tooth_Decay_CNN_Training.ipynb` in Jupyter or Google Colab to train the model and view results.

## Dataset
The dataset includes labeled images of teeth categorized into:
- **Healthy**
- **Caries (Decay)**

## License
MIT License — see [LICENSE](LICENSE)

---
Built by [DinhLucent](https://github.com/DinhLucent)