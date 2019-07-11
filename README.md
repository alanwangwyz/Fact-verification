# Fact-verification
![](https://img.shields.io/badge/index-pylucene-green.svg)
![](https://img.shields.io/badge/method-cosine&Word2Vec-blue.svg)
![](https://img.shields.io/badge/language-python-orange.svg)

![image](https://github.com/alanwangwyz/Fact-verification/blob/master/image/article-fact-or-opinion.jpg)
🍀
**Task**

From Training dataset to develop a reasonable prediction for the test data to evaluate our model

**Key Process To Generate result**
1. Preprocess
2. Document Retrieval
3. Sentence Retrieval
4. Label classification

## Preprocess ##
👻`Json` to `Dataframe`

👻Remove `StopWords`

👻`LowerCase`


## Document Retrieval ##
🌎`pylucene`to locate index

🌍`BM25` algorithm to improve recall and accuracy

🌏`Potential Title` extraction

## Sentence Retrieval ##
✨`Two` evidence for selection

✨`W2V``GloVe``Cosine`model 

✨`NER` and so on

## Label Classification ##
👉Allennlp Textual Entailment model

## Result ##
|Document F1|Sentence F1|Label Accuracy|
|47.2%|43.09%|55.61%|
