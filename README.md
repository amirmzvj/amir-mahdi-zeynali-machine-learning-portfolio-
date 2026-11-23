# Amir Mahdi Zeynali — Machine Learning Portfolio

A collection of practical notebooks and datasets covering **Machine Learning, Deep Learning, data preprocessing, Natural Language Processing, multi-armed bandits, and association-rule mining**.

This repository provides an overview of the portfolio. The complete collection—including Jupyter notebooks, CSV files, and the CNN image dataset—is available in the release archive.

[![Latest Release](https://img.shields.io/github/v/release/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-)](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0)
[![GitHub repository](https://img.shields.io/badge/GitHub-Portfolio-181717?logo=github)](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-)

## Download the complete portfolio

**Release:** [v1.0.0 — Machine Learning Portfolio](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0)

Download the `رزومه.zip` asset from the release page and extract it to access the complete folder structure.

## Portfolio at a glance

| Content | Included |
|---|---:|
| Jupyter notebooks | 32 |
| CSV datasets | 3 |
| CNN image files | 58,658 |
| Main subject areas | 6 |

## Areas of work

### 1. Machine Learning

Notebooks exploring regression, classification, model fundamentals, and common Python data-science tools:

- Linear Regression — California housing price prediction
- Support Vector Machines (SVM) and Kernel SVM
- Support Vector Regression (SVR)
- Decision Tree — Play Tennis example
- Random Forest Classification
- Diabetes-related analysis
- Gradient Descent
- NumPy, pandas, Matplotlib, and Seaborn exercises
- Housing data preprocessing
- Upper Confidence Bound (UCB) and Thompson Sampling

### 2. Deep Learning and Neural Networks

- **Artificial Neural Network (ANN):** `artificial_neural_network.ipynb`, accompanied by `Churn_Modelling.csv`.
- **Convolutional Neural Network (CNN):** convolutional neural-network and image-classification notebooks, accompanied by a labeled image collection.

The CNN image collection is organized into `Training` and `Validation` sets, each with `female` and `male` class folders:

| Split | Female | Male | Total |
|---|---:|---:|---:|
| Training | 23,243 | 23,766 | 47,009 |
| Validation | 5,841 | 5,808 | 11,649 |
| **Total** | **29,084** | **29,574** | **58,658** |

### 3. Bandit Algorithms and Association-Rule Mining

The `DEP Learning` section includes notebooks on:

- UCB with 12,000 rounds
- Contextual UCB with 15,000 observations
- Thompson Sampling with 18,000 observations
- Non-stationary Thompson Sampling with 20,000 observations
- Binary and weighted Market Basket analysis
- ECLAT frequent-itemset mining

### 4. Natural Language Processing

- Natural Language Processing fundamentals and implementation exercises.

### 5. Data Preprocessing

Notebooks and exercises covering:

- Car data preprocessing
- Water-potability data preprocessing
- Titanic data preprocessing
- NumPy array and data-selection exercises

### 6. Datasets

The archive includes these CSV files:

| File | Description |
|---|---|
| `ann/Churn_Modelling.csv` | Customer churn dataset |
| `pre/car_data.csv` | Car data with `Engine_Size` and `Price` columns |
| `pre/water_potability.csv` | Water-quality features and `Potability` target |

## Archive structure

The following is the structure inside the downloaded ZIP archive:

```text
رزومه/
├── ML/
│   ├── california_housing_price_linear_regression.ipynb
│   ├── Diabet.ipynb
│   ├── gradian_decend.ipynb
│   ├── HOUSING_preprocess.ipynb
│   ├── kernel_svm.ipynb
│   ├── mat_plot_lib(seaborn).ipynb
│   ├── mat_plot_lib.ipynb
│   ├── numpy.ipynb
│   ├── pandas(loc_iloc).ipynb
│   ├── play_tennis_decision_tree.ipynb
│   ├── random_forest_classification.ipynb
│   ├── svm.ipynb
│   ├── SVR1.ipynb
│   ├── thompson_sampling.ipynb
│   └── upper_confidence_bound.ipynb
├── DEP Learning/
│   ├── 01_UCB_12000_rounds.ipynb
│   ├── 02_UCB_Context_15000.ipynb
│   ├── 03_Thompson_18000_observations.ipynb
│   ├── 04_Thompson_NonStationary_20000.ipynb
│   ├── 06_MarketBasket_5000_binary.ipynb
│   ├── 07_MarketBasket_5000_weighted.ipynb
│   └── 08_ECLAT_8000x80_long.ipynb
├── ann/
│   ├── artificial_neural_network.ipynb
│   └── Churn_Modelling.csv
├── cnn/
│   ├── cnn gender.ipynb
│   ├── convolutional_neural_network.ipynb
│   ├── Training/
│   │   ├── female/
│   │   └── male/
│   └── Validation/
│       ├── female/
│       └── male/
├── NLP/
│   └── natural_language_processing.ipynb
└── pre/
    ├── Amir Mahde Zeynali CAR_DATA_PREPROCESS.ipynb
    ├── Amir Mahde Zeynali WATER_DATA_preprocess.ipynb
    ├── amir_mahdi_zeynali_1.ipynb
    ├── amir_mahdi_zeynali_2.ipynb
    ├── amir_mahdi_zeynali_3.ipynb
    ├── TITANIC_pre_process.ipynb
    ├── car_data.csv
    └── water_potability.csv
```

## How to use

1. Download `رزومه.zip` from the [v1.0.0 release](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0).
2. Extract the archive.
3. Open the relevant `.ipynb` file with Jupyter Notebook, JupyterLab, or Google Colab.
4. Make sure the dataset paths used by a notebook point to the extracted dataset location.
5. Install the libraries imported by that notebook in your Python environment. The archive does not include a single consolidated dependency file, so requirements may differ between notebooks.

## Notes

- This is a learning and project portfolio; notebooks may use different datasets, libraries, and workflows.
- Dataset and image-source licensing may differ from the code. Check the original dataset terms before redistributing or reusing any included data.
- No software or dataset license is declared by this repository at this time.

---

**Author:** Amir Mahdi Zeynali  
**Repository:** [amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-)
