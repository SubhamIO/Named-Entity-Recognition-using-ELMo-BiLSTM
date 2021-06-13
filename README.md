# Named-Entity-Recognition_DeepLearning-ELMo-BiLSTM

## Introduction : 

- Named-entity recognition (NER) (also known as entity identification, entity chunking and entity extraction) is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organisations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.
 It adds a wealth of semantic knowledge to your content and helps you to promptly understand the subject of any given text.

## Applications : 

- Few applications of NER include: extracting important named entities from legal, financial, and medical documents, classifying content for news providers, improving the search algorithms, and etc.

## Approaches to tackle this problem:

- Machine Learning Approach : treating the problem as a Multi-class classification with named entities are our labels . The problem here is that for longer sentences identifying and labelling named entities require thorough understanding of the context of a sentence and sequence of the word labels in it, which this method ignores and cannot capture the essence of the entire sentence.

- Deep Learning Approach : The best possible model which can tackle this problem is Long-Short Time Memory(LSTM) models, specifically we will use Bi-directional LSTM for our setup . A Bi-directional LSTM is a combination of two LSTM's - one runs forward from "right to left" and one runs backward from "left to right", thus capturing the entire essence/context of the sentence . For NER, since the context covers past and future labels in a sequence, we need to take both the past and the future information into account.


Check out the full Articele and tutorial on how to run this project [here.](https://kingsubham27.medium.com/named-entity-recognition-using-deep-learning-elmo-embedding-bi-lstm-48295bc66cab)
