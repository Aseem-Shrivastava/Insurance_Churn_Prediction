# Insurance Churn Prediction

The project uses an anonymized dataset to train a model capable of predicting insurance policy customer churn. The dataset is sourced from Kaggle, but was originally part of a Hackathon by MachineHack.

Key Features:
1. Thorough data exploration and visualization
2. Training multiple classification models, evaluating them on relevant metrics and selecting the best performing model
3. Hyper-parameter tuning the best performing model
4. Employing oversampling method to tackle the imbalanced dataset and improving the model performance


## Project Organization

```
├── README.md          <- The top-level README for developers using this project.
├── data
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         src and configuration for tools like black
│
├── environment.yml    <- The environment file for reproducing the analysis environment
│
├── setup.cfg          <- Configuration file for flake8
│
└── src   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes src a Python module
    │
    └── analysis.ipynb          <- Jupyter notebook with data analysis and modelling
```

--------

