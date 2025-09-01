# Digital Humanities 2025 - Thesis Project Repository - Echoes of the Mockingjay
## About this Project
This thesis project explores how fans on tumblr in _The Hunger Games_ fandom (excluding the prequels) talk about the narrative's characters. After participant observation and fieldwork followed by a close analysis of my own posts and posting habits, I began my second phase - computational analysis.
This involves the use of Python, specifically via Jupyter notebooks, to scrape and collect posts, preprocess the text and tags, filter out the irrelevant material (as much as possible), and organize them. 
After that, I did the following:
- Frequency analysis of tags
- Using Riveter, a Python tool, to run linguistic and sentiment analyses on the corpus

## Contents:
1. This README.md file
2. __personal_tumblr_archive.ipynb__ - A Jupyter notebook to compile, explore, and analyse your personal tumblr blog.
3. __thg_fandom_corpus_analysis.ipynb__ - A Jupyter notebook to build an expansive corpus and preprocess it to conduct a similar analysis or adapt for your own purposes.
   
## How to Use this Repository
Steps:
1. Follow the instructions on <a href = 'https://www.tumblr.com/docs/en/api/v2'>Tumblr's API documentation page </a> to get an API key. The keys and tokens are required to use Tumblr's API Python Library.  
2. Follow the instructions at <a href = 'https://github.com/maartensap/riveter-nlp'>this link</a> to install and set up your Jupyter notebook for Riveter.
3. Download and run __personal_tumblr_archive.ipynb__ 
4. Download and run __thg_fandom_corpus_analysis.ipynb__ and run to compile a corpus to conduct tag frequency analysis, and computational linguistic and sentiment analysis using Riveter.

__NOTE for troubleshooting Riveter:__ Move all files into the directory .../riveter-nlp/riveter if Jupyter is having difficulty importing or installing a module.
