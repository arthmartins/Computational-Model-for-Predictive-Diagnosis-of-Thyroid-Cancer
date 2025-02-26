# Computational-Model-for-Predictive-Diagnosis-of-Thyroid-Cancer
Thyroid cancer is a prevalent malignant tumor in the endocrine system, with increasing diagnoses worldwide. Early detection is crucial for improving patient outcomes and reducing invasive procedures.

Computer-Aided Diagnosis (CAD) systems, integrating AI and medical imaging, support physicians in exam interpretation. A key factor in deep learning models is the choice of activation functions, which introduce non-linearity, enhancing pattern recognition. Optimizing these functions directly impacts model learning and generalization.

This study compares activation functions for thyroid cancer detection in ultrasound images, using the ViT Hybrid model, which combines ResNet50 for feature extraction with Vision Transformers' global attention. Among the functions evaluated, the Mexican Hat wavelet, known for enhancing edge detection, stood out.

Results show Mexican Hat achieved the highest Balanced Accuracy (68.39%) and F1-Score (80%) in the ViT Hybrid, also outperforming other functions in ResNet50 alone. However, dataset imbalance led to overfitting signs.

Despite challenges, the study reinforces the importance of activation function selection in medical AI, as better models lead to more accurate diagnoses.
