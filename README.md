# PD-Detection-Transformer-GMM
This repository contains the Python implementation for the article "VITA: Voice-based Intelligent Transformer-GMM Assessment Framework for Parkinson’s Disease Diagnosis." The code combines GMM, Transformers, and SHAP analysis for accurate and interpretable voice-based diagnosis.


# VITA: Voice-based Intelligent Transformer-GMM Assessment Framework for Parkinson’s Disease Diagnosis

## Overview

VITA (Voice-based Intelligent Transformer-GMM Assessment) is an AI-driven framework for the early diagnosis of Parkinson’s Disease (PD) using voice recordings. The framework combines the probabilistic clustering capabilities of Gaussian Mixture Models (GMMs) with the representation learning power of Transformer networks to provide accurate, interpretable, and scalable PD assessment.

Early detection of Parkinson’s Disease remains a major clinical challenge due to symptom overlap with other neurological disorders and the dependence on specialist evaluations. VITA addresses these limitations through a non-invasive voice-based diagnostic approach enhanced by explainable artificial intelligence (XAI) techniques.

## Key Features

* Voice-based and non-invasive Parkinson’s Disease assessment
* Hybrid Transformer-GMM architecture
* Advanced preprocessing and feature engineering pipeline
* Dimensionality reduction for efficient learning
* Explainable AI (XAI) using SHAP for prediction transparency
* Scalable framework suitable for telemonitoring and clinical support systems

## Methodology

The proposed framework integrates:

1. **Voice Signal Processing**

   * Extraction and preprocessing of speech features from PD datasets.

2. **Gaussian Mixture Models (GMM)**

   * Probabilistic clustering and latent pattern discovery.

3. **Transformer Network**

   * Deep feature extraction and classification.

4. **Explainability Module**

   * SHAP-based interpretation of model predictions to improve clinical trustworthiness.

## Dataset

The model was evaluated using publicly available Parkinson’s Disease voice datasets containing:

* 756 voice recordings
* 252 speakers
* Unified Parkinson’s Disease Rating Scale (UPDRS) scores
* Overall and motor assessment labels

## Results

The proposed VITA framework achieved:

| Metric   | Score  |
| -------- | ------ |
| Accuracy | 90.18% |
| F1-Score | 92.91% |

The results demonstrate the effectiveness of combining Transformer architectures with probabilistic modeling for robust Parkinson’s Disease diagnosis.

## Publication

If you use this work, please cite:

```bibtex
@inproceedings{shafaati2025vita,
  author={Shafaati, Saghar and Beheshtifard, Zahra},
  title={VITA: A Voice-based Intelligent Transformer-GMM Assessment Framework for Parkinson's Disease Diagnosis},
  booktitle={2025 11th International Conference on Signal Processing and Intelligent Systems (ICSPIS)},
  year={2025},
  pages={344--349},
  doi={10.1109/ICSPIS68676.2025.11551713}
}
```

## Paper Access

* DOI: https://doi.org/10.1109/ICSPIS68676.2025.11551713
* Open-access version: https://www.researchgate.net/publication/406901668_VITA_A_Voice-based_Intelligent_Transformer-GMM_Assessment_Framework_for_Parkinson's_Disease_Diagnosis

## Keywords

Parkinson’s Disease, Deep Learning, Machine Learning, Transformer Networks, Explainable AI, Voice Analysis, Medical Diagnosis, Early Detection, Healthcare AI, Signal Processing.

## Future Directions

* Multimodal data fusion
* Real-time patient telemonitoring
* Clinical decision support systems
* Personalized disease progression analysis

## Authors

**Saghar Shafaati**
Computer Engineering Researcher

**Ziaeddin Beheshtifard**
