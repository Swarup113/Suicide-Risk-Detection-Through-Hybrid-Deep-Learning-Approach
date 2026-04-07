# Suicide Risk Detection using NLP and Deep Learning

---

## Overview
This repository presents a deep learning-based framework for detecting suicidal ideation from social media text data. By leveraging Natural Language Processing (NLP) and Sentiment Analysis, the study aims to identify emotional distress signals from user-generated content on Reddit and Twitter.

The research evaluates multiple Deep Learning (DL) architectures alongside traditional Machine Learning (ML) models. A hybrid BiGRU-CNN model is proposed to improve performance by capturing both contextual dependencies and local textual features.

### DOI: https://doi.org/10.14569/IJACSA.2024.0150270 
---

## Research Objectives

| Objective ID | Description |
|--------------|------------|
| O1 | Detect suicidal ideation from social media text |
| O2 | Compare Deep Learning and Machine Learning approaches |
| O3 | Evaluate cross-dataset generalization |
| O4 | Develop a hybrid model for improved performance |

---

## Model Architecture Comparison

| Category | Model | Description |
|----------|------|------------|
| DL | CNN | Extracts local textual features using convolutional filters |
| DL | Bi-GRU | Captures bidirectional contextual dependencies |
| DL | BiGRU-CNN | Hybrid model combining sequential and spatial learning |
| ML | Traditional Models | Baseline classifiers for comparative evaluation |

---

## Embedding Techniques

| Embedding | Type | Key Characteristics |
|----------|------|--------------------|
| Word2Vec (CBOW) | Predictive | Context-based word prediction |
| Word2Vec (Skip-Gram) | Predictive | Performs well on sparse data |
| GloVe | Pretrained | Global word co-occurrence statistics |

---

## Methodology Pipeline

| चरण | Process | Description |
|------|--------|------------|
| 1 | Data Collection | Reddit and Twitter datasets |
| 2 | Preprocessing | Cleaning, tokenization, stopword removal |
| 3 | Feature Engineering | Word embeddings and vocabulary construction |
| 4 | Model Training | DL and ML model training with Adam optimizer |
| 5 | Evaluation | Performance analysis using multiple metrics |

---

## Evaluation Metrics

| Metric | Purpose |
|-------|--------|
| ROC Curve | Measures classification performance across thresholds |
| Confusion Matrix | Evaluates prediction correctness |
| Accuracy | Overall correctness of predictions |
| Loss Curve | Monitors training convergence |

---

## Validation Techniques

| Technique | Description |
|----------|------------|
| Manual Input Testing | Real-time input validation |
| Cross-Dataset Testing | Generalization across datasets |
| K-Fold Cross Validation | Robust statistical validation |

---

## Results

| Model | Dataset | Accuracy |
|------|--------|---------|
| BiGRU-CNN | Dataset 1 | 93.07% |
| BiGRU-CNN | Dataset 2 | 92.47% |

---

## Performance Summary

| Aspect | Observation |
|--------|------------|
| Best Model | BiGRU-CNN |
| Best Embedding | Skip-Gram |
| Optimizer | Adam |
| Generalization | Strong across datasets |
| Stability | Consistent performance across validation methods |

---

## Key Contributions

- Hybrid BiGRU-CNN architecture for improved classification performance  
- Comparative analysis of DL and ML approaches  
- Multi-source dataset evaluation (Reddit and Twitter)  
- Comprehensive validation using multiple testing strategies  

---

## Project Structure

| Directory/File | Description |
|---------------|------------|
| data/ | Raw and processed datasets |
| notebooks/ | Experimental notebooks |
| models/ | Model architectures and saved weights |
| utils/ | Helper functions and preprocessing scripts |
| results/ | Evaluation outputs and visualizations |
| README.md | Project documentation |

---

## Ethical Considerations

| Concern | Description |
|--------|------------|
| Data Privacy | No personally identifiable information should be exposed |
| Misuse Risk | Not intended for automated clinical diagnosis |
| Bias | Model performance may vary across demographics |

---

## Disclaimer
This project is intended strictly for research and academic purposes. It is not a substitute for professional mental health diagnosis, intervention, or clinical use.

---

## Keywords

| Domain | Terms |
|-------|------|
| NLP | Sentiment Analysis, Text Classification |
| Application | Suicide Risk Detection, Early Prevention |
| Techniques | Deep Learning, Machine Learning |
