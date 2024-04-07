# my_mr_clean

## Overview

`my_mr_clean` is a Python script designed to retrieve content from Wikipedia, clean and tokenize the content, and perform basic text analysis tasks such as counting word frequencies and visualizing them in histograms. It also includes functionality to remove stop words from the text and visualize the most relevant words in the content.

## Features

- Retrieve content from Wikipedia using the MediaWiki API.
- Clean the retrieved content by removing markup, URLs, and non-alphabetic characters.
- Tokenize the cleaned content into individual words.
- Count the frequency of each word in the tokenized content.
- Print the most frequent words along with their frequencies.
- Visualize the most frequent words in a histogram.
- Remove stop words to focus on the most relevant words in the content.
- Visualize the most relevant words in a histogram.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/my_mr_clean.git
   ```

2. Navigate to the project directory:

   ```bash
   cd my_mr_clean
   ```


## Usage

1. Open the `my_mr_clean.ipynb` file in your preferred text editor.
2. Run the script:

   ```bash
   python3 my_mr_clean.py
   ```

## Dependencies

- `requests`: for making HTTP requests to the Wikipedia API.
- `matplotlib`: for data visualization, specifically for creating histograms.

## License

![Qwasar Logo](https://example.com/qwasar-icon.png)
