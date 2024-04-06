# Web Mining and Applied NLP (44-620)

## Final Project: Article Summarizer

### Student Name: Naiema Elsaadi
<b>
The project aims to assist users in quickly understanding the sentiment of articles and identifying key information without having to read the entire text. It can be useful for researchers, journalists, and anyone interested in understanding the emotional content of written text.</b>

## Introduction
<b>
The project is a Python-based text analysis tool that performs sentiment analysis on articles retrieved from online sources. It utilizes natural language processing (NLP) techniques to analyze the sentiment of articles and provides insights into the emotional tone of the text.</b>


### Key features of the project include:

* Retrieving articles from specified URLs.
* Parsing the HTML content of articles and extracting the main text.
* Analyzing the sentiment of the text using both token-based and lemma-based approaches.
* Generating histograms to visualize the distribution of sentiment scores.
* Summarizing articles based on their sentiment scores, providing concise summaries of the main points.

## Objectives
<b>The primary objective of this project is to apply web mining and natural language processing (NLP) skills to develop a text analysis tool. The project aims to achieve the following goals:</b>


1. API Integration: Explore options for integrating with web APIs to fetch articles from online sources dynamically. This allows users to analyze content from a variety of sources, enhancing the versatility and usability of the tool.

2. Sentiment Analysis: Utilize NLP techniques to analyze the sentiment of articles and quantify the emotional tone of the text. This involves determining polarity scores that indicate whether the sentiment of the text is positive, negative, or neutral.


3. Text Corpus Analysis: Gather text corpus data from online sources and analyze the frequency of words to identify common themes or topics. This involves processing large volumes of text data to extract meaningful insights and trends.

4. Visualization: Implement visualization techniques to present the analysis results in a clear and intuitive manner. This includes generating histograms, word clouds, and other visualizations to help users understand the data more effectively.

5. Article Summarization: Implement algorithms to automatically generate concise summaries of articles retrieved from online sources. This involves extracting key information and significant insights from the text to provide users with a condensed version of the content.
<br></br><b>
By achieving these objectives, the project aims to provide a valuable tool for data analysts, researchers, journalists, and content creators to analyze and extract insights from textual data efficiently and effectively. Additionally, the project serves as a unique addition to the developer's online portfolio, showcasing their skills and capabilities in web mining and NLP.</b>


## Prerequisites
Before running the project, ensure you have the following prerequisites:

- Git
- Github
- Python 3.10+ installed
- VS studio Code
- juypterlab
- anaconda prompt (miniconda3) or windows PowerShell
- Required Python libraries (e.g., numpy) installed in your active environment

## Getting Started

- Before we begin, make sure you have the necessary dependencies installed in your Python environment. 
- If you haven't already, you'll need to install spaCy and spaCy NLP  using the following command:
<br>`python -m pip install beautifulsoup4`
<br>`python -m pip install html5lib`
<br>`python -m pip install requests`
<br>`python -m pip install spacy`
<br>`python -m pip install spacytextblob`



## Before we start 

- Create and activate a Python virtual environment. 
- Address any errors you get running this code cell by installing the necessary packages into your active Python environment.
- Before starting the project, try all these imports FIRST
<br>`from collections import Counter`
<br>`import pickle`
<br>`import requests`
<br>`import spacy`
<br>`from bs4 import BeautifulSoup`
<br>`import matplotlib.pyplot as plt`
<br>`!pip list`
<br>`print('All prereqs installed.')`

### Modules
<b>The following modules are required for the installation of this project:</b>
* import requests
* from bs4 import BeautifulSoup
* import pickle
* import spacy
* from spacytextblob.spacytextblob import SpacyTextBlob
* from textblob import TextBlob
* import numpy as np
* import pandas as pd
* import matplotlib.pyplot as plt


## Installation

Instructions for installing any dependencies or software needed to run the project.
Include commands for installing packages or setting up environments.
To use the notebooks in this repository, follow these steps:

1. Clone the repository to your local machine:
git clone Repo
2. Navigate to the project directory:
cd file
3. Create a virtual environment (optional but recommended):
python -m venv venv
4. Activate the virtual environment:
 For Windows:
venv\Scripts\activate
5. Install the required packages:
pip install -r requirements.txt
6. Launch Jupyter Lab:
jupyter lab
7. Open the desired notebook and execute the code cells.


## Data Source 

The source of the repository for this project is available at:[GitHub Repository](https://github.com/wmnlp-materials/article-summarizer)


## Contact

For any questions, feedback, or inquiries, you can reach out to me via  [My GitHub Repository](https://github.com/NaiemaElsaadi/article-summarizer-Final-Project)


## Acknowledgments

Special thanks to the Web Mining and Applied NLP (44-620) course instructor Dr. Case for her guidance and support throughout the project.

## Reference
https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start
https://github.com/denisecase/620-mod6-web-scraping
https://github.com/denisecase/620-mod6-web-scraping/blob/main/web_scraping.ipynb








































