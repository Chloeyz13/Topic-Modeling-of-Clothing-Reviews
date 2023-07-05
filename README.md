# Topic-Modeling-of-Clothing-Reviews

This readme file provides an overview of the topic modeling project and its key components. It serves as a guide to understand the project's purpose, methodology, and usage.

## Project Overview
The topic modeling project aims to uncover latent themes of Women's Clothing E-Commerce Reviews.

## Methodology
The project utilizes the Latent Dirichlet Allocation (LDA) algorithm, a popular topic modeling technique, to identify topics within the document corpus. LDA assumes that each document is a mixture of various topics, and each topic represents a distribution of words. By applying LDA, the project uncovers these latent topics and assigns topic probabilities to each document.

## Key Components
The project consists of the following key components:

1. **Set Up Pyspark**: Install nltk and download nltk stopwords.

2. **Text Processing**: Use nltk to decompose into sentences & sentences into tokens.

3. **Clean Data**: Remove useless text like emails, line characters, single quotes, punctuations, and empty strings.

4. **Make Bigrams and Lemmatize**: Install spacy, logging for lemmatization, and logging for gensim.

5. **Tag Words**: Tag all remaining words in the story as parts of speech using the [Penn POS Tags](https://stackoverflow.com/questions/15388831/what-are-all-possible-pos-tags-of-nltk/32336935#32336935).

6. **Build LDA Model**: Create a tag dictionary, create corpus, term document frequency, and then build a LDA model.

7. **Visualize topics**: Visualize a selected number of topics. Compute perplexity and coherence score. 

8. **Justifications and Questions**: Analyze the results.

## Environments

- Python 3.10.12
- Libraries:
  - spark 3.2.1
  - nltk 3.8.1
  - spacy 3.6.0
  - gensim 4.3.1
  - pyLDAvis 3.2.1

## Conclusion
The topic modeling project provides a powerful approach to uncover latent themes within a collection of textual data. By utilizing the LDA algorithm and following the outlined steps, we can gain valuable insights into the underlying topics present in their documents.

For more detailed information, refer to the project documentation or reach out to the project contributors.

Happy topic modeling!

Yiwen (Chloe) Shen

yiwenshenyz13@gmail.com
