# Bias & Trustworthiness in Hate Speech Detection

<img width="1536" height="1024" alt="1 correctOne" src="https://github.com/user-attachments/assets/cb58482b-3c3d-4060-8600-054db607ff51" />

An Explainability Analysis Using SHAP and Human Rationales


## What This Project Does
Compares four models [Majority Class, TF-IDF, FastText, DistilBERT] on the HateXplain dataset and uses SHAP to check if the model looks at the same words as human annotators when detecting hate speech.


## Dataset
HateXplain (Mathew et al., AAAI 2021) - 20,148 posts from Twitter and Gab with human rationales.


## Models
- Level 0: Majority Class(40% accuracy)
- Level 1: TF-IDF + Logistic Regression(63% accuracy)
- Level 2: FastText + Logistic Regression (58% accuracy)
- Level 3: DistilBERT fine-tuned(66% accuracy)


## Main Finding
The model relies on a single keyword for its predictions.
Humans consider 28 words of context.
Right answer, incomplete reasoning.


## Author
Elif Gafar | MSc Human-Centered AI
