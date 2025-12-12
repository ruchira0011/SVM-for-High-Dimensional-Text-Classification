# SVM for High-Dimensional Text Classification — Tutorial & Code

This repository contains the complete code, figures, and written tutorial for applying Support Vector Machines (SVM) to high-dimensional text classification tasks. The project demonstrates how a Linear SVM combined with TF-IDF features can achieve strong performance on both binary (SMS Spam) and multiclass (20 Newsgroups) classification problems.

The tutorial explains:

How text is converted into numerical vectors using Bag-of-Words and TF-IDF

Why SVMs work especially well on sparse, high-dimensional data

Core concepts such as margins, support vectors, and the role of the C parameter

Practical comparison with neural networks and modern NLP approaches

Strengths and limitations of SVMs in real-world text processing tasks

A fully reproducible Jupyter Notebook is included, covering:

Data loading and preprocessing

TF-IDF vectorisation

Training and evaluating a LinearSVC model

Visualising confusion matrices and feature weights

Exploring the effect of different C values

Scaling the same pipeline to the 20 Newsgroups multiclass dataset

All figures used in the tutorial (sparsity visualisation, margin illustration, feature-weight bar plots, confusion matrices) are generated directly from the notebook to ensure transparency and reproducibility.

Datasets

SMS Spam Collection: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

20 Newsgroups: Automatically loaded via scikit-learn

This repository aims to provide a clear and accessible learning resource that demonstrates why SVMs remain a competitive baseline for NLP tasks, even alongside deep-learning models. It is suitable for students, educators, and practitioners looking to understand both the theory and practical implementation of SVM-based text classification.
