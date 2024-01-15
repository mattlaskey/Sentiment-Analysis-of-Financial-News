# Evaluation
## In this folder you can find the evaluation notebooks using the testing set eg. [66% agree](https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_66agree) 

- [eval_best_model_on_huggingFace.ipynb](eval_best_model_on_huggingFace.ipynb) contains the evaluation computations done for the [most downloaded model](https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis) trained on this data on huggingface. 
- [eval_distilBert.ipynb](eval_distilBert.ipynb) contains the evaluation computations done [our finetuned model](/distilBert-classifier.ipynb) based on the DistilBert architecure.
- [eval_chat3.ipynb](eval_chat3.ipynb) contains the evaluation computations done for [our fine turned vision](/chat3GPT-classifier.ipynb) of a ChatGPT2 instance [published by microsoft](https://huggingface.co/microsoft/DialogRPT-updown) geared toward another classification tasks.
- [eval_mostFreqClass.ipynb.ipynb](eval_mostFreqClass.ipynb.ipynb) is the most evalution notebook for the most frequent class classifier