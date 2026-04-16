# K-VQG: A Study on Knowledge-based Visual Question Generation
![](./Public/assets/hero.png)
## Overview

This repository contains the end-to-end implementation and system architecture for K-VQG, a research-driven framework designed to automate the generation of high-context questions from visual data. By integrating Large Multimodal Models (LMMs) with Sequence-to-Sequence (Seq2Seq) architectures, the project demonstrates a scalable approach to interpreting visual content through structured AI orchestration.

## Thesis Abstract

Extracting information from images is an increasingly prominent task due to its ever-expanding utility and applications. Generating knowledge-based questions (and answers) from images is a more novel approach of this that complements traditional image analysis techniques, offering a more interpretive method for understanding visual content. Knowledge-based questions are designed to prompt responses that extract relevant information from the subject image. In this study, we developed and examined various techniques for performing Knowledge-Based Visual Question Generation (K-VQG). These techniques included prompt engineering utilizing the latest large multimodal model (GPT-4 Vision) and employing sequence-to-sequence (Seq2Seq) models with semantic role labels (SRLs). Within the study, we employed various prompts aimed at providing context through both categorization and few-shot learning techniques. Alongside this, we implemented a sequence-to-sequence (Seq2Seq) model for textual question generation, anchored in semantic role labels, using LLM-generated captions of the images as its input. We observed that the proposed 2-shot learning method delivered the best results on the quantitative metrics (Semantic Similarity, METEOR, etc.).

## Contents

- **Code:** Contains the code implementations used for data collection, question generation, training, and evaluation.
- **Documentation:** [Thesis Report](Documentation/Thesis%20Report%20(Ammar%20Hatiya).pdf)
, alongside supplementary materials such as resource guides, and related literature.
- **Results:** Evaluation metrics, analysis results, and visualizations.
- **Data:** Includes Ground truth data and CSV files used in the study.

## Author

- **Author:** Ammar Hatiya
- **Field of Study:** Computer Science
- **Degree:** Honours Bachelors of Science, Computer Science Co-op

## Contact

For any inquiries or collaborations, feel free to contact the author:

[Ammar Hatiya](mailto:ammar.hatiya@gmail.com)


