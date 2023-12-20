# Highlight Implementation:

- Finetune BERT-base-cased, BERt-base-uncased, BERT-lare-uncased, DistilBERT on IMDB Dataset
- Implemented a new Linear Layer additional to the BERT model backbone for sentiment analysis task
- Test the finetuned model on Amazon Review Datasets.

# Results:

| BERT MODEL | Before Finetune (%) | After Finetune (%) |
| ---------- | ------------------- | -------------- |
| DistilBERT | 88.20               | 88.27          |
| base-uncased | 50.00             | 90.33          |
| base-cased | 50.01               | 89.01          |
| large-uncased | 38.81            | 90.62          |

# Comments

- The dataset folders contains the IMDB, Amazon Review (test dataset only), and the tokenized dataset that for each model. However, it is too large to put in github, see the notebook for more information on how to get tokenized dataset
- Model contains all of the checkpoints of the model after finetuning