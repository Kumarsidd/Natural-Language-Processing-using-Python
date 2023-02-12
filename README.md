# Natural-Language-Processing-using-Python
A simple NLP which performs grammar correction, text classification, text correction using Happy Transformer API .
# GETTING STARTED
## Installation
Initially you've to install 
 ```pip install happytransformer```
 * Then import the model using ```from happytransformer import HappyTextClassification```
 * Then define new variable ```happy_tc = HappyTextClassification("BERT", "ProsusAI/finbert", num_labels=3)``` here "_BERT_" is used to access pretraineed model, next args is used to define MODELS, last _"num_labels"_ is used to check the models output in 3 manners such as POSITIVE, NEGATIVE, NUETRAL.
 * Then ```print(result)``` or ```print(result.label) or print(result.score)``` to check result's manner whether positive or negative or neutral and score to check the accuracy.
 

To know more about Happy Transfromer, check about https://happytransformer.com/
