# NLP_Triage_System_Demo

This demo is the output of exploring the challenging task of developing a Natural Language Preprocessing (NLP) Machine Learning (ML) model used in a triage system for a mental health forum based on a highly skewed dataset. 

I show that Bidirectional Encoder Representations from Transformers (BERT), while capable of achieving state-of-the-art results with relatively balanced datasets, does not perform well when trained on highly imbalanced classes with scarce samples. 

I explore how to address this issue by introducing cost-sensitive learning, shifting the model from a multi-class to a binary classifier, and undersampling. Results prove that these techniques can help improve BERT performance by up to +30pp increase in official F1 metric. 

The output of this project is a prototype of the final two ML models that can be tested using GoogleColab in this link: https://colab.research.google.com/drive/1oFb2y64eHuczP4hsZMsWAR8XeEPtD6tZ?usp=sharing
