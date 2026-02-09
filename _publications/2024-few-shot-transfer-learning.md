---
layout: publication
title: "FSTL-SA: Few-shot Transfer Learning for Sentiment Analysis from Facial Expressions"
authors:
  - name: "Gaurav Meena"
    superscript: "1"
    # link: "https://www.curaj.ac.in/faculty/gaurav-meena"
  - name: "Krishna Kumar Mohbey"
    superscript: "1"
    # link: "https://www.curaj.ac.in/faculty/krishna-kumar-mohbey"
  - name: "K Lokesh"
    superscript: "2"
    # link: "{{ site.homepage }}"
affiliations:
  - "Central University of Rajasthan"
  - "Indian Institute of Technology Jodhpur"
links:
  Paper: "/assets/publications/2024-few-shot-transfer-learning/paper.pdf"
  # Code: "https://github.com/katikapalli/fstl-sa"
abstract: >
  The primary objective of sentiment analysis is determining a person's viewpoint on a subject or the document's overall contextual polarity. When a significant quantity of labeled data is provided for the target task, deep learning is demonstrated to be successful for sentiment analysis in facial expressions. Nonetheless, there is ongoing research toward training a deep learning model with few observations of labeled data such that it may generalize effectively on a novel task called Few-shot Learning. This research proposes a unique few-shot transfer learning (FSTL-SA) framework for nonverbal communication sentiment polarity categorization. First, a deep learning model is trained using a large publicly available dataset of CK+ and FER2013 on anger, fear, and surprise in the source domain. The trained model was then finetuned in the target domain using the N-way-k-shot approach on happy, sad, and neutral classes and FER2013 and CK+. In addition, we employed two-stage semi-supervised few-shot learning to address the labeled data scarcity. The proposed framework performed better than cutting-edge methods on nonverbal sentiment analysis. The proposed deep convolutional neural network (DCNN) achieved an accuracy of 75.33% in the source domain, and the FSTL-SA method achieved an average accuracy of 61% for 100 shots. Additionally, we achieved an accuracy of 82% on a single semi-supervised approach for 60-shot.
bibtex: |
  @article{meena2024fstl,
    title={FSTL-SA: few-shot transfer learning for sentiment analysis from facial expressions},
    author={Meena, Gaurav and Mohbey, Krishna Kumar and Lokesh, K},
    journal={Multimedia Tools and Applications},
    pages={1--29},
    year={2024},
    publisher={Springer}
  }
---
