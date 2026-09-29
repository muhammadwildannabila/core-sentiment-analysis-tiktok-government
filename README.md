<div align="center">

# Sentiment Analysis of TikTok Comments on Batu City Government

### NLP · Public Sentiment Analytics · Machine Learning · Government Communication

**Empirical Analysis of Social Media Feedback for Public-Sector Communication**

<br>

<img src="assets/sentiment.png" width="520" alt="TikTok Public Sentiment Analysis">

<br><br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-7C3AED?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![TikTok](https://img.shields.io/badge/TikTok-Social%20Media%20Data-000000?style=flat-square&logo=tiktok&logoColor=white)

<br>

![Dataset](https://img.shields.io/badge/DATASET-1%2C647%20COMMENTS-2563EB?style=for-the-badge)
![Models](https://img.shields.io/badge/MODELS-6%20COMPARED-7C3AED?style=for-the-badge)
![Best Accuracy](https://img.shields.io/badge/BEST%20ACCURACY-79%25-22C55E?style=for-the-badge)

<br><br>

**Collect → Process → Classify → Compare → Interpret**

<br>

[![Presentation](https://img.shields.io/badge/VIEW-PROJECT%20PRESENTATION-00C4CC?style=for-the-badge&logo=canva&logoColor=white)](https://canva.link/2twsf1ms0kozj70)

</div>

---

## Project at a Glance

<table>
<tr>
<td align="center" width="20%">
<strong>1,647</strong><br>
TikTok Comments
</td>
<td align="center" width="20%">
<strong>3 Classes</strong><br>
Sentiment
</td>
<td align="center" width="20%">
<strong>6 Models</strong><br>
Compared
</td>
<td align="center" width="20%">
<strong>SVM</strong><br>
Highest Accuracy
</td>
<td align="center" width="20%">
<strong>79%</strong><br>
Best Reported Accuracy
</td>
</tr>
</table>

> **Project focus:** Analyzing TikTok comments related to Batu City Government content to explore sentiment patterns, recurring discussion terms, and machine-learning approaches for public-feedback classification.

---

# Project Context

Government social-media channels generate direct and highly unstructured public feedback.

Individual comments can contain:

- opinions,
- questions,
- complaints,
- appreciation,
- informal expressions,
- and discussion of public services.

Analyzing these comments manually becomes increasingly difficult as their volume grows.

This project explores:

> ### How can NLP and machine learning transform TikTok comments into structured sentiment and discussion patterns that support government communication analysis?

The analytical workflow moves from:

```text
TikTok Comments
      │
      ▼
Unstructured Public Feedback
      │
      ▼
NLP Processing
      │
      ├── Sentiment Analysis
      ├── Keyword Exploration
      └── Model Comparison
              │
              ▼
     Communication Insights
```

---

# Internship Context

This project was developed in the context of a **2025 internship at DISKOMINFO Kota Batu** as a practical application of data analytics, Natural Language Processing, and machine learning to public-sector communication analysis.

The project analyzes social-media feedback associated with Batu City Government content and demonstrates how computational text analysis can support structured exploration of digital public feedback.

> The analytical results represent patterns in the collected TikTok comments and should not be interpreted as representative measurements of all Batu City residents.

---

# Research Objectives

The analysis focuses on five objectives:

1. Collect and preprocess TikTok comment data.
2. Analyze Positive, Neutral, and Negative sentiment patterns.
3. Explore frequently occurring terms and discussion signals.
4. Compare multiple machine-learning classification algorithms.
5. Translate analytical findings into communication-oriented insights.

---

# Dataset Overview

| Dimension | Scope |
|---|---|
| **Data Source** | TikTok Comments |
| **Total Comments** | **1,647** |
| **Target Context** | Batu City Government |
| **Sentiment Classes** | Positive · Neutral · Negative |
| **Domain** | Government Social Media Analytics |
| **Primary Task** | Multiclass Sentiment Classification |
| **Models Compared** | **6 Machine Learning Models** |

The dataset provides an empirical basis for analyzing sentiment within the collected social-media comments.

---

# Analytical Workflow

```text
                      TIKTOK COMMENTS
                             │
                             ▼
                       DATA COLLECTION
                             │
                             ▼
                 CLEANING & PREPROCESSING
                             │
                             ▼
                EXPLORATORY DATA ANALYSIS
                             │
                  ┌──────────┴──────────┐
                  ▼                     ▼
           SENTIMENT ANALYSIS      KEYWORD ANALYSIS
                  │                     │
                  ▼                     │
           TEXT FEATURES               │
                  │                     │
                  ▼                     │
       MACHINE LEARNING MODELS          │
                  │                     │
                  ▼                     │
          MODEL EVALUATION              │
                  │                     │
                  └──────────┬──────────┘
                             ▼
                   ANALYTICAL INSIGHTS
                             │
                             ▼
               COMMUNICATION EVALUATION
```

This workflow connects raw text processing with quantitative model comparison and qualitative interpretation.

---

# Sentiment Distribution

<p align="center">
  <img src="assets/sentiment.png" alt="TikTok Comment Sentiment Distribution" width="800">
</p>

| Sentiment | Share |
|---|---:|
| 🟢 **Positive** | **33.8%** |
| ⚪ **Neutral** | **44.0%** |
| 🔴 **Negative** | **22.2%** |

<div align="center">

![Positive](https://img.shields.io/badge/POSITIVE-33.8%25-22C55E?style=for-the-badge)
![Neutral](https://img.shields.io/badge/NEUTRAL-44.0%25-64748B?style=for-the-badge)
![Negative](https://img.shields.io/badge/NEGATIVE-22.2%25-DC2626?style=for-the-badge)

</div>

### Key Observation

**Neutral sentiment represents the largest category in the analyzed comments at 44.0%.**

Positive comments account for 33.8%, while 22.2% are classified as negative.

```text
Neutral   ██████████████████████  44.0%
Positive  █████████████████       33.8%
Negative  ███████████             22.2%
```

The dominance of neutral classifications describes the sentiment distribution of the analyzed dataset.

It does **not by itself establish why** those comments are neutral or whether government communication is effective. Answering those questions requires closer examination of comment content and communication context.

---

# Keyword Exploration

<p align="center">
  <img src="assets/wordcloud.png" alt="TikTok Comment Word Cloud" width="850">
</p>

Frequently occurring terms include:

<div align="center">

![Batu](https://img.shields.io/badge/BATU-Frequent%20Term-2563EB?style=flat-square)
![Kota](https://img.shields.io/badge/KOTA-Frequent%20Term-7C3AED?style=flat-square)
![Sae](https://img.shields.io/badge/SAE-Frequent%20Term-22C55E?style=flat-square)
![Parkir](https://img.shields.io/badge/PARKIR-Discussion%20Signal-D97706?style=flat-square)

</div>

The occurrence of terms such as **batu**, **kota**, **sae**, and **parkir** highlights recurring vocabulary within the collected comments.

The presence of **parkir** suggests that parking-related discussion appears within the corpus and may warrant deeper qualitative investigation.

> Word frequency alone does not establish whether a topic is positive, negative, urgent, or representative of broader citizen concerns.

---

# Machine Learning Benchmark

Six classification algorithms were compared.

| Model | Reported Accuracy |
|---|---:|
| **Support Vector Machine (SVM)** | **79%** |
| Decision Tree | 76% |
| Neural Network | 76% |
| Random Forest | 73% |
| Naive Bayes | 72% |
| K-Nearest Neighbors | 58% |

<div align="center">

![SVM](https://img.shields.io/badge/SVM-79%25-22C55E?style=for-the-badge)
![DT](https://img.shields.io/badge/DT-76%25-2563EB?style=flat-square)
![NN](https://img.shields.io/badge/NN-76%25-7C3AED?style=flat-square)
![RF](https://img.shields.io/badge/RF-73%25-D97706?style=flat-square)
![NB](https://img.shields.io/badge/NB-72%25-0891B2?style=flat-square)
![KNN](https://img.shields.io/badge/KNN-58%25-64748B?style=flat-square)

</div>

Based on the **reported accuracy metric**, SVM achieved the highest observed performance.

---

# Model Performance Comparison

<p align="center">
  <img src="assets/model-comparison.png" alt="Sentiment Classification Model Comparison" width="850">
</p>

The experiment demonstrates that different classification algorithms respond differently to the same text-classification task.

```text
SVM              ████████████████████  79%
Decision Tree    ███████████████████   76%
Neural Network   ███████████████████   76%
Random Forest    ██████████████████    73%
Naive Bayes      ██████████████████    72%
KNN              ████████████          58%
```

### Model Selection

**Support Vector Machine achieved the highest reported accuracy at 79%.**

This makes SVM the strongest model **under the reported accuracy comparison**.

However, accuracy alone does not provide a complete evaluation of multiclass sentiment classification.

Additional metrics such as:

`Precision` · `Recall` · `Macro F1` · `Weighted F1` · `Confusion Matrix`

would provide stronger evidence regarding performance across Positive, Neutral, and Negative classes.

---

# Why SVM Works Well for Text Classification

SVM is well suited to many traditional NLP classification problems because text representations commonly produce:

- high-dimensional feature spaces,
- sparse feature matrices,
- many potentially informative terms,
- and complex class boundaries.

Conceptually:

```text
Text
 │
 ▼
Feature Representation
 │
 ▼
High-Dimensional Vector Space
 │
 ▼
Support Vector Machine
 │
 ▼
Decision Boundary
 │
 ▼
Sentiment Class
```

The result in this project is consistent with SVM being competitive for sparse text-classification tasks.

---

# Key Analytical Findings

<table>
<tr>
<td width="50%" valign="top">

### 01 · Neutral Sentiment Dominates

**44.0%** of analyzed comments were classified as Neutral, making it the largest sentiment category.

This describes the composition of the collected TikTok-comment dataset.

</td>
<td width="50%" valign="top">

### 02 · Positive Exceeds Negative

Positive sentiment accounts for **33.8%**, compared with **22.2% Negative**.

This indicates that positive classifications occur more frequently than negative classifications within the analyzed comments.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 03 · Parking Appears in Discussion

The term **parkir** appears prominently in keyword exploration.

This provides a signal for deeper qualitative investigation into parking-related discussion.

</td>
<td width="50%" valign="top">

### 04 · SVM Leads Accuracy Comparison

Among six evaluated algorithms, **SVM recorded the highest reported accuracy at 79%**.

Further class-level metrics would strengthen the model-selection evidence.

</td>
</tr>
</table>

---

# From Comments to Communication Intelligence

```text
                     TIKTOK COMMENTS
                            │
                            ▼
                       NLP ANALYSIS
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
         SENTIMENT                     KEYWORDS
              │                           │
              ▼                           ▼
    Positive / Neutral /          Discussion Signals
         Negative                        │
              │                           │
              └─────────────┬─────────────┘
                            ▼
                    PATTERN REVIEW
                            │
                            ▼
                    HUMAN INTERPRETATION
                            │
                            ▼
                COMMUNICATION INSIGHTS
```

The analytical output is intended to **support human interpretation**, not replace contextual evaluation of public communication.

---

# Practical Relevance

The analysis can potentially support public-sector communication teams by helping them:

| Analytical Output | Potential Application |
|---|---|
| Sentiment distribution | Monitor patterns in collected feedback |
| Negative classifications | Prioritize comments for qualitative review |
| Frequent keywords | Identify recurring discussion signals |
| Model classification | Structure large volumes of text |
| Temporal extension | Compare sentiment across communication periods |
| Content-level analysis | Explore responses to different posts |

These are potential analytical applications rather than demonstrated improvements in communication effectiveness.

---

# Responsible Interpretation

Social-media sentiment analysis requires several important distinctions.

### TikTok Comments ≠ All Citizens

The dataset represents collected comments from TikTok users, not a representative survey of Batu City residents.

### Sentiment ≠ Communication Effectiveness

Positive or negative classifications alone cannot determine whether a communication strategy is successful.

### Keyword Frequency ≠ Issue Severity

A frequently occurring term may warrant investigation, but frequency alone does not establish urgency or importance.

### Correlation ≠ Causation

Observed comment patterns do not demonstrate that government content or policy caused a particular public response.

### Automated Classification ≠ Ground Truth

NLP models can misclassify sarcasm, slang, ambiguous language, contextual expressions, and mixed sentiment.

These limitations are particularly important when analytical results concern public communication.

---

# Key Technical Challenge

### Challenge

TikTok comments contain noisy and highly informal language.

Common characteristics include:

- abbreviations,
- inconsistent spelling,
- slang,
- non-standard grammar,
- repeated characters,
- mixed expressions,
- and context-dependent meaning.

### Approach

The project applies a structured text-processing pipeline before classification:

```text
Raw Comment
     │
     ▼
Cleaning
     │
     ▼
Normalization
     │
     ▼
Text Preprocessing
     │
     ▼
Feature Extraction
     │
     ▼
Machine Learning
```

The objective is to reduce irrelevant textual noise while preserving information useful for sentiment classification.

---

# My Contribution

### Muhammad Wildan Nabila
**Data Analytics · NLP · Machine Learning**

My contribution covered the analytical workflow, including:

- TikTok comment data collection
- Data cleaning and preprocessing
- Exploratory Data Analysis
- NLP feature engineering
- Sentiment classification
- Six-model comparison
- Model evaluation
- Keyword analysis
- Analytical interpretation
- Insight generation
- Presentation and reporting

This project demonstrates the workflow from **raw social-media text to structured NLP analysis and interpretable communication insights**.

---

# Technology Ecosystem

<div align="center">

<img src="https://skillicons.dev/icons?i=python" height="48" alt="Python">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/numpy/013243" height="44" alt="NumPy">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/pandas/150458" height="44" alt="Pandas">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/scikitlearn/F7931E" height="44" alt="Scikit-learn">
&nbsp;&nbsp;&nbsp;
<img src="https://cdn.simpleicons.org/jupyter/F37626" height="44" alt="Jupyter">

<br><br>

`Python` · `Pandas` · `Scikit-learn` · `NLP` · `SVM` · `Matplotlib` · `WordCloud`

</div>

---

# Skills Demonstrated

<table>
<tr>
<td width="33%" valign="top">

**Natural Language Processing**

- Text Cleaning
- Text Preprocessing
- Feature Engineering
- Sentiment Analysis

</td>
<td width="33%" valign="top">

**Machine Learning**

- Multiclass Classification
- Model Benchmarking
- SVM
- Performance Evaluation

</td>
<td width="33%" valign="top">

**Data Analytics**

- Exploratory Analysis
- Social Media Analytics
- Keyword Exploration
- Insight Communication

</td>
</tr>
</table>

---

# Analytical Limitations

### 1 · Platform Representation

TikTok users and commenters are a self-selected population and should not be assumed to represent all Batu City residents.

### 2 · Accuracy-Only Comparison

The available benchmark reports model accuracy. Class-level Precision, Recall, F1, and confusion matrices would strengthen evaluation.

### 3 · Contextual Language

Sarcasm, slang, local expressions, and ambiguous comments can reduce sentiment-classification reliability.

### 4 · Keyword Interpretation

Word clouds visualize frequency but do not measure topic importance, sentiment toward a topic, or issue severity.

### 5 · Temporal Scope

Results describe the collected dataset and period rather than permanent public attitudes.

### 6 · No Causal Evaluation

The analysis does not establish whether government communication caused the observed sentiment.

---

# Future Development

The strongest extensions for this project include:

- Precision, Recall, and Macro F1 evaluation
- Confusion matrix analysis
- Cross-validation
- TF-IDF pipeline documentation
- IndoBERT comparison
- Aspect-Based Sentiment Analysis
- Topic modeling
- Topic coherence evaluation
- Temporal sentiment analysis
- Per-post sentiment analysis
- Sarcasm handling
- Indonesian slang normalization
- Interactive Streamlit dashboard
- Automated reporting
- Ethical social-media monitoring pipeline

A particularly valuable next step would be:

```text
SENTIMENT
How is the comment expressed?
      │
      ▼
ASPECT
What service is being evaluated?
      │
      ▼
TOPIC
What broader issue is discussed?
      │
      ▼
TIME
How is discussion changing?
      │
      ▼
COMMUNICATION INSIGHT
```

This would provide substantially richer information than polarity classification alone.

---

# Project Presentation

<div align="center">

[![View Presentation](https://img.shields.io/badge/CANVA-View%20Project%20Presentation-00C4CC?style=for-the-badge&logo=canva&logoColor=white)](https://canva.link/2twsf1ms0kozj70)

</div>

---

# Project Summary

| Dimension | Result |
|---|---|
| **Problem** | Government social-media sentiment analysis |
| **Source** | TikTok Comments |
| **Comments** | **1,647** |
| **Classes** | Positive · Neutral · Negative |
| **Positive** | **33.8%** |
| **Neutral** | **44.0%** |
| **Negative** | **22.2%** |
| **Models Compared** | **6** |
| **Highest Reported Accuracy** | **SVM — 79%** |
| **Additional Analysis** | Keyword Exploration |
| **Context** | Public-Sector Communication Analytics |

---

# Author

**Muhammad Wildan Nabila**  
Bachelor of Informatics · Universitas Muhammadiyah Malang

<div align="left">

![Data Science](https://img.shields.io/badge/Data%20Science-2563EB?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-7C3AED?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-DC2626?style=flat-square)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0F766E?style=flat-square)

</div>

---

<div align="center">

### TikTok Comments → NLP → Sentiment Patterns → Communication Insights

**Natural Language Processing · Machine Learning · Social Media Analytics · Public-Sector Analytics**

</div>
