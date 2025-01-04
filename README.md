# web-text-entity-recognition
This project showcases web scraping and natural language processing (NLP) using Python, BeautifulSoup, and SpaCy. The goal is to extract content from a news article and perform text analysis tasks, including named entity recognition (NER), token frequency analysis, sentence-level part-of-speech (POS) tagging, and data redaction.

**Project Features**
Web scraping to extract content from an online article using BeautifulSoup.
Named Entity Recognition (NER) to detect and label entities (e.g., PERSON, ORGANIZATION).
Token frequency analysis to display the most common words in the article.
Random selection of three consecutive sentences for POS tagging and lemmatization.
Visualization of named entities and syntactic dependencies.
De-identification of names (PERSON entities) by replacing them with [REDACTED].

**Technologies Used**
Programming Language: Python
Libraries:
BeautifulSoup (for web scraping)
SpaCy (for NLP tasks)
urllib.request (for URL handling)
