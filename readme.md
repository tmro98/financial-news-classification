**Classification of full-length news articles**

|task|representation/model|metric|
|---|---|---|
|binary topic classification|  RoBERTa-large fine-tuned |93% accuracy, 91% recall (test size = 0.2, 2890)
|3-class sentiment classification|  RoBERTa-large fine-tuned | 75% accuracy (test size = 0.2, 1530)|   

### binary topic

| class | # |
|---|---|
|financial | 7647 |
| non-financial | 6799 |


### multiclass sentiment

|classification|#|
|---|---|
| neg  |2287|
| neu*   |2544|
| pos   |2816|

*a major source of uncertainty and error(during manual classification and modeling),

<br>

## Resources  

LLMs   
https://magazine.sebastianraschka.com/p/understanding-large-language-models

Huggingface (Transformers)  
https://huggingface.co/docs/transformers/index  
https://huggingface.co/docs/transformers/tasks/sequence_classification  
https://huggingface.co/docs/transformers/training#train-with-pytorch-trainer  
https://huggingface.co/docs/transformers/v4.30.0/en/main_classes/trainer#transformers.Trainer

Scikit-Learn  
https://scikit-learn.org/stable/user_guide.html

## Literature

Evaluation of Sentiment Analysis in Finance: From Lexicons to Transformers  
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9142175

FinBERT: Financial Sentiment Analysis with Pre-trained Language Models  
https://arxiv.org/pdf/1908.10063.pdf


How to Fine-Tune BERT for Text Classification?  
https://arxiv.org/pdf/1905.05583.pdf

Financial Sentiment Analysis:
An Investigation into Common Mistakes and Silver Bullets  
https://aclanthology.org/2020.coling-main.85.pdf
