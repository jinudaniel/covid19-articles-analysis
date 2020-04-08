# Covid-19 News Articles Analysis.

Analyze US news articles related to Covid-19. Also create a summarizer and text generation app using Flask which will summarize and predict the next words for Covid-19 news articles.

## Fetch Data
Data was fetched from [NewsApi](https://newsapi.org/docs/get-started). Articles were fetched from 3rd March 2020 to 1st April 2020.

## Summarizer App
A Text Summarizer app was created using Flask, FlaskForm and HuggingFace Transformer's BART model. More about HuggingFace BART model can be found [here](https://huggingface.co/transformers/model_doc/bart.html)

![screen1](https://github.com/jinudaniel/covid19-articles-analysis/blob/master/assets/screen1.PNG)
  
#### Output
![screen2](https://github.com/jinudaniel/covid19-articles-analysis/blob/master/assets/screen2.PNG)

## Text Generator App
A language model app to predict the next words given an input was created using Flask and HuggingFace Transformer's GPT2 model.

![lm_screen1](https://github.com/jinudaniel/covid19-articles-analysis/blob/master/assets/lm_screen1.PNG)

#### Output
![lm_screen2](https://github.com/jinudaniel/covid19-articles-analysis/blob/master/assets/lm_screen2.PNG)

