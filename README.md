# Identifying Key Brain Biomarkers for Alzheimer's Disease Progression and Stability: A Machine Learning Approach
## Summary

This repository contains the code and methodology for identifying critical brain MRI biomarkers associated with Alzheimer's disease progression and cognitive stability using machine learning techniques. By analyzing longitudinal and baseline neuroimaging data, we developed predictive models that outperform conventional full-feature models.

Our work leverages Random Forests, Support Vector Machines, and SHAP-based feature selection to extract the most informative biomarkers. SMOTE oversampling was employed to handle class imbalance, leading to improved classification accuracy. Key biomarkers identified include the Left Fusiform Gyrus, Right Middle Frontal Gyrus, and Parahippocampal Gyrus asymmetry.

## Key Findings

- **Random Forest** models trained on **SMOTE-balanced datasets** achieved the highest predictive accuracy.
- Using **only the top 10 SHAP-ranked features** improved pMCI classification by **6%** and sMCI classification by **8.5%** over models using all 300 biomarkers.
- Identified important biomarkers validated existing neurobiological knowledge, enhancing interpretability and clinical relevance.
- This feature selection strategy enables efficient, accurate early diagnosis tools and supports the development of personalized intervention strategies.

## Highlights

- **Datasets:** Alzheimer's Disease Neuroimaging Initiative (ADNI) - MRI-based biomarker data.
- **Techniques:** Random Forest, SVM, SHAP Values, SMOTE.
- **Goal:** Early diagnosis of Alzheimer's disease by predicting progression and stability patterns using a minimal set of biomarkers.
- **Outcome:** Reduced biomarkers while achieving superior classification accuracy for pMCI and sMCI groups.
