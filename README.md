
# Emotion Detection in Text

## Project Overview

Emotion Detection in Text is an NLP and Machine Learning project that identifies emotions from textual data. The project processes text, extracts relevant features, and applies different machine learning algorithms to classify emotions.

## Objectives

- Analyze textual data to identify emotional patterns.
- Perform text preprocessing and cleaning.
- Extract text features using CountVectorizer.
- Train and evaluate different Machine Learning models.
- Predict emotions from input text.

## Dataset

The project uses the `Emotion_final.csv` dataset containing two columns:

- **Text:** Input text.
- **Emotion:** Corresponding emotion label.

The dataset contains six emotion categories:

- Happy
- Sadness
- Anger
- Fear
- Love
- Surprise

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLP
- TextBlob
- NeatText
- Scikit-learn
- WordCloud
- CountVectorizer

## Machine Learning Algorithms

The following algorithms are implemented and evaluated:

1. Multinomial Naive Bayes
2. K-Nearest Neighbors (KNN)
3. Support Vector Classifier (Linear SVC)
4. Support Vector Classifier (RBF SVC)

## Project Structure

```text
Emotion-Detection-in-Text/
│
├── README.md
├── requirements.txt
├── .gitignore
├── notebook/
│   └── Emotion_from_Text.ipynb
└── dataset/
    └── Emotion_final.csv
```

## Model Performance

| Algorithm | Accuracy |
|---|---:|
| Multinomial Naive Bayes | 78.31% |
| KNN | 59.44% |
| Linear SVC | 88.61% |
| RBF SVC | 32.34% |

Linear SVC achieved the highest test accuracy among the evaluated models.

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/YOUR-USERNAME/Emotion-Detection-in-Text.git
```

2. Navigate to the project folder.

```bash
cd Emotion-Detection-in-Text
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Open the notebook.

```bash
jupyter notebook
```

5. Open `Emotion_Detection_in_Text.ipynb` and run the cells.

## Project Outcome

This project demonstrates how Natural Language Processing and Machine Learning techniques can be used to analyze text and classify emotions.

---
**Developed as an NLP and Machine Learning project.**
