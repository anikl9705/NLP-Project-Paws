# NLP-Project-Paws

Paraphrase Adversaries from Word Scrambling

group project for CSE 576 Topics/Natural Language Processing


## The Team

1.Anirudh Krishna Lakshmanan (alaksh19@asu.edu)

2.Sagar Seth (sseth9@asu.edu)

3.Yuanyuan Tian (ytian72@asu.edu)

4.Zhemin Zhang (zzhan215@asu.edu)

5.Xinyu Zhao (Xzhao119@asu.edu)



## TA

Pratyay Banerjee <pbanerj6@asu.edu>

<b>regular meeting with TA: 4:30-5:30pm Wed every week </b>

location: BYENG221 TA Lab   https://www.google.com/maps/place/Brickyard+Engineering,+699+S+Mill+Ave,+Tempe,+AZ+85281/@33.4235981,-111.9417253,17z/data=!3m1!4b1!4m5!3m4!1s0x872b08d8329334d3:0x4fe12bf6b8cf1757!8m2!3d33.4235981!4d-111.9395366



## Meeting Logs


### Meeting 1

#### Date
2020.02.10

#### Content
project selection

------
### Meeting 2
#### Date 
2020.02.24

#### Content
project: PAWS

The main link: https://github.com/google-research-datasets/paws

(1) Read the dataset description in the main link: PAWS-Wiki + PAWS-QQP

(2) Discuss the paper:  

PAWS: Paraphrase Adversaries from Word Scrambling (https://arxiv.org/abs/1904.01130)

especially the dataset generation

(3) Take a look at the dataset:  

PAWS-QQP

(4) Go through the code:  

https://github.com/google-research-datasets/paws/blob/master/qqp_generate_data.py

(5) Decide the refular meeting time with TA

#### Questions prepared for TA

* How to fine-tune BERT? 
* How to see the changes after we feed the PAWS dataset input BERT?
* 

------
### Meeting 3 with TA
#### Date 
2020.02.26


------
### Meeting 4 
#### Date 
2020.03.09

##### some resources about BERT I found -- Yuanyuan:

BERT, or Bidirectional Encoder Representations from Transformers, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.

###### (1) Intro

https://www.blog.google/products/search/search-language-understanding-bert/

https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html

A super great blog about NLP: FROM Pre-trained Word Embeddings TO Pre-trained Language Models — Focus on BERT
Paper: https://towardsdatascience.com/from-pre-trained-word-embeddings-to-pre-trained-language-models-focus-on-bert-343815627598

The academic paper which describes BERT in detail and provides full results on a number of tasks can be found here: https://arxiv.org/abs/1810.04805.


###### (2) Official

Github: https://github.com/google-research/bert

Google Colab:BERT End to End (Fine-tuning + Predicting) with Cloud TPU: Sentence and Sentence-Pair Classification Tasks

###### (3) Blogs 

https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/bert_finetuning_with_cloud_tpus.ipynb#scrollTo=wHQH4OCHZ9bq

*Tips: If you get a message as “You’ve reached the end of your free member preview for this month.” from https://medium.com/, read those blogs in the incognito mode of your browser.

Google’s BERT changing the NLP Landscape: https://medium.com/sciforce/googles-bert-changing-the-nlp-landscape-5f4a7bf65cc5

A Visual Guide to Using BERT for the First Time: http://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/

BERT for dummies — Step by Step Tutorial: https://towardsdatascience.com/bert-for-dummies-step-by-step-tutorial-fb90890ffe03

State-of-the-art pre-training for natural language processing with BERT: https://blog.insightdatascience.com/using-bert-for-state-of-the-art-pre-training-for-natural-language-processing-1d87142c29e7

A Hands-On Guide To Text Classification With Transformer Models (XLNet, BERT, XLM, RoBERTa): https://towardsdatascience.com/https-medium-com-chaturangarajapakshe-text-classification-with-transformer-models-d370944b50ca (github: https://github.com/ThilinaRajapakse/pytorch-transformers-classification) (out of date, no need to use)

Simple Transformers — Introducing The Easiest Way To Use BERT, RoBERTa, XLNet, and XLM: https://towardsdatascience.com/simple-transformers-introducing-the-easiest-bert-roberta-xlnet-and-xlm-library-58bf8c59b2a3 (github: https://github.com/ThilinaRajapakse/simpletransformers)

Question Answering with BERT, XLNET, XLM, and DistilBERT using Simple Transformers: https://towardsdatascience.com/question-answering-with-bert-xlnet-xlm-and-distilbert-using-simple-transformers-4d8785ee762a


