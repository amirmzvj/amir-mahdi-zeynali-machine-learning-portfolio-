# Amir Mahdi Zeynali — Machine Learning Portfolio

A practical portfolio of Python and Jupyter Notebook work across **Machine Learning, Deep Learning, Computer Vision, Natural Language Processing, data preprocessing, multi-armed bandits, and association-rule mining**.

<p align="left">
  <a href="https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0"><img src="https://img.shields.io/github/v/release/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-?label=GitHub%20Release&color=181717" alt="Latest GitHub release"></a>
  <a href="https://www.kaggle.com/datasets/amirmahdizeynali/amir-mahdi-zeynali-machine-learning-portfolio"><img src="https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle&logoColor=white" alt="Kaggle dataset"></a>
  <a href="https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-"><img src="https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white" alt="GitHub repository"></a>
</p>

## Explore the portfolio

| Resource | What you will find |
|---|---|
| [Kaggle Dataset](https://www.kaggle.com/datasets/amirmahdizeynali/amir-mahdi-zeynali-machine-learning-portfolio) | Dataset page and downloadable portfolio files |
| [GitHub Release v1.0.0](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0) | Complete ZIP archive (`رزومه.zip`) |
| [Portfolio Showcase Notebook](Portfolio_Showcase.ipynb) | Guided index of the projects and a small archive-inspection utility |

> **Quick start:** Download `رزومه.zip` from the [GitHub Release](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0), extract it, and open the notebooks with Jupyter Notebook, JupyterLab, or Google Colab.

## Portfolio at a glance

| Content | Included |
|---|---:|
| Jupyter notebooks | 32 |
| CSV datasets | 3 |
| CNN image files | 58,658 |
| Main subject areas | 6 |

## Areas of work

### 1. Machine Learning and Python data tools

The `ML/` folder includes practical notebooks on:

- Linear Regression — California housing price prediction
- Support Vector Machine (SVM), Kernel SVM, and Support Vector Regression (SVR)
- Decision Tree — Play Tennis example
- Random Forest Classification
- Diabetes-related analysis and housing-data preprocessing
- Gradient Descent
- NumPy, pandas, Matplotlib, and Seaborn exercises
- Upper Confidence Bound (UCB) and Thompson Sampling

### 2. Deep Learning and Neural Networks

- **Artificial Neural Network (ANN):** `ann/artificial_neural_network.ipynb`, with `ann/Churn_Modelling.csv`.
- **Convolutional Neural Network (CNN):** `cnn/convolutional_neural_network.ipynb` and `cnn/cnn gender.ipynb`, with image folders split into `Training` and `Validation` and labeled `female` / `male`.

CNN image counts:

| Split | Female | Male | Total |
|---|---:|---:|---:|
| Training | 23,243 | 23,766 | 47,009 |
| Validation | 5,841 | 5,808 | 11,649 |
| **Total** | **29,084** | **29,574** | **58,658** |

### 3. Bandit algorithms and association-rule mining

The `DEP Learning/` folder contains notebooks for:

- UCB with 12,000 rounds
- Contextual UCB with 15,000 observations
- Thompson Sampling with 18,000 observations
- Non-stationary Thompson Sampling with 20,000 observations
- Binary and weighted Market Basket analysis
- ECLAT frequent-itemset mining

### 4. Natural Language Processing

- NLP fundamentals, text cleaning, and a Bag-of-Words workflow in `NLP/natural_language_processing.ipynb`.

### 5. Data preprocessing

- Car data preprocessing
- Water-potability data preprocessing
- Titanic data preprocessing
- NumPy array and data-selection exercises

### 6. Included CSV datasets

| File | Description |
|---|---|
| `ann/Churn_Modelling.csv` | Customer churn dataset |
| `pre/car_data.csv` | Car data with `Engine_Size` and `Price` columns |
| `pre/water_potability.csv` | Water-quality features and `Potability` target |

## Notebook index

<details>
<summary><strong>Machine Learning — ML/</strong></summary>

- `california_housing_price_linear_regression.ipynb`
- `Diabet.ipynb`
- `gradian_decend.ipynb`
- `HOUSING_preprocess.ipynb`
- `kernel_svm.ipynb`
- `mat_plot_lib(seaborn).ipynb`
- `mat_plot_lib.ipynb`
- `numpy.ipynb`
- `pandas(loc_iloc).ipynb`
- `play_tennis_decision_tree.ipynb`
- `random_forest_classification.ipynb`
- `svm.ipynb`
- `SVR1.ipynb`
- `thompson_sampling.ipynb`
- `upper_confidence_bound.ipynb`

</details>

<details>
<summary><strong>Bandits and Market Basket — DEP Learning/</strong></summary>

- `Amir Mahde Zeynali 01_UCB_12000_rounds.ipynb`
- `Amir Mahde Zeynali 02_UCB_Context_15000.ipynb`
- `Amir Mahde Zeynali 03_Thompson_18000_observations.ipynb`
- `Amir Mahde Zeynali 04_Thompson_NonStationary_20000.ipynb`
- `Amir Mahde Zeynali 06_MarketBasket_5000_binary.ipynb`
- `Amir Mahde Zeynali 07_MarketBasket_5000_weighted.ipynb`
- `Amir Mahde Zeynali 08_ECLAT_8000x80_long.ipynb`

</details>

<details>
<summary><strong>Other project folders</strong></summary>

- `ann/artificial_neural_network.ipynb`
- `cnn/cnn gender.ipynb`
- `cnn/convolutional_neural_network.ipynb`
- `NLP/natural_language_processing.ipynb`
- `pre/Amir Mahde Zeynali CAR_DATA_PREPROCESS.ipynb`
- `pre/Amir Mahde Zeynali WATER_DATA_preprocess.ipynb`
- `pre/amir_mahdi_zeynali_1.ipynb`
- `pre/amir_mahdi_zeynali_2.ipynb`
- `pre/amir_mahdi_zeynali_3.ipynb`
- `pre/TITANIC_pre_process.ipynb`

</details>

## How to use

1. Download `رزومه.zip` from the [GitHub Release](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-/releases/tag/v1.0.0) or use the [Kaggle Dataset](https://www.kaggle.com/datasets/amirmahdizeynali/amir-mahdi-zeynali-machine-learning-portfolio).
2. Extract the archive if you downloaded the ZIP.
3. Open a relevant `.ipynb` file with Jupyter Notebook, JupyterLab, or Google Colab.
4. Check the dataset paths used by that notebook and adjust them to your extracted folder location.
5. Install the libraries imported by the notebook. There is no single consolidated requirements file, so dependencies may differ between projects.

## Notes

- This is a learning and project portfolio; notebooks may use different datasets, libraries, and workflows.
- Dataset and image-source terms may differ from the code. Review the original terms before redistributing or reusing third-party data.
- No single software or dataset license is declared for the entire collection.

---

**Author:** Amir Mahdi Zeynali  
**GitHub:** [amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-](https://github.com/amirmzvj/amir-mahdi-zeynali-machine-learning-portfolio-)  
**Kaggle:** [Machine Learning Portfolio](https://www.kaggle.com/datasets/amirmahdizeynali/amir-mahdi-zeynali-machine-learning-portfolio)
