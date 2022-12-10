## ENEM Challenge
This is a repository of the paper **Evaluating the Performance of Language Models solving ENEM_ A Study of BERTimbau and GPT-3***  

This paper examines the potential of artificial intelligence, specifically Transformer models such as BERT and GPT-3, in answering the Brazilian National High School Examination (ENEM). We analyzed the data of 916 questions administered in years 2010 to 2017 from ENEM Challenge \url{https://www.ime.usp.br/~ddm/project/enem/}. A number of models were tested based on BERTimbau embeddings, finetuned, and GPT3 with few shots and "chain of thought" training regimens. Overall, we found an accuracy score of .77 and an F1 score of .77 for the GPT3 models, which represents a new state of the art for ENEM challenge.

### Results  

| **Model**                       | **Accuracy**        | **F1**        |
| ---                             | ---                 | ---           |
| BERTIMbau Embeddings            |                     |               |
|   Heading                       | 20%                 | 0.19          |
|   Statement                     | 21%                 | 0.21          |
|   [CLS]                         | 20%                 | 0.19          |
| BERTIMbau Finetuned             | 57%                 | 0.41          |
| GPT3                            |                     |               |
| Few shot  davinci-002           | 77%                 | 0.77          |
| Few shot  davinci-003           | 77%                 | 0.77          |
| Chain of Thought  davinci-002   |                     |               |
| Chain of Thought  davinci-003   |                     |               |
