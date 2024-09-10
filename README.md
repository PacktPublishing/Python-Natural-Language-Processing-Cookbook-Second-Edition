# Python Natural Language Processing Cookbook, Second Edition


<a href="https://www.packtpub.com/en-us/product/python-natural-language-processing-cookbook-9781803245744"><img src="https://m.media-amazon.com/images/I/61vHwjtkrxL._SL1360_.jpg" alt="Python Natural Language Processing Cookbook" height="256px" align="right"></a>

This is the code repository for [Python Natural Language Processing Cookbook, Second Edition](https://www.packtpub.com/en-us/product/python-natural-language-processing-cookbook-9781803245744), published by Packt.

**Over 60 recipes for building powerful NLP solutions using Python and LLM libraries**

## What is this book about?

Master NLP through practical recipes in this second edition of Python Natural Language Processing Cookbook that expands on data preparation and modeling, and delves into transformer models, GPT-4, NLU, and XAI for advanced NLP tasks.

This book covers the following exciting features: 
* Understand fundamental NLP concepts along with their applications using examples in Python
* Classify text quickly and accurately with rule-based and supervised methods
* Train NER models and perform sentiment analysis to identify entities and emotions in text
* Explore topic modeling and text visualization to reveal themes and relationships within text
* Leverage Hugging Face and OpenAI LLMs to perform advanced NLP tasks
* Use question-answering techniques to handle both open and closed domains
* Apply XAI techniques to better understand your model predictions

If you feel this book is for you, get your [copy](https://www.amazon.com/Python-Natural-Language-Processing-Cookbook/dp/1803245743/ref=tmm_pap_swatch_0?_encoding=UTF8&sr=8-2) today!


## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```python
from transformers import T5Tokenizer, T5ForConditionalGeneration
import torch
device = torch.device("cuda" if torch.cuda.is_available() else "cpu")
```

**Following is what you need for this book:**
This updated edition of the Python Natural Language Processing Cookbook is for data scientists, machine learning engineers, and developers with a background in Python. Whether you’re looking to learn NLP techniques, extract valuable insights from textual data, or create foundational applications, this book will equip you with basic to intermediate skills. No prior NLP knowledge is necessary to get started. All you need is familiarity with basic programming principles. For seasoned developers, the updated sections offer the latest on transformers, explainable AI, and Generative AI with LLMs.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  	1-10	   | Python 3.10                       | Windows, macOS, or Linux|
|  	1-10	   | Poetry                     | Windows, macOS, or Linux|
|  	1-10	   | Jupyter Notebook (optional)                      | Windows, macOS, or Linux|

### Related products <Other books you may enjoy>  
* Mastering NLP from Foundations to LLMs  [[Packt]](https://www.packtpub.com/en-us/product/mastering-nlp-from-foundations-to-llms-9781804619186?type=print) [[Amazon]](https://www.amazon.com/Mastering-NLP-Foundations-LLMs-Techniques/dp/1804619183/ref=sr_1_1?sr=8-1)

* Generative AI Foundations in Python [[Packt]](https://www.packtpub.com/en-us/product/generative-ai-foundations-in-python-9781835460825?type=print) [[Amazon]](https://www.amazon.com/Generative-Foundations-Python-techniques-challenges/dp/1835460828/ref=sr_1_1?sr=8-1)
  
## Get to Know the Authors
**Zhenya Antić** is an expert in AI and NLP. Currently she is the Director of AI Automation at Arch , leading initiatives in Intelligent Document Processing, applying various AI solutions to complex problems. She has worked on various NLP projects with many different companies through her consulting experience. Zhenya has a Ph.D. in Linguistics from University of California-Berkeley and a B.S in Computer Science from Massachusetts Institute of Technology.

**Saurabh Chakravarty** is a seasoned professional with expertise in NLP and large-scale distributed systems. He presently works with AWS as an SDE, where he is always looking to leverage ideas on how NLP and its associated technologies can be used in diverse ways to solve problems in other software engineering domains. Saurabh has a master's degree and Ph.D. from Virginia Tech, specializing in NLP and deep learning.
