# Fsentiment
## A NLP project about financial sentiment classification
### For more details please see our report

The outcome of this project is one [DistiBert classifier]( 	
distilBert-classifier.ipynb) which achives the following metrics on an finantial experts classified test data set:

- Macro F1 score:		0.86

The training and test data come from the [financial phrasebank](https://huggingface.co/datasets/financial_phrasebank) dataset.

Important to note here is that the training data set is the [sentences all agree](https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_allagree) sub-data set in which all annotators classified a sentence with the same label. The validation data and test data set is of lower quality here only [75% of the annotators agree](https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_75agree) and [66% of the annotators agree](https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_66agree) respectively. On the plus side however these sets are larger. 

It is hard to compare our results on the currently [most downloaded model](https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis) trained on this data set on Hugging face since they do not disclose on which sub data set they are training or testing on. Therefore we tested this model on the [66% of the annotators agree](https://huggingface.co/datasets/financial_phrasebank/viewer/sentences_66agree) data set and measured an macro F1 score of 0.90 (evaluation script found [here](/evaluation/eval_best_model_on_huggingFace.ipynb)). 

With these evaluation results we conclude that the simple DistilBert can achieve equal results to other state-of-the-art methods in this problem domain. For the detailed evaluation results please refer to the [evaluation folder](/evaluation/)

We published our [model](https://huggingface.co/Dave12121/Fsentiment) on hugging face for futher use. 

We also published the [GPT-2 benchmark](https://huggingface.co/Dave12121/chat3Fsentiment).


# Sentiment-Analysis-of-Financial-News
