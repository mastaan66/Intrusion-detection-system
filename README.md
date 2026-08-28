# Intrusion-detection-system

An intrusion detection prototype that classifies network connections as good or bad using the KDD Cup 1999 dataset.

The project tests feature extraction and selection, then compares seven classifiers on accuracy and runtime. Decision Tree gave the best balance in the reported run.

## Why this exists

Intrusion detection requires quick, accurate classification. This repo reproduces a baseline comparison on a classic dataset so the pipeline can be extended to modern data.

## Dataset

KDD Cup 1999 by DARPA. The notebook loads the data, handles preprocessing and splits for training and testing.

## Method

- Data cleaning and feature handling
- Train and evaluate seven classifiers
- Compare accuracy and computational time
- Select the model with the best trade off

## Project structure

```text
.
├── Intrusion_Detection_System.ipynb
└── README.md
```

## Prerequisites

Python 3.8 or later with pandas, scikit-learn and matplotlib. Jupyter for the notebook.

## Usage

```bash
git clone https://github.com/mastaan66/Intrusion-detection-system.git
cd Intrusion-detection-system
pip install pandas scikit-learn matplotlib jupyter
jupyter notebook Intrusion_Detection_System.ipynb
```

Run the notebook cells in order.

## Limitations

- KDD Cup 1999 is dated and not representative of modern traffic
- Results are for educational comparison only

## Contributing

Issues and pull requests are welcome.

## License

MIT. See LICENSE.
