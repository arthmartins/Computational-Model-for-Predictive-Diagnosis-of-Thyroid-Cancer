# Computational-Model-for-Predictive-Diagnosis-of-Thyroid-Cancer
Thyroid cancer is one of the most common malignant tumors in the endocrine system
 and has been increasingly diagnosed worldwide. Early detection is crucial to improving
 patient outcomes, increasing the likelihood of successful treatment, and avoiding invasive
 procedures. In this context, Computer-Aided Diagnosis (CAD) systems have emerged as
 powerful tools, combining artificial intelligence and medical image analysis to provide
 effective support to physicians in interpreting exams and making decisions. In this sce
nario, the choice of activation functions plays a critical role in the performance of deep
 learning models, such as those used in CAD systems. Activation functions are responsible
 for introducing non-linearity into neural networks, enabling models to capture complex
 patterns in medical images. Different functions directly influence the model’s learning
 and generalization capabilities, making it essential to understand their characteristics
 and explore new approaches to optimize performance. This work presents a comparative
 study of different activation functions applied to the diagnosis of thyroid cancer using
 ultrasound images, utilizing the Vision Transformer (ViT) Hybrid model. This archi
tecture combines the feature extraction capabilities of Convolutional Neural Networks
 (ResNet50) with the global attention mechanisms of Vision Transformers. Among the
 evaluated functions, the wavelet Mexican Hat, characterized by abrupt peaks in its graph
 that facilitate pattern and edge detection, was explored as an activation function in a
 complex problem. The metrics analyzed highlight exican Hat as the best function for Bal
anced Accuracy (68.39%) and F1-Score (80%) in the ViT Hybrid, while also achieving
 superior performance compared to other functions when applied to the ResNet50 alone.
 However, the results indicate that the model faces limitations due to dataset imbalance
 and scarcity, leading to signs of overfitting during training. Despite these challenges, the
 study reinforces the importance of selecting suitable activation functions in the medical
 context, as better performance translates into more accurate diagnoses.
