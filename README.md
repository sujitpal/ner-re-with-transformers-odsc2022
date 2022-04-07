# transformers-ner-re-odsc2022

## Title

Transformer based approaches to Named Entity Recognition (NER) and Relationship Extraction (RE)

## Session type 

Workshop (hands-on)

## Abstract

Named Entity Recognition (NER) and Relationship Extraction (RE) are foundational for many downstream NLP tasks such as Information Retrieval and Knowledge Base construction. While pre-trained models exist for both NER and RE tasks, they are usually specialized for some narrow application domain. If your application domain is different, your best bet is to train your own models. However, the costs associated with training, specifically generating training data, can be a significant deterrent for doing so. Fortunately, Language Models learned by pre-trained Transformers learn a lot about the language of the domain it is trained and fine-tuned on, and therefore NER and RE models based on these Language Models require fewer training examples to deliver the same level of performance. In this workshop, participants will learn about, train, and evaluate Transformer based neural models for NER and RE.

## Outline

* Background (25 mins)
  * Problem Definition
  * Overview of previous (non-neural) approaches to NER and RE
* Named Entity Recognition (1 hour)
  * Neural and Transformer based architectures for Named Entity Recognition
  * Hands-on case study – train a Transformer based NER using the Groningen Meaning Bank (GMB) dataset to predict entities such as person, organization, geographical entity, etc.
* Relationship Extraction (1 hour) 
  * Neural and Transformer based architectures for Relationship Extraction
  * Hands-on case study – train a Transformer based RE model using the New York Times Relation Extraction dataset to predict relations such as nationality, place of birth, company founder, etc.
* Conclusion (20 mins)
  * Applications of NER and RE
  * Q/A session


## Datasets

* [GMB (Groningen Meaning Bank) dataset for NER](https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus)
* [NYT (New York Times) dataset for RE](https://www.kaggle.com/daishinkan002/new-york-times-relation-extraction-dataset)

## Links

* [Blog post on ODSC](https://odsc.com/blog/building-named-entity-recognition-and-relationship-extraction-components-with-huggingface-transformers/?utm_campaign=Learning%20Posts&utm_content=200655503&utm_medium=social&utm_source=twitter&hss_channel=tw-1357730263481122817) describing why you might want to consider taking this tutorial.

