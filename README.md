# Script Generator Using Generative-AI

## Description

The Script Analysis and Generation project is designed to scrape, preprocess, analyze, and generate text based on TV show scripts. This project utilizes various libraries for web scraping, data preprocessing, exploratory data analysis, and language model training. The final output is a fine-tuned GPT-2 model capable of generating script-like text based on given prompts.

## Features

-   **Data Scraping and Cleaning:** Fetches and preprocesses script content from specified URLs.
-   **Exploratory Data Analysis:** Analyzes the frequency of words and generates visualizations such as bar charts and word clouds.
-   **Data Preparation:** Tokenizes and pads text data for model training.
-   **Model Building:** Fine-tunes a GPT-2 model on the preprocessed script data.
-   **Text Generation:** Generates script-like text using the fine-tuned GPT-2 model.

## Installation

### Prerequisites

-   Python 3.7+
-   Jupyter Notebook
-   Required Python libraries (see below)
	- Requests
	- BeautifulSoup
	- re
	- nltk
	- plotly
	- collections
	- pandas
	- wordcloud
	- matplotlib
	- tensorflow
	- transformers

### Setup

1.  **Clone the Repository**
    
    ```bash
    git clone https://github.com/ananyamanjunath/Script-Generator-Using-Generative-AI.git
    cd Script-Generator-Using-Generative-AI
    ```
  
    
2.  **Run the Jupyter Notebook**
    
    ```bash
    jupyter notebook code.ipynb
    ```
  
    

## Warning Note

Please note that the script data is scraped from external sources and may contain errors or inconsistencies. Ensure to review and clean the data as necessary before using it for analysis or model training.

