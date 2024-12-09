# Finite-Automata-Based-Mental-Health-Monitoring-System-Monitoring-Stress-Anxiety-Patterns-

# Automata-Based Mental Health Monitoring System

This repository contains the implementation of an **Automata-Based Mental Health Monitoring System**, a comparative analysis between **Finite Automata (FA)** and **Pushdown Automata (PDA)** for detecting mental health conditions such as stress, anxiety, depression, and suicidal tendencies.

## Overview

The project leverages automata theory to classify mental health states by analyzing text data. It demonstrates how FA can recognize straightforward patterns, while PDA, with stack-based memory, excels in identifying complex, context-sensitive behaviors.

### Key Features
- **Finite Automata (FA)** for simpler, linear mental health state transitions.
- **Pushdown Automata (PDA)** for handling recursive and context-sensitive patterns.
- **Logistic Regression** classifier with TF-IDF text vectorization.
- Performance metrics like accuracy, F1-score, and confusion matrix.
- Visualization of transition diagrams for both FA and PDA.
- Comparative analysis of execution time, memory usage, and classification performance.

## Dataset
The system uses a dataset containing mental health-related statements labeled with their respective statuses (e.g., "Anxiety," "Normal," "Depression," etc.). The text is vectorized using TF-IDF to extract meaningful features.

## Results
- The PDA model outperforms FA in accuracy and F1-score, showcasing its ability to handle complex classification tasks.
- DFA Accuracy: **85%**
- PDA Accuracy: **92%**

## Repository Structure

├── src/ │ ├── dfa_implementation.py # DFA model implementation │ ├── pda_implementation.py # PDA model implementation │ ├── utils.py # Helper functions for data preprocessing and visualization ├── data/ │ ├── mental_health_dataset.csv # Dataset used for training and evaluation ├── results/ │ ├── dfa_transition_diagram.png # DFA transition diagram │ 
├── pda_transition_diagram.png # PDA transition diagram │ ├── confusion_matrix.png # Confusion matrix visualization ├── README.md # Project documentation ├── requirements.txt # Python dependencies


## Installation
1. Clone the repository:
   ```bash
https://github.com/vais05/Finite-Automata-Based-Mental-Health-Monitoring-System-Monitoring-Stress-Anxiety-Patterns-


