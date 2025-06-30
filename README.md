# YouTube Comment Analysis 📊

A project to fetch comments from YouTube videos and perform sentiment analysis to extract insights about audience engagement and opinions.

---

## 🚀 Features

- Automatically fetch YouTube video comments
- Clean, process, and organize the comment data
- Perform sentiment analysis on collected comments
- Generate reports and visualizations to summarize results

---

## 🗂️ Project Structure

```text
├── LICENSE                <- License information
├── Makefile               <- Automation commands like `make data` or `make train`
├── README.md              <- Project overview and setup instructions

├── data
│   ├── external           <- Data from third-party sources
│   ├── interim            <- Intermediate transformed data
│   ├── processed          <- Final datasets ready for modeling
│   └── raw                <- Raw, unmodified data dumps

├── docs                   <- Project documentation (Sphinx)

├── models                 <- Trained models, serialized outputs, and predictions

├── notebooks              <- Jupyter notebooks for exploration
│   └── 1.0-xyz-description.ipynb

├── references             <- Manuals, data dictionaries, and supporting documents

├── reports
│   ├── figures            <- Generated visualizations and graphics
│   └── summaries          <- Final reports in PDF, HTML, etc.

├── requirements.txt       <- Project dependencies

├── setup.py               <- Makes the project installable with `pip install -e .`

├── src                    <- Source code
│   ├── __init__.py        <- Marks `src` as a Python module
│   ├── data               <- Scripts for data acquisition and processing
│   │   └── make_dataset.py
│   ├── features           <- Feature engineering scripts
│   │   └── build_features.py
│   ├── models             <- Scripts to train and predict with models
│   │   ├── train_model.py
│   │   └── predict_model.py
│   └── visualization      <- Scripts for creating visualizations
│       └── visualize.py

└── tox.ini                <- Configuration for testing with Tox
