# Ship Classification

## Project Overview

This repository contains a Jupyter Notebook (`notebooks/shipclass.ipynb`) that implements ship classification based on acoustic and signal data. The notebook covers:

- Mounting Google Drive for data access
- Data loading and organization
- Preprocessing and feature extraction using `librosa`, `scipy.signal`, and `numpy`
- Model training with TensorFlow Keras, including `StratifiedKFold` cross-validation
- Model evaluation using `scikit-learn` metrics (`classification_report`, `confusion_matrix`)
- Visualizations with `matplotlib`, `seaborn`, and `Plotly`

## Repository Structure

```
ship-classification/
├── notebooks/
│   └── shipclass.ipynb
├── data/
│   └── (raw and processed data files)
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/albuca09/shipclassificationCNN-LSTM/tree/main/ship-classification
   cd ship-classification
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `notebooks/shipclass.ipynb` and run the cells in order.

## Dependencies

The main Python packages required are:

- numpy
- pandas
- scipy
- scikit-learn
- tensorflow
- librosa
- pillow
- tqdm
- plotly
- seaborn
- tabulate

## License

This project is licensed under the MIT License.
