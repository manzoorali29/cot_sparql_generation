---
date: '2024-07-04'
title: 'Cross-Lingual Transfer Learning for Named Entity Recognition in Low-Resource Languages'
type: 'Master'
supervisor: dice:HamadaZahera dice:ManzoorAli
contact: dice:ManzoorAli
---

## Overview

This topic would investigate the effectiveness of cross-lingual transfer learning for performing Named Entity Recognition (NER) in low-resource languages. The thesis would involve pre-training a model on high-resource languages, and then fine-tuning it on annotated datasets of low-resource languages. Special attention would be given to the challenges of morphological complexity and the scarcity of annotated data in these languages. The research could also explore innovative data augmentation techniques and the use of unsupervised or semi-supervised methods to improve the availability of training data
For instance, Wu and Dredze (2019) demonstrated that mBERT, when fine-tuned on NER datasets from multiple high-resource languages, can effectively transfer knowledge to low-resource languages, achieving competitive results without the need for extensive annotated data in the target language. Similarly, the work by Rahimi, Li, and Cohn (2019) utilized cross-lingual word embeddings to enhance NER in low-resource languages, showing that shared multilingual representations can bridge the gap between languages. These studies underscore the potential of cross-lingual transfer learning as a powerful strategy for addressing the limitations faced by NER systems in low-resource languages, ultimately contributing to more inclusive and diverse natural language processing tools.

### Research Gaps

Limited exploration of unsupervised methods for cross-lingual NER: Most existing research on cross-lingual NER has focused on supervised methods, which require labeled data in the source language. There is a gap in understanding how unsupervised methods can be effectively used for cross-lingual NER in low-resource language 

### Tasks

- Investigate the state-of-the-art in cross-lingual NER
- Develop an approach for transferring knowledge from model trained on high resource language to low resource language. 
- Data augmentation techniques for generating labelled data for low resource languages.
- Transfer learning approach to train a model to surface the existing benchmarks
- Documentation of all the module steps performed during the whole process

### Useful Resources

- The Surprising Cross-Lingual Effectiveness of BERT
  https://aclanthology.org/D19-1077/ 
- Massively Multilingual Transfer for NER
 https://aclanthology.org/P19-1015/ 
- A survey on Named Entity Recognition—datasets, tools, and methodologies https://www.sciencedirect.com/science/article/pii/S2949719123000146 
- Cross Lingual Named Entity Recognition using Deep Learning
  https://scholarworks.calstate.edu/downloads/c247f136q 
- A Comprehensive Survey on Transfer Learning
https://ieeexplore.ieee.org/abstract/document/9134370/?casa_token=_oo20BaCEbUAAAAA:M51WIX96HO4Ju4rkZld_1_3JfEUzw6gPd6ESDc7rk-AC6W819FkcnS6FK9xRoRS6DdTpPzIIs0E 

### Prerequisites

- Basic NLP concepts
- Proficiency with Python Programming 
- Deep learning and Transfer learning concepts
