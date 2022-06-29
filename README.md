# TextSummarizer
Get Summary from large text using nltk

To install stopwords from nltk library, run below in python env

import nltk
import ssl

try:
    _create_unverified_https_context = ssl._create_unverified_context
except AttributeError:
    pass
else:
    ssl._create_default_https_context = _create_unverified_https_context

nltk.download()
