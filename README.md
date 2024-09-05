# Random Sentence Generation for NLP

## Overview

This repository contains a script for generating a dataset of random sentences tailored for Natural Language Processing (NLP) tasks. The script utilizes the Faker library to create realistic data for various entities such as names, cities, companies, emails, phone numbers, jobs, dates, times, and addresses. Additionally, it incorporates the NLTK library to replace words in sentences with their synonyms, increasing the dataset's variability.

## Features

- **Sentence Generation**: Produces random sentences with realistic data for different categories.
- **Synonym Replacement**: Enhances dataset variability by replacing words in sentences with their synonyms.
- **CSV Output**: Saves the generated sentences along with their labels in a CSV file, suitable for use in NLP models.

## Prerequisites

To run the script, you need the following libraries:

- `nltk`
- `Faker`
- `pandas`

You can install the required libraries using pip:

```bash
pip install nltk faker pandas
```

## Setup

1. **Download NLTK WordNet Data**

   Before running the script, you need to download the WordNet data required by the NLTK library. You can do this by running the following Python commands:

   ```python
   import nltk
   nltk.download('wordnet')
   ```

2. **Script Overview**

   The script is designed to generate sentences with the following steps:
   
   - **Data Generation Functions**: Functions to generate names, cities, companies, emails, phone numbers, jobs, dates, times, and addresses.
   - **Synonym Replacement**: Replaces words in sentences with their synonyms.
   - **Dataset Creation**: Generates sentences with associated labels (greet, query, task) and applies synonym replacements. The data is then saved into a CSV file.

## Usage

To generate the dataset, run the provided script. This will produce a CSV file named `dataset.csv` containing the generated sentences and their labels.

```bash
python script.py
```

## Files

- `script.py`: The main Python script that generates the dataset.
- `dataset.csv`: The output file containing the generated sentences and their labels.

## Example

The script generates sentences like:

- "Hello, I hope you're doing well. Can you tell me more about the new product?"
- "Please send me the email address and phone number at your convenience."

These sentences are then replaced with variations using synonyms, creating a diverse dataset for NLP tasks.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please open an issue or contact the repository maintainer.

Feel free to adjust any sections or add additional details specific to your project or use case.
