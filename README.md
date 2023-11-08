# Word Correction using Python's TextBlob Package

## Introduction

This repository contains a Python script that demonstrates how to perform word correction and text processing using the TextBlob package. TextBlob is a simple and powerful Python library for processing textual data. It provides a convenient API for diving into common natural language processing (NLP) tasks, including spell correction, sentiment analysis, and more.

In this script, we focus on word correction, where we input a text with possible spelling mistakes, and TextBlob will attempt to correct these mistakes automatically.

## Prerequisites

Before running the script in this repository, you will need to have the following installed:

- Python 3 (https://www.python.org/downloads/)
- TextBlob package (install using `pip install textblob`)
- nltk corpora (install using `python -m textblob.download_corpora`)

## Getting Started

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/AdadAlShabab/Word-Correction-Using-TextBlob-Package.git
   ```

2. Navigate to the project directory:

3. Install the required Python packages:

   ```bash
   pip install textblob
   python -m textblob.download_corpora
   ```

4. Run the `word_correction.py` script to see TextBlob in action:

   ```bash
   python textblob.py
   ```

## Example

For example, if you have the following text:

```
Ecam
```

The script will correct it to:

```
Exam
```

## Acknowledgments

- [TextBlob](https://textblob.readthedocs.io/en/dev/) - The Python library used for word correction and text processing.

Feel free to explore, modify, and extend this script for your own NLP tasks. If you encounter any issues or have suggestions for improvements, please create an issue or a pull request.
