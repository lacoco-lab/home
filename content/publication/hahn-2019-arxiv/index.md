---
title: Theoretical limitations of self-attention in neural sequence models
authors:
- Michael Hahn
date: '2020-10-01'
publishDate: '2023-11-01T19:18:58.538610Z'
publication_types:
- article-journal
publication: '*Transactions of the Association for Computational Linguistics*'
abstract: 'Transformers are emerging as the new workhorse of NLP, showing great success
  across tasks. Unlike LSTMs, transformers process input sequences entirely through
  self-attention. Previous work has suggested that the computational capabilities
  of self-attention to process hierarchical structures are limited. In this work,
  we mathematically investigate the computational power of self-attention to model
  formal languages. Across both soft and hard attention, we show strong theoretical
  limitations of the computational abilities of self-attention, finding that it cannot
  model periodic finite-state languages, nor hierarchical structure, unless the number
  of layers or heads increases with input length. These limitations seem surprising
  given the practical success of self-attention and the prominent role assigned to
  hierarchical structure in linguistics, suggesting that natural language can be approximated
  well with models that are too weak for the formal languages typically assumed in
  theoretical linguistics.'
url_pdf: https://doi.org/10.1162/tacl_a_00306
links:
- name: Preprint
  url: https://arxiv.org/abs/1906.06755
- name: Formalization
  url: https://github.com/m-hahn/uhat-lean
- name: Supplement
  url: files/transformers-proof.pdf
---
