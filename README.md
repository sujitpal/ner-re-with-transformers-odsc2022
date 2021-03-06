# ner-re-with-transformers-odsc2022

## Title

[Transformer based approaches to Named Entity Recognition (NER) and Relationship Extraction (RE)](https://odsc.com/speakers/transformer-based-approaches-to-named-entity-recognition-ner-and-relationship-extraction-re/)

## Session type 

Workshop (hands-on)

## Abstract

Named Entity Recognition (NER) and Relationship Extraction (RE) are foundational for many downstream NLP tasks such as Information Retrieval and Knowledge Base construction. While pre-trained models exist for both NER and RE tasks, they are usually specialized for some narrow application domain. If your application domain is different, your best bet is to train your own models. However, the costs associated with training, specifically generating training data, can be a significant deterrent for doing so. Fortunately, Language Models learned by pre-trained Transformers learn a lot about the language of the domain it is trained and fine-tuned on, and therefore NER and RE models based on these Language Models require fewer training examples to deliver the same level of performance. In this workshop, participants will learn about, train, and evaluate Transformer based neural models for NER and RE.

## Outline

* **Background** (25 mins)
  * [Introduction and General Concepts](01-introduction.md)
* **Named Entity Recognition** (1 hour)
  * [Neural and Transformer based architectures for Named Entity Recognition](02-ner-intro.md)
  * [Case Study #1: BERT based NER fine-tuned using the Groningen Meaning Bank (GMB) dataset](03-gmb-ner-bert.ipynb)
  * [Case Study #2: Switching out BERT with DistilBERT](03a-gmb-ner-bert.ipynb)
  * [Case Study #3: XLM-RoBERTa based NER fine-tuned using HuggingFace Trainer API](03a-gmb-ner-xlmr.ipynb)
* **Relationship Extraction** (1 hour) 
  * [Neural and Transformer based architectures for Relationship Extraction](04-re-intro.md)
  * [Case Study #4: BERT based RE (e: entity markers mention pooling) fine-tuned using New York Times dataset](05-nyt-re-bert.ipynb)
  * [Case Study #5: BERT based RE (b: standard mention pooling) fine-tuned using New York Times dataset](05a-nyt-re-bert.ipynb)
  * [Case Study #6: BERT based RE (f: entity markers entity start) fine-tuned using New York Times dataset](05b-nyt-re-bert.ipynb)
* **Conclusion** (20 mins)
  * [Wrap-up](06-conclusion.md)
  * Q/A session


## Running the Code

* (optional) Fork this repository
* Navigate to the [Colab Web UI](https://colab.research.google.com/)
* Click on the GitHub tab
* Enter the URL of your forked (or this) repository in the field titled "Enter a GitHub URL" and hit the Search icon
* You should see the notebooks appear in the results. Click on the notebook you want to work with in Colab

## Datasets

* [GMB (Groningen Meaning Bank) dataset for NER](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)
* [NYT (New York Times) dataset for RE](https://www.kaggle.com/daishinkan002/new-york-times-relation-extraction-dataset)

## Additional Links

* [Blog post on ODSC](https://odsc.com/blog/building-named-entity-recognition-and-relationship-extraction-components-with-huggingface-transformers/?utm_campaign=Learning%20Posts&utm_content=200655503&utm_medium=social&utm_source=twitter&hss_channel=tw-1357730263481122817) describing why you might want to consider taking this tutorial.

