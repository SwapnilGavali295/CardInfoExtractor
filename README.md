# Contact Card Entity Extraction

This project aims to extract specific details such as names, phone numbers, emails, job titles, company names, and addresses from unstructured text data scanned from contact cards using OCR. The extraction process utilizes a combination of Regular Expressions (RE) and Natural Language Processing (NLP) techniques.

## Features

- **Extracts Key Entities**: Detects names, phone numbers, emails, websites, company names, job titles, and addresses.
- **Utilizes NLP Libraries**: Includes support for NLTK, spaCy, and Flair for Named Entity Recognition (NER).
- **Custom Filtering for Indian Names**: Uses a list of 10,000 common English words to improve the accuracy of detecting names in an Indian context.
- **Regex-Based Extraction**: Simple and effective regular expressions to identify patterns in phone numbers, emails, and addresses.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Libraries:
  - `pandas`
  - `nltk`
  - `spacy`
  - `flair`
  - `re`
  - `WordNetLemmatizer`

Install necessary libraries using:

```bash
pip install pandas nltk spacy flair

