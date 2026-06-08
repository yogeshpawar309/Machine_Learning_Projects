# Project: Wikipedia Text Preprocessing Pipeline

In this project, I developed a complete NLP preprocessing pipeline using Wikipedia articles from four domains: Artificial Intelligence, Climate Change, Space Exploration, and Famous Scientists. The objective was to transform raw textual data into a machine-learning-ready format while understanding each preprocessing stage and its impact on the dataset.

The project began with automated data collection using web scraping techniques. A total of 60 articles were collected and stored with category labels. The raw text was then cleaned by removing citations, punctuation, extra spaces, and converting all text to lowercase. After cleaning, tokenization was applied to split text into individual words. Stopword removal reduced noise by eliminating common words that contributed little semantic value.

To compare normalization techniques, both stemming and lemmatization were implemented. While stemming produced shorter word roots, lemmatization generated more meaningful dictionary words, making it more suitable for downstream NLP tasks. The processed tokens were then joined to create a final clean text column.

Finally, TF-IDF vectorization was used to convert text into numerical features. This enabled identification of the most important terms within each category and prepared the dataset for future machine learning applications such as text classification.

One interesting insight was that Space Exploration articles consistently contained highly specialized vocabulary, resulting in distinct TF-IDF features. A surprising learning experience was observing how aggressively stemming can distort words compared to lemmatization, even though both aim to reduce word variations.

This project strengthened my understanding of end-to-end text preprocessing workflows in Natural Language Processing
