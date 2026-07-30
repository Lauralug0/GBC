# GBC — Applied Machine Learning & NLP Portfolio

A collection of applied machine learning, NLP, and computer vision notebooks
from coursework at George Brown College, kept here as a portfolio of
independent technical work.

## Notebooks

Two of the stronger pieces from this coursework have their own standalone
repos:

- **[ResumeMatchingTransformer](https://github.com/Lauralug0/ResumeMatchingTransformer)** — fine-tunes DistilBERT to match resumes against job descriptions
- **[PrescriptionParserCRF](https://github.com/Lauralug0/PrescriptionParserCRF)** — CRF-based sequence labeling to parse doctor's prescriptions

| Notebook | Description |
|---|---|
| [`news_topic_modeling.ipynb`](notebooks/news_topic_modeling.ipynb) | Extracts topics from news documents using matrix factorization / SVD-based topic modeling. |
| [`text_classification_nlp.ipynb`](notebooks/text_classification_nlp.ipynb) | Compares NLP feature extraction methods (CountVectorizer, TF-IDF) for text classification. |
| [`auto_feature_selector.ipynb`](notebooks/auto_feature_selector.ipynb) | An automated feature-selection tool combining multiple selection methods on a real-world dataset. |
| [`real_estate_price_prediction.ipynb`](notebooks/real_estate_price_prediction.ipynb) | Linear regression model predicting real estate prices, with exploratory analysis and evaluation. |
| [`image_thresholding.ipynb`](notebooks/image_thresholding.ipynb) | Applies and compares image-thresholding techniques for computer vision preprocessing. |

## Repo structure

```
GBC/
├── README.md
├── requirements.txt
├── .gitignore
└── notebooks/
    ├── news_topic_modeling.ipynb
    ├── text_classification_nlp.ipynb
    ├── auto_feature_selector.ipynb
    ├── real_estate_price_prediction.ipynb
    └── image_thresholding.ipynb
```

## Running

Each notebook is self-contained and was originally developed in Google Colab
(each includes an "Open in Colab" badge). To run locally:

```bash
git clone https://github.com/Lauralug0/GBC.git
cd GBC
pip install -r requirements.txt
jupyter notebook notebooks/
```

Some notebooks load their dataset from Google Drive or a Colab file upload
cell — when running locally, replace that cell with a local path to the
dataset referenced in the notebook's markdown.

## Author

Laura Lugo — George Brown College
