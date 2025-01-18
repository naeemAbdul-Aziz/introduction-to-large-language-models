# Quick Introduction to Large Language Models

This repository contains a Jupyter notebook that provides a quick introduction to working with Large Language Models (LLMs) using the LangChain library, OpenAI API, and HuggingFace Hub. The notebook is designed to showcase the basic functionality of LLMs, including text generation, prompt engineering, and few-shot learning techniques.

## Table of Contents

- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Examples](#examples)
- [Dependencies](#dependencies)
- [License](#license)

## Features

- Integration with OpenAI's GPT-based models.
- Prompt engineering with `PromptTemplate` and `FewShotPromptTemplate`.
- Example-based learning for custom and humorous responses.
- Working with HuggingFace's Flan-T5 model via the HuggingFace Hub.
- Efficient token utilization monitoring via OpenAI callbacks.

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/naeemAbdul-Aziz/introduction-to-large-language-models.git
   cd introduction-to-large-language-models

2. Install required dependencies:
   pip install -r requirements.txt

   Alternatively, install directly within the notebooks:
   !pip install -q langchain==0.0.208 openai python-dotenv huggingface_hub

3.Set up your API keys for OpenAI and HuggingFace and add them to a .env file as follows:
OPENAI_API_KEY='<your_openai_api_key>'
HUGGINGFACEHUB_API_TOKEN='<your_huggingface_hub_api_token>'
Usage
Open the notebook in Google Colab or a local Jupyter environment.
Ensure your .env file is configured correctly with the API keys.
Run each cell to explore how to interact with LLMs for generating responses and solving queries.
Opening in Google Colab
Click the badge below to open the notebook directly in Google Colab:

Open in Google Colab
[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/your-notebook-link](https://colab.research.google.com/drive/1DRpBmq6i8fREqIWItHdpjECdYoPWNrIP?usp=sharing))

Dependencies
Python 3.x
langchain==0.0.208
openai
python-dotenv
huggingface_hub




