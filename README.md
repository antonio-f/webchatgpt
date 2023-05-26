# Web ChatGPT

Create a web-based conversational bot powered by GPT. Based on Abhishek Thakur's [video](https://www.youtube.com/watch?v=T1hdz3eU3bg).

## Instructions

Create a Python environment including `scrapy`, `langchain`, `gradio`, `html2text`. Pip-install other possible missing dependencies.

1) Run terminal. At `hfcrawl` dir level, type `scrapy crawl huggingface`. Go back one level to `webchatgpt` and type `python index.py`.

WARNING: you need an API key from OpenAI site (see https://platform.openai.com/account/api-keys). Once the key is generated, copy it and type `export OPENAI_API_KEY=">>>INSERT_KEY_HERE<<<"`. 

2) After setting the key, type `python bot.py`, go to http://127.0.0.1:7860 and ask some question about diffusers.




