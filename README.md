# Covid-19 News Articles Analysis.

Analyze US news articles related to Covid-19. Also create a summrizer app using Flask which will summarize the Covid-19 new articles.

## Fetch Data
Data was fetched from [NewsApi](https://newsapi.org/docs/get-started). Articles were fetchedhed from 3rd March 2020 to 1st April 2020.

## Summarizer App
A Text Summarizer app was created using Flask, FlaskForm and HuggingFace Transformer's BART model. More about HuggingFace BART model can be found [here](https://huggingface.co/transformers/model_doc/bart.html)