# Google QUEST Experiments

Part of a NLP course final project.
Exploration of various Transformer networks and pretrained weights for sentence-based regression.
- BERT
- DistilBERT
- RoBERTa
- XLNet


# What is [Google QUEST](https://www.kaggle.com/c/google-quest-challenge)?
In this competition, we need to use [this new dataset](https://www.kaggle.com/c/google-quest-challenge/data) to build predictive algorithms for different subjective aspects of question-answering. The question-answer pairs were gathered from nearly 70 different websites, in a "common-sense" fashion. Our raters received minimal guidance and training, and relied largely on their subjective interpretation of the prompts. As such, each prompt was crafted in the most intuitive fashion so that raters could simply use their common-sense to complete the task. By lessening our dependency on complicated and opaque rating guidelines, we hope to increase the re-use value of this data set.

Demonstrating these subjective labels can be predicted reliably can shine a new light on this research area. Results from this competition will inform the way future intelligent Q&A systems will get built, hopefully contributing to them becoming more human-like.

# Requirements
 - [Google Colab](https://github.com/googlecolab) environment with PyTorch and internet connection.
 - Must download train.csv, test.csv, and sample_submission.csv from official Kaggle page to local directory of google colab runtime.

# Result
- Achieved mean Spearman's rank correlation coefficient (across all 30 category labels) of 0.39 using BERT-uncased model 

# Used Libraries
 - [NumPy](https://github.com/numpy/numpy)
 - [SciPy](https://github.com/scipy/scipy)
 - [Pytorch](https://github.com/pytorch/pytorch)
 - [Scikit-Learn](https://github.com/scikit-learn/scikit-learn)
 - [Huggingface's Transformer](https://github.com/huggingface/transformers)