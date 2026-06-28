# Hackathon Prep
## Project structure

```text
hackathon-prep/
├── competitions/
│   └── titanic/
│       └── notebooks/
│           ├── 01_eda.ipynb          # Exploratory data analysis for Titanic
│           └── 02_baseline.ipynb     # Baseline ML pipeline and validation
│
├── data/
│   └── titanic/                      # Local Titanic dataset files
│       ├── train.csv                 # Ignored by Git
│       ├── test.csv                  # Ignored by Git
│       └── gender_submission.csv     # Ignored by Git
│
├── models/                           # Saved models, ignored by Git
├── notebooks/                        # General notebooks
├── notes/                            # Study notes and useful materials
├── src/                              # Reusable Python code
├── submissions/
│   └── titanic/
│       └── baseline_logreg.csv       # Local Kaggle submission, ignored by Git
│
├── README.md
└── .gitignore
```

### Notes

* Raw data files are stored locally in `data/` and are ignored by Git.
* Submission files are stored locally in `submissions/` and are ignored by Git.
* Competition-specific notebooks are stored inside `competitions/<competition_name>/notebooks/`.
* The Titanic baseline model reached a validation accuracy of `0.8156`.
