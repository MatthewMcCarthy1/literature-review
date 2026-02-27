# Explainable AI in Cybersecurity: Interpreting Machine Learning Models for Phishing Detection

A systematic literature review investigating the application of LIME and SHAP explainability frameworks to machine learning-based phishing detection. 
Synthesizes 14 peer-reviewed studies (2016–2025) across traditional ML (Random Forest, SVM), deep learning (CNNs, RNNs), and transformer architectures (BERT, RoBERTa, DistilBERT).

## Key Findings

- Post-hoc explanations demonstrate strong fidelity for ensemble models but show instability and inconsistent token-level attributions on transformers.
- Almost no studies validate XAI outputs with real human users, creating an "interpretability paradox" where explanations are technically sound but practically unproven.
- Feature importance varies significantly across datasets, exposing a risk of models learning dataset-specific shortcuts rather than genuine threat indicators.

This research directly informed the design of [PhishGuard-AI](https://github.com/MatthewMcCarthy1/phishguard-ai), my final year project implementing explainable phishing detection.

**Grade:** 1.1 | ATU Galway, Year 4 Semester 1
