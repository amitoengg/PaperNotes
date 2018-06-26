# PaperNotes
My Notes on Papers 

## June 2018
1. [CIKM 2013 : Learning deep structured semantic models for web search using clickthrough data](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/cikm2013_DSSM_fullversion.pdf). **DSSM** is **CDSSM** without pooling and convolution.
2. [CIKM 2014 : A Latent Semantic Model with Convolutional-Pooling Structure for Information Retrieval](http://www.iro.umontreal.ca/~lisa/pointeurs/ir0895-he-2.pdf) This paper (**CDSSM**) incorporates a convolutional-pooling structure over word sequences to learn low-dimensional, semantic vector representations for search queries and Web documents. The Words are repesented as count of trigrams. Size of models is prop to N * 30K (as 30K trigrams)
3. [CIKM 2016 : A Deep Relevance Matching Model for Ad-hoc Retrieval](https://arxiv.org/pdf/1711.08611.pdf) (**DRMM**)
ad-hoc retrieval task is mainly about `relevance matching` while most NLP matching tasks concern `semantic matching`, and there are some
fundamental differences between these two matching tasks.Successful relevance matching requires proper handling of the `exact matching signals, query term importance, and diverse matching requirements`. Uses `Matching Histograms` to take care of variable length documents so that no padding is required. Later aggregates the match for each query term using a Gating Mechanism (query reweighting) This produces an aggregation weight for each query term controlling how much the relevance score on that query term contributes to the final relevance score.
4. [SIGIR 2015 : Learning to reweight terms with distributed representations](https://www.cs.cmu.edu/~callan/Papers/sigir15-gzheng.pdf)


