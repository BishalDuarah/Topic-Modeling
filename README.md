# TOPIC-MODELING

This repository contains a topic modeling project analyzing the NIPS (NeurIPS) scientific papers dataset (~7,000–8,000 documents) to uncover hidden themes in machine learning research. The project uses Latent Dirichlet Allocation (LDA) with Gensim, visualizes results with pyLDAvis, and explores applications like paper classification and research trend analysis.

OVERVIEW

Dataset: NIPS papers (1987–2017, sourced from Kaggle or NeurIPS proceedings), containing titles, abstracts, and full text in text/CSV format.
Objective: Discover research patterns, organize papers by theme, and extract actionable insights using topic modeling.
Methodology: Preprocessing (tokenization, lemmatization), bigram/trigram detection, DTM creation, LDA with 10 topics, and evaluation with coherence scores.
Results: 10 topics identified (e.g., neural networks, reinforcement learning), with some overlap due to generic terms like "model" and "use."
Visualization: Interactive pyLDAvis HTML output showing topic distributions.
Conclusion: Model captures broad themes but needs refinement for clarity; applications include classification and trend analysis.
Future Work: Tune topic numbers, explore NMF/BERTopic, and apply to larger/diverse datasets.



