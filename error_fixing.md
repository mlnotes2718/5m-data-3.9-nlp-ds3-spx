# How I fix the Error

## Error 1 Problem Downloading Spacy

![alt text](<error/Screenshot 2026-01-26 at 18.10.51.png>)

I recreate a new conda [environment here](nlp_env.yml). 

## Error 2 Problem Downloading NLTK Package

![alt text](<error/Screenshot 2026-01-26 at 18.15.11.png>)

I rename the package 

```python
#nltk.download('punkt')
nltk.download('punkt_tab')
```

![alt text](<error/Screenshot 2026-01-26 at 19.00.53.png>)

```python
# nltk.download('averaged_perceptron_tagger')
nltk.download('averaged_perceptron_tagger_eng')
```