# PaperNotes
My Notes on Papers 

## June 2018
1. [CIKM 2013 : Learning deep structured semantic models for web search using clickthrough data](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf). **DSSM** is **CDSSM** without pooling and convolution.
1. [CIKM 2014 : A Latent Semantic Model with Convolutional-Pooling Structure for Information Retrieval](http://www.iro.umontreal.ca/~lisa/pointeurs/ir0895-he-2.pdf) This paper (**CDSSM**) incorporates a convolutional-pooling structure over word sequences to learn low-dimensional, semantic vector representations for search queries and Web documents. The Words are repesented as count of trigrams. Size of models is prop to N * 30K (as 30K trigrams)
1. [EMNLP 2014 : Modeling interestingness with deep neural networks](https://www.microsoft.com/en-us/research/wp-content/uploads/2014/10/604_Paper.pdf)
1. [NIPS 2014 : Convolutional Neural Network Architectures for Matching Natural Language Sentences](https://arxiv.org/pdf/1503.03244.pdf)
1. [CIKM 2016 : A Deep Relevance Matching Model for Ad-hoc Retrieval](https://arxiv.org/pdf/1711.08611.pdf) (**DRMM**)
ad-hoc retrieval task is mainly about `relevance matching` while most NLP matching tasks concern `semantic matching`, and there are some
fundamental differences between these two matching tasks.Successful relevance matching requires proper handling of the `exact matching signals, query term importance, and diverse matching requirements`. Uses `Matching Histograms` to take care of variable length documents so that no padding is required. Later aggregates the match for each query term using a Gating Mechanism (query reweighting) This produces an aggregation weight for each query term controlling how much the relevance score on that query term contributes to the final relevance score.
1. [CIKM 2017 : DeepRank: A New Deep Architecture for Relevance Ranking in Information Retrieval](https://arxiv.org/pdf/1710.05649.pdf)

1. [SIGIR 2015 : Learning to reweight terms with distributed representations](https://www.cs.cmu.edu/~callan/Papers/sigir15-gzheng.pdf)
1. [IJCAI 2015 : Syntax-based Deep Matching of Short Texts](https://arxiv.org/pdf/1503.02427.pdf)
1. 
