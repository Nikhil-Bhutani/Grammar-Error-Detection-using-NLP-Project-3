# Grammar-Error-Detection-using-NLP-Project-3
## Grammar Error Checker using BERT and XLNET.
This project can detect whether the given input English Sentence is grammatically correct or not.
*Input:*  Sentence(English Language).

*Output:* The implemented system will check whether the given sentence is grammatically correct or not using both BERT(bert-base-cased) and XLNET(xlnet-base-cased) models were used.

Here both the models are trained on Google-Colaboratory and after training the classifier models are downloaded and further used for grammar checking. 

I have used The Corpus of Linguistic Acceptability (CoLA) dataset for predicting a single sentence as grammatically correct or not. Dataset used consist a set of sentences labeled as grammatically correct or incorrect represented by labels 1 and 0 respectively. It was first published in May of 2018, and is one of the tests included in the "GLUE Benchmark" on which models like BERT are competing.

### Requirements
#### Install Required Libraries
```bash
   pip install tensorflow
```
```bash
   pip install transformers
```
```bash
   pip install torch
```
```bash
   pip install wget
```
```bash
   pip install numpy 
```
```bash
   pip install pandas
```
```bash
   pip install seaborn
```
```bash
   pip install matplotlib
```
```bash
   pip install scikit-learn
```
