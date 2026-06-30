# ML-experiments-on-ARP-spoofing-detection

Experimental part of the research for the *Computers and Networks Security* course at the University of Padua.

This repository contains the Python notebook used for the experimental analysis of Machine Learning models for ARP spoofing detection. The experiments are based on the **Kitsune Network Attack Dataset**, focusing on the **ARP MitM** scenario.

## Dataset

The dataset files are **not included** in this repository because they are too large to be stored directly on GitHub.

To reproduce the experiments, the dataset must be downloaded manually from Kaggle:

[Kitsune Network Attack Dataset - Kaggle](https://www.kaggle.com/datasets/ymirsky/network-attack-dataset-kitsune)

After downloading the dataset:

1. Extract the downloaded archive.
2. Create a folder named `data` in the root directory of this repository, if it does not already exist.
3. Copy the files related to the **ARP MitM** scenario into the `data` folder, without changing their name.
4. Run the notebook.

The expected structure is:

```text
ML-experiments-on-ARP-spoofing-detection/
│
├── results/...
│
├── data/
│   ├── ARP_MitM_dataset.csv
│   ├── ARP_MitM_labels.csv
│
├── ML_arp_spoofing_detection.ipynb
├── README.md
└── ...
