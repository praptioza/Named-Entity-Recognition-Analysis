# Named Entity Recognition Analysis

## Overview

🚀 Explore the world of Named Entity Recognition (NER) with Python! This project dives into four popular libraries - NLTK, spaCy, Hugging Face Transformers, and Stanza - to extract named entities from text data. By evaluating their performance on a set of 20 test cases, we gain insights into their accuracy, precision, and recall using micro-averaging. 

⚡ Spoiler alert: Hugging Face Transformers' NER pipeline steals the show with its top-notch performance.

## Libraries Used

🔹 **NLTK**: Natural Language Toolkit for various NLP tasks, including NER.
🔹 **spaCy**: Industrial-strength NLP library for Python.
🔹 **Hugging Face Transformers**: State-of-the-art NER models based on transformer architectures.
🔹 **Stanza**: A collection of accurate and efficient NLP tools.

## Performance Evaluation

The performance of each NER approach is evaluated using micro-averaging to calculate accuracy, precision, and recall. The results for each step are as follows:

### Results

🔹 **Prediction for Step 1** (Viterbi Algorithm & HMM):
  - Micro-average Accuracy: 0.4667
  - Micro-average Precision: 0.3061
  - Micro-average Recall: 0.3947

🔹 **Prediction for Step 2** (NLTK ne_chunk):
  - Micro-average Accuracy: 0.6533
  - Micro-average Precision: 0.3750
  - Micro-average Recall: 0.3158

🔹 **Prediction for Step 3** (spaCy nlp):
  - Micro-average Accuracy: 0.8133
  - Micro-average Precision: 0.7250
  - Micro-average Recall: 0.7632

🔹 **Prediction for Step 4** (Hugging Face Transformers NER):
  - Micro-average Accuracy: 0.8267
  - Micro-average Precision: 0.7568
  - Micro-average Recall: 0.7368

🔹 **Prediction for Step 5** (Stanza NER):
  - Micro-average Accuracy: 0.7467
  - Micro-average Precision: 0.6486
  - Micro-average Recall: 0.6316

## Conclusion

Designed a high-accuracy NER system, optimizing entity extraction and reducing processing time. 

⚡ Achieved 83% accuracy by implementing machine learning-based NER approaches, with Hugging Face Transformers delivering the best performance.

## Installation

1. Clone the repository:
   git clone https://github.com/praptioza/Named-Entity-Recognition-Analysis.git

2. Navigate to the project directory:
   cd Named-Entity-Recognition-Analysis

3. Install the required libraries:
   pip install -r requirements.txt

4. Run the analysis:
   python main.py

