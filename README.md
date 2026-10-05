# Natural Language Processing: Practical Work

Practical work (TPs) for the Natural Language Processing module, implemented in Python with Jupyter notebooks and scripts.

## Repository structure

```
.
├── Documents/         # Text documents and data used by the labs
├── TP1/               # Practical work 1
├── TP2/               # Practical work 2
├── TP3/               # Practical work 3
├── TP4-5/             # Practical work 4 and 5
├── TP6/               # Practical work 6
├── TP8/               # Practical work 8
├── Test/              # Test files
├── requirements.txt   # Python dependencies
└── README.md
```

## Tech stack

| Library | Purpose |
|---------|---------|
| `nltk` | Text processing and NLP toolkit |
| `scikit-learn` | Vectorization and machine learning |
| `pandas`, `numpy` | Data manipulation and numerical computation |
| `matplotlib`, `wordcloud` | Visualizations and word clouds |
| `requests`, `beautifulsoup4`, `lxml` | Web requests and HTML/XML parsing |
| `selenium`, `webdriver_manager` | Browser automation for web scraping |
| `streamlit` | Interactive web apps |
| `ipykernel` | Jupyter notebook support |

## Getting started

```bash
git clone https://github.com/sarahmoussaoui/Natural-Language-Processing-Practical-Work.git
cd Natural-Language-Processing-Practical-Work

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

Some NLTK features need extra resources. Download the ones you need from a Python shell:

```python
import nltk
nltk.download("punkt")
nltk.download("stopwords")
```

## Usage

Each practical work lives in its own folder. Open the folder and run its notebooks (with Jupyter or VS Code) or its Python scripts. Streamlit apps are launched with:

```bash
streamlit run your_app.py
```

Selenium-based scrapers need Google Chrome installed; `webdriver_manager` downloads the matching driver automatically.
