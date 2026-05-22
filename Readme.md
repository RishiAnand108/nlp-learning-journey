# NLP Learning Journey

A complete hands-on repository for learning and practicing Natural Language Processing (NLP) concepts using Python.

This repository contains practical notebooks and implementations of important NLP concepts such as:
- Tokenization
- Stemming
- Lemmatization
- Bag of Words
- Spam Classification
- Text Preprocessing
# NLP Learning Journey

A hands-on collection of Jupyter notebooks and small projects to learn and practice Natural Language Processing (NLP) with Python.

This repository contains practical notebooks and example implementations for common NLP tasks including:
- Tokenization
- Stemming
- Lemmatization
- Bag of Words (BoW)
- SMS spam classification
- Text preprocessing

## Tech stack

- Python 3.8+ (or compatible)
- NLTK
- scikit-learn
- pandas
- NumPy
- Jupyter Notebook

## Project structure

Example layout (files may vary):

```
NLP/
├── 3-Lemmatization-Text Preprocessing.ipynb
├── 4-Text Preprocessing-Stopwords With NLTK.ipynb
├── 5-Parts of Speech Tagging.ipynb
├── 6-named entity Recognition.ipynb
├── Bag of Words Practicals.ipynb
├── Tokenization Example.ipynb
├── Stemming And Its Types-Text Preprocessing.ipynb
├── SpamClassifier-master/
│   └── SMSSpamCollection
├── requirements.txt
└── Readme.md
```

## Topics covered

- Tokenization: sentence and word tokenization, basic preprocessing
- Stemming: Porter, Snowball, Lancaster and comparison
- Lemmatization: POS-aware lemmatization and normalization
- Bag of Words: CountVectorizer and feature extraction
- Spam classification: SMS preprocessing and a simple ML pipeline

## Installation

1. Clone the repository (replace <repo-url> with the repository URL):

```bash
git clone https://github.com/RishiAnand108/nlp-learning-journey
```

2. Change to the project directory (adjust the folder name if different):

```bash
cd NLP
```

3. Create and activate a virtual environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate
```

4. Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the notebooks

Start Jupyter Notebook or JupyterLab and open the notebooks in the repository:

```bash
jupyter notebook
# or
jupyter lab
```

Open any notebook and run the cells step by step. Some notebooks expect the datasets to be present in the repository (for example, the `SpamClassifier-master/SMSSpamCollection` file).

## Learning outcomes

After working through these notebooks you should be comfortable with:

- Basic NLP preprocessing (tokenization, stopword removal, normalization)
- Transforming text into numeric features (BoW / CountVectorizer)
- Building and evaluating a simple text classification model
- Applying stemming and lemmatization and understanding the differences

## Future improvements

- Add TF–IDF vectorization examples
- Add Word2Vec (or other word embeddings) examples
- Add a sentiment analysis notebook
- Add transformer-based examples (Hugging Face / transformers)
- Provide a small web demo (Streamlit or Flask) to serve models

## Contributing

Contributions are welcome. If you'd like to contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes and open a pull request

Please include clear descriptions and, when applicable, tests or example notebooks.

## Author

Rishikesh Prasad

---

If you'd like, I can also:
- Add a short badge header (Python version / license)
- Fix or standardize notebook filenames
- Create a minimal example script to run the spam classifier from the command line

Tell me which of the above (if any) you'd like me to do next.