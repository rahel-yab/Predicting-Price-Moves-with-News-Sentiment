## Predicting Stock Price Moves with News and Analyst Sentiment

## Project Overview

This project aims to build a data science pipeline to investigate the correlation between market-moving textual data (news headlines) and analyst ratings with subsequent daily stock returns. The ultimate goal is to quantify the impact of sentiment on stock price movements.

## 🚀 Getting Started
These instructions will get a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
This project requires Python 3.8+ and uses a virtual environment for dependency management.

 ### Clone the Repository:

```bash

git clone https://github.com/your-username/your-repo-name.git
cd predicting-price-moves
```
 ### Create & Activate Virtual Environment:
```bash
python3 -m venv venv
source venv/bin/activate
If you use Anaconda, use: conda create -n sentiment-env python=3.10
```

### Install Dependencies:

```bash
pip install -r requirements.txt
NLTK Data Setup: The project uses NLTK for text processing. You must download the required stopwords data package once:
```
```python
import nltk
nltk.download('stopwords')
```
