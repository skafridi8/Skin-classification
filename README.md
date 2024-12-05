# Skin-classification
Objective
Skin diseases are among the most common health issues, affecting people of all ages and backgrounds worldwide. Conditions like eczema, psoriasis, and various forms of skin cancer often present similar visual characteristics, making accurate diagnosis challenging, even for experienced dermatologists. Misdiagnosis can lead to ineffective treatment and delayed care, causing unnecessary discomfort and health complications.

This project aims to leverage deep learning techniques, specifically Convolutional Neural Networks (CNNs), to accurately classify nine different skin diseases using a skin image dataset.

By developing CNN-based models, the research aims to empower both healthcare professionals and individuals to assess skin conditions quickly, with the potential to integrate the model into user friendly applications using Streamlit

Dataset Description
The dataset used for this research contains images categorized into nine skin disease classes. These classes include common conditions such as acne, eczema, and melanoma. The images are preprocessed and resized to 224x224 pixels in PNG format. This dataset is obtained from Kaggle compiled from various dermatological research sources and includes the following distribution:

Class 1: Actinic keratosis
Class 2: Atopic Dermatitis
Class 3: Benign keratosis
Class 4: Dermatofibroma
Class 5: Melanocytic nevus
Class 6: Melanoma
Class 7: Squamous cell carcinoma
Class 8: Tinea Ringworm Candidiasis
Class 9: Vascular lesion
Data Source: https://www.kaggle.com/datasets/riyaelizashaju/skin-disease-classification-image-dataset

Proposed Approach
Data preprocessing: resizing, data augmentation, normalization
Implementation of Custom CNN
Implementation of advance transfer learning approaches e.g Densenet201, Visual Transformers
Testing
If posssible, Deploying with open source tools

The performance of the ViT B16 model, achieving an accuracy of 84%, was notably superior to that of the hyperparameter-tuned and cross-validated variants. This suggests that the basic architecture, enhanced through transfer learning, was highly effective in recognizing complex patterns in the data. However, limitations persisted, as the model struggled to exceed 84% accuracy due to the dataset's inherent challenges, such as a balanced distribution of nine diverse classes and the difficulty in capturing images clearly. Future research could explore advanced transfer learning techniques, such as EfficientNet or Swin Transformer, along with fine-tuning pre-trained models to further enhance performance.
