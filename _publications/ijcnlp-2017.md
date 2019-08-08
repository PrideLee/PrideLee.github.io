---
title: "Capturing Long-range Contextual Dependencies with Memory-enhanced Conditional Random Fields"
collection: publications
permalink: /publication/ijcnlp-2017-mecrf
date: 2017-11-28
venue: 'Proceedings of the Eighth International Joint Conference on Natural Language Processing'
paperurl: 'http://www.aclweb.org/anthology/I17-1056'
paperurltext: 'Link to ACL anthology'
citation: '<b>Fei Liu</b>, Timothy Baldwin and Trevor Cohn (2017) <a href="http://liufly.github.io/files/papers/ijcnlp-2017.pdf"><u>Capturing Long-range Contextual Dependencies with Memory-enhanced Conditional Random Fields</u></a>. In <i>Proceedings of the Eighth International Joint Conference on Natural Language Processing</i>, Taipei, Taiwan, pp. 555-565.'
---

```
@InProceedings{Liu+:2017,
  author    = {Liu, Fei  and  Baldwin, Timothy  and  Cohn, Trevor},
  title     = {Capturing Long-range Contextual Dependencies with Memory-enhanced Conditional Random Fields},
  booktitle = {Proceedings of the Eighth International Joint Conference on Natural Language Processing},
  year      = {2017},
  address   = {Taipei, Taiwan},
  pages     = {555--565}
}
```

## Abstract
Despite successful applications across a broad range of NLP tasks, conditional random fields (``CRFs''), in particular the linear-chain variant, are only able to model local features. While this has important benefits in terms of inference tractability, it limits the ability of the model to capture long-range dependencies between items. Attempts to extend CRFs to capture long-range dependencies have largely come at the cost of computational complexity and approximate inference. In this work, we propose an extension to CRFs by integrating external memory, taking inspiration from memory networks, thereby allowing CRFs to incorporate information far beyond neighbouring steps. Experiments across two tasks show substantial improvements over strong CRF and LSTM baselines.