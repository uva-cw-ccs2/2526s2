# Tutorial exercises week 1: Working with textual data

# Instructions

In this assignment, you will work with textual data, focusing on dataset structure, processing, and basic analysis techniques. You will inspect the dataset, discuss research questions, and implement fundamental preprocessing steps such as tokenization, stopword removal, and stemming.

## Questions 

### 1. Get the data and read the data in. 

Download `Vox_articles.csv` from Canvas (under Week 1, [Dataset tutorial](https://canvas.uva.nl/courses/57659/pages/dataset-tutorial)).

This dataset contains articles from *Vox News*. Read it into Python using **pandas**.


### 2. Tokenization

-   What is tokenization, and why is it useful in text processing?
-   Implement a basic tokenization process using Python.

*Hint*: You can use `nltk.word_tokenize()` or Python's built-in `split()` method.

### 2. Stopword removal

-   Why is it beneficial to remove stopwords in text analysis?
-   Implement a method to remove stopwords from a tokenized text sample.

*Hint*: NLTK provides a built-in list of stopwords in multiple languages.
