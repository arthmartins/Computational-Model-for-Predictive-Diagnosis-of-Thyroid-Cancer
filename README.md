# Computational-Model-for-Predictive-Diagnosis-of-Thyroid-Cancer
Thyroid cancer is a prevalent malignant tumor in the endocrine system, with increasing diagnoses worldwide. Early detection is crucial for improving patient outcomes and reducing invasive procedures.

Computer-Aided Diagnosis (CAD) systems, integrating AI and medical imaging, support physicians in exam interpretation. A key factor in deep learning models is the choice of activation functions, which introduce non-linearity, enhancing pattern recognition. Optimizing these functions directly impacts model learning and generalization.

This study compares activation functions for thyroid cancer detection in ultrasound images, using the ViT Hybrid model, which combines ResNet50 for feature extraction with Vision Transformers' global attention. Among the functions evaluated, the Mexican Hat wavelet, known for enhancing edge detection, stood out.

Results show Mexican Hat achieved the highest Balanced Accuracy (68.39%) and F1-Score (80%) in the ViT Hybrid, also outperforming other functions in ResNet50 alone. However, dataset imbalance led to overfitting signs.

Despite challenges, the study reinforces the importance of activation function selection in medical AI, as better models lead to more accurate diagnoses.

## Architeture

The architecture used in this work is based on the Hybrid Vision Transformer (ViT) model. This model integrates the features of Convolutional Neural Networks (CNNs) and the Vision Transformer. The combination aims to leverage the strengths of both approaches: efficient local feature extraction through ResNet50 and the ViT's ability to capture global dependencies using self-attention mechanisms. This hybrid design enhances the model's performance in tasks requiring both detailed local information and an understanding of broader contextual relationships within the data.

![ArquiteturaHViT](https://github.com/user-attachments/assets/549abcec-0d5d-444d-bbd0-2e1b443c454b)

## Results

![image](https://github.com/user-attachments/assets/ee463d40-292f-485c-9745-575ff7db888e)

The table above presents the combination of two previously shown tables, comparing the performance of activation functions with the Hybrid Vision Transformer (ViT) and ResNet50. The functions that achieved the best results in the metrics for each model are highlighted in bold: the Mexican Hat wavelet with the ViT Hybrid and ReLU with ResNet50.

* The Mexican Hat wavelet showed superior results in terms of Balanced Accuracy and precision when used with the ViT Hybrid, correctly classifying 10 ultrasound images as positive.
* ReLU performed better in classifying negative images, identifying 2 additional images, but struggled with positive classifications.
* The negative class had only 30 images, so the small difference in correct classifications had a significant impact on Balanced Accuracy.
* The Mexican Hat wavelet performed well in both architectures, being the best with the ViT Hybrid and the second-best with ResNet50, demonstrating strong potential for thyroid cancer classification.
* In contrast, ReLU, which initially performed poorly, showed improved results with ResNet50, highlighting how performance can vary based on the architecture used.

However, when analyzing the results, it is evident that the model suffered from overfitting. This is reflected in its low performance, reaching a maximum of 70% balanced accuracy, along with a high discrepancy in the values of Precision and Recall.

## Conclusion

This study aimed to compare different activation functions for thyroid cancer diagnosis using Hybrid Vision Transformer architecture, which combines ResNet50 for feature extraction with Vision Transformer for attention mechanisms. The functions evaluated included Sigmoid, ReLU, PReLU, ELU, SELU, Tanh, and the Mexican Hat wavelet. Although overall results were modest, the Mexican Hat wavelet emerged as the best performer, achieving 68.39% in Balanced Accuracy and 80% in F1-Score for the Hybrid ViT, while in ResNet50, it ranked second, following ReLU, which achieved 70.73% in Balanced Accuracy and 79% in F1-Score.

Nevertheless, the results highlight the significant impact of choosing activation functions, emphasizing how appropriate selection can enhance accuracy in thyroid cancer diagnosis. The study of new activation functions proved promising, with the Mexican Hat wavelet consistently performing best in Hybrid ViT tests.


