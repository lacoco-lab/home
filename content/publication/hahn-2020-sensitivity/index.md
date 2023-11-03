---
title: Sensitivity as a complexity measure for sequence classification tasks
authors:
- Michael Hahn
- Dan Jurafsky
- Richard Futrell
date: '2021-11-01'
publishDate: '2023-11-01T19:18:58.506466Z'
publication_types:
- article-journal
publication: '*Transactions of the Association for Computational Linguistics*'
abstract: 'We introduce a theoretical framework for understanding and predicting the complexity of sequence classification tasks, using a novel extension of the theory of Boolean function sensitivity. The sensitivity of a function, given a distribution over input sequences, quantifies the number of disjoint subsets of the input sequence that can each be individually changed to change the output. We argue that standard sequence classification methods are biased towards learning low-sensitivity functions, so that tasks requiring high sensitivity are more difficult. To that end, we show analytically that simple lexical classifiers can only express functions of bounded sensitivity, and we show empirically that low-sensitivity functions are easier to learn for LSTMs. We then estimate sensitivity on 15 NLP tasks, finding that sensitivity is higher on challenging tasks collected in GLUE than on simple text classification tasks, and that sensitivity predicts the performance both of simple lexical classifiers and of vanilla BiLSTMs without pretrained contextualized embeddings. Within a task, sensitivity predicts which inputs are hard for such simple models. Our results suggest that the success of massively pretrained contextual representations stems in part because they provide representations from which information can be extracted by low-sensitivity decoders.'
links:
- name: URL
  url: 
    https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00403/106992/Sensitivity-as-a-Complexity-Measure-for-Sequence
- name: Code
  url: https://github.com/m-hahn/sensitivity
---
