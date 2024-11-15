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
pip install pandas nltk spacy flair


## Files

- **top10k.txt**: Contains the 10,000 most common English words, used to filter non-English terms.
- **jobs.txt**: A list of common job titles, used to identify job-related terms in the data.
- **MyContacts(1).xlsx**: A sample Excel file with OCR-scanned data, where parsed text data should be placed in the `parsedTxt` column for processing.

## Installation

To set up the environment and dependencies, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/contact-card-entity-extraction.git
   cd contact-card-entity-extraction
