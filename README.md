### Term Article Summary

#### Installation

`pip install term_article_summary`

### Source

### Installation

#### Clone the repository

`git clone https://github.com/ayushsubedi/term-article-summary`

#### CD into the cloned directory and create a virtualenv

`python -m venv env`

### Enable virtualenv

`.\env\Scripts\activate`

### Install dependency packages from requirements.txt

`pip install -r requirements.txt`

### Run the app

`python term_article_summary.py --url=https://abc.xyz --ratio=0.5 --algorithm=bert`

Usage: term_article_summary.py [OPTIONS]

```
Options:
  --url TEXT                      Enter a valid URL
  --ratio FLOAT                   Ratio to summarize to.
  --algorithm [gensim|spacy|bert]
                                  Algorithm to use
  --help                          Show this message and exit.
```
