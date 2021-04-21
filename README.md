# Group10_NLP_Final_Project
Final Project NLP : Understanding and implementing the research paper : ***Tweet2Vec: Character-Based Distributed Representations for Social Media***

Contributors : Kumara Prasanna Jayaraju and Rinaldo Sonia

This repository provides a character-level encoder/trainer for social media posts. See Tweet2Vec paper for details.

There are two models implemented in the paper - the character level tweet2vec and a word level baseline. 

Data Collection:
Unfortunately, We didnt have any dataset associated with the paper due to confidentiality. So we planned to collect tweets on our own, based on the following common life oriented keywords such as '#life', '#motivation', '#happy', '#emotions', '#friends', '#babies', '#dogs' to implement and test out the project.

We have divided the paper into two parts and you can find the notebook and supportive files in their respective diretories.
Part 1: Comparing the correctly predicted hashtags by Word Model baseline with Tweet2Vec
Part 2: Training and testing the dataset to calculate Precision, Recall and Mean Rank.

Reference:
InProceedings{dhingra-EtAl:2016:P16-2,
  author    = {Dhingra, Bhuwan  and  Zhou, Zhong  and  Fitzpatrick, Dylan  and  Muehl, Michael  and  Cohen, William},
  title     = {Tweet2Vec: Character-Based Distributed Representations for Social Media},
  booktitle = {Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)},
  month     = {August},
  year      = {2016},
  address   = {Berlin, Germany},
  publisher = {Association for Computational Linguistics},
  pages     = {269--274},
  url       = {http://anthology.aclweb.org/P16-2044}
}


