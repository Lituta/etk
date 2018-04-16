# ETK: Information Extraction Toolkit

ETK is a Python library for high precision information extraction from many document formats.
It proivdes a flexible framework of **composable extractors** that enables you to combine a host of **predefined extractors** provided in ETK with custom extractors that you may need to develop for your application.
It supports extraction from HTML pages, text documents, CSV and Excel files and JSON documents.
ETK is open-source software, released under the MIT license.

![travis ci](https://travis-ci.org/usc-isi-i2/etk.svg?branch=etk2)

## Documentation


## Features

* Extraction from HTML, text, CSV, Excel, JSON
* High-precision predefined extractors for common entities (dates, phones, email, cities, ...)
* Extraction of microdata, schema.org and RDFa markup
* Integration with [spaCy](https://github.com/explosion/spaCy) for text processing
* Automatic identification and extraction of HTML tables containing data
* Automatic identification and extraction of time series
* Semi-automatic generation of Web wrappers
* Scalable execution and management of extraction pipelines

## Installation

<table>
  <tr><td><b>Operating system:</td><td>macOS / OS X, Linux, Windows</td></tr>
  <tr><td><b>Python version:</td><td>Python 3.6+</td></tr>
<table>

Clone or fork this repository, open a terminal window and in the directory where you downloaded ETK type the following commands:
```
conda-env create .
source activate etk2_env
python -m spacy download en_core_web_sm
```

## Run Tests

`python -m unittest discover`
