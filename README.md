

## 1. Playing with BERT base fucionality locally NSP mode

Notebook shows how BERT predicts next sentence(NSP mode).

[nsp_compare_sentences.ipynb:](https://github.com/len-sla/NLP/blob/master/nsp_compare_sentences.ipynb)


![### bert-msm.PNG](bert-nsp.PNG)



---
## 2. Predicting BERT in equal sizes
[predict_bert_equal_batches.ipynb:](https://github.com/len-sla/NLP/blob/master/predict_bert_equal_batches.ipynb)

Notebook shows how you can use Google Colab with free GPU to get Bert model predictions. Generally it is nothing special except the times where there is not enough GPU memory to do the task. To make it possible traing set is being traine in batches. Below there is example BERT model = 'cased_L-12_H-768_A-12' is used

---
## 3. Text Summarization


[Text Summarization using BERT, GPT2,XLNET.ipynb](https://github.com/len-sla/NLP/blob/master/Text%20Summarization%20using%20BERT%2C%20GPT2%2CXLNET.ipynb)



Text Summarization is the process of shortening a set of data computationally, to create a subset (a summary) that represents the most important or relevant information within the original content.

The sentences, in summary, are generated by the model, not just extracted from the original text data.
Original text was taken froom Internet and was like below

_'''
       CLIP (Contrastive Language–Image Pre-training) builds on a large body of work on zero-shot transfer, natural language supervision, and multimodal learning. The idea of zero-data learning dates back over a decade8 but until recently was mostly studied in computer vision as a way of generalizing to unseen object categories.910 A critical insight was to leverage natural language as a flexible prediction space to enable generalization and transfer. In 2013, Richer Socher and co-authors at Stanford11 developed a proof of concept by training a model on CIFAR-10 to make predictions in a word vector embedding space and showed this model could predict two unseen classes. The same year DeVISE12 scaled this approach and demonstrated that it was possible to fine-tune an ImageNet model so that it could generalize to correctly predicting objects outside the original 1000 training set.

_Most inspirational for CLIP is the work of Ang Li and his co-authors at FAIR13 who in 2016 demonstrated using natural language supervision to enable zero-shot transfer to several existing computer vision classification datasets, such as the canonical ImageNet dataset. They achieved this by fine-tuning an ImageNet CNN to predict a much wider set of visual concepts (visual n-grams) from the text of titles, descriptions, and tags of 30 million Flickr photos and were able to reach 11.5% accuracy on ImageNet zero-shot.

_Finally, CLIP is part of a group of papers revisiting learning visual representations from natural language supervision in the past year. This line of work uses more modern architectures like the Transformer32 and includes VirTex,33 which explored autoregressive language modeling, ICMLM,34 which investigated masked language modeling, and ConVIRT,35 which studied the same contrastive objective we use for CLIP but in the field of medical imaging

        '''

![### NLP_summarisation.PNG](NLP_summarisation.PNG)
---

### Libraries
Notebook was inspired by content of https://github.com/google-research/bert. All models from smallest to to standard one could be downloaded from https://storage.googleapis.com/bert_models/2020_02_20/all_bert_models.zip Models were downloaded and uzipped to subirectory models. Everything was done in Conda prepared environment.

 
 

## Status
Project is: _in progress_, 




### Info
Created by [@len-sla]
