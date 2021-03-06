# Overview

- **Chapter 3: Natural Language Processing, Recurrent Neural Nets and Self-Attention Nets**

  - 3.1: *Introduction to Natural Language Processing*
    - The Get Things Done Way
    - The Slow and Steady Way
    
    
  - 3.2 *Recurrent Neural Nets*
    - Blogposts that presents RNN
    - Show me the Code
    - Show me the Math
 
  - 3.3 *Self-Attention Nets* (aka Transformer)
     - Blogposts that presents Transformer
     - Show me the Code
     - Show me the Math
   
 - 3.4: *Natural Language Processing (for real)*
 
 
 **Words of advice:**

  - NLP is kind of niche but still a pretty wide subfield, knowing little goes a long way but understanding the basics goes a longer way.
  - The free courses listed in Secion 3.1 require quite a lot of committment, if you're looking for a quick way to break-in to NLP, pick one of the tools from `The Get Things Done Way` section and start from there, while you work through one of the courses listed above. 
    - P/S: You don't have to know everything in NLP or all the tools but it's good to know that alternative tools exists
  - Read the `NLP (for real)` section =)


----


### 3.1: **Introduction to Natural Language Processing**

**The Get Things Done Way**
 - PyTorch Tutorials:
   - https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html (take a look at others under the `Text` section on the left panel too) 
   - https://github.com/pytorch/text
   - https://github.com/pytorch/fairseq
   - http://mlexplained.com/2018/02/08/a-comprehensive-tutorial-to-torchtext/
   - https://github.com/ritchieng/the-incredible-pytorch
 - AllenNLP Tutorials:
   - https://allennlp.org/tutorials and [EMNLP 2018 tutorial](https://github.com/allenai/writing-code-for-nlp-research-emnlp2018/blob/master/writing_code_for_nlp_research.pdf)
 - FastAI Tutorials:
   - http://nlp.fast.ai/
 - Keras NLP Tutorials:
   - https://realpython.com/python-keras-text-classification/
   - https://nlpforhackers.io/keras-intro/
   - https://machinelearningmastery.com/develop-word-based-neural-language-models-python-keras/
 - DyNet Tutorials:
   - https://dynet.readthedocs.io/en/latest/tutorial.html
   - [EMNLP 2016 Tutorial](https://github.com/clab/dynet_tutorial_examples)
 - SpaCy Tutorials
   - https://spacy.io/usage/spacy-101
   - https://explosion.ai/blog/deep-learning-formula-nlp
   - https://www.youtube.com/watch?v=vrtTAeBLElw
   - https://nlpforhackers.io/complete-guide-to-spacy/
 - Gensim Tutorials
   - https://radimrehurek.com/gensim/tutorial.html
   - https://lilianweng.github.io/lil-log/2017/10/15/learning-word-embedding.html
   - https://machinelearningmastery.com/develop-word-embeddings-python-gensim/
   - https://towardsdatascience.com/topic-modelling-in-python-with-nltk-and-gensim-4ef03213cd21
 - NLTK Basics (the useful bits): 
   - http://www.nltk.org/howto/
   - https://www.kaggle.com/alvations/basic-nlp-with-nltk 

**The Slow and Steady Way**
 - Stanford Course: https://web.stanford.edu/class/cs224n/ 
 - Berkley Course: http://people.ischool.berkeley.edu/~dbamman/nlp18.html
 - CMU Course: http://phontron.com/class/nn4nlp2017/
 - Oxford Course: https://www.cs.ox.ac.uk/teaching/courses/2016-2017/dl/ 
 - [Lisbon Machine Learning School (LxMLS 2018)](http://lxmls.it.pt/2018/?page_id=19) (focuses a lot on NLP in 2018)
 - Saarland University [Foundations in Language Sciencea and Technology (FLST) course](http://www.coli.uni-saarland.de/courses/FLST/2018/FLST.html)  
  - National University of Singapore (NUS) [Deep Learning for NLP Course](https://www.comp.nus.edu.sg/~kanmy/courses/6101_1810/)
  
  
**References**
  - Books / Articles
    - [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) (Jurafsky and Martin's Book) 
    - [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) (Chris Manning's book, hardcore math)
    - [Computational Linguistics and Deep Learning](https://www.mitpressjournals.org/doi/pdf/10.1162/COLI_a_00239) (Chris Manning's words in 2015)
    - [A Primer on Neural Network Models for Natural Language Processing](https://u.cs.biu.ac.il/~yogo/nnlp.pdf) (Yoav Goldberg's book/chapter)
      - physical book version on https://www.morganclaypool.com/doi/abs/10.2200/S00762ED1V01Y201703HLT037
    - [Jacob Einstein's notes on NLP and DL](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf)
    - [Natural Language Processing with PyTorch](http://shop.oreilly.com/product/0636920063445.do)
    - [Deep Learning with Text](http://shop.oreilly.com/product/0636920076063.do)
  - Related but not directly
    - [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) (Russell and Norvig's book)
      - Borrow from national library, click [here](https://catalogue.nlb.gov.sg/cgi-bin/spydus.exe/FULL/WPAC/BIBENQ/13461273/269039522,1) =) 
    - [Deep Learning](https://www.deeplearningbook.org/) (Goodfellow et al. book)
  


----


### 3.2: **Recurrent Neural Nets**

  - Blogpost that explains RNN
    - http://colah.github.io/posts/2015-08-Understanding-LSTMs/
    - http://karpathy.github.io/2015/05/21/rnn-effectiveness/
    - http://www.wildml.com/2015/09/recurrent-neural-networks-tutorial-part-1-introduction-to-rnns/
    - http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/
    - https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767
    - https://skymind.ai/wiki/lstm
    - **On Attention**
      - https://medium.com/syncedreview/a-brief-overview-of-attention-mechanism-13c578ba9129
      - http://www.wildml.com/2016/01/attention-and-memory-in-deep-learning-and-nlp/
      - https://skymind.ai/wiki/attention-mechanism-memory-network
      - https://machinelearningmastery.com/attention-long-short-term-memory-recurrent-neural-networks/
  
  - Show me the code
    - https://iamtrask.github.io/2015/11/15/anyone-can-code-lstm/
    - http://www.jessicayung.com/lstms-for-time-series-in-pytorch/
    - https://medium.com/@shivambansal36/language-modelling-text-generation-using-lstms-deep-learning-for-nlp-ed36b224b275
    - https://adventuresinmachinelearning.com/keras-lstm-tutorial/
    - https://www.depends-on-the-definition.com/attention-lstm-relation-classification/
    - For more, see above `The Get Things Done Way` (Section 3.1) 

  - Show me the math
    - https://www.coursera.org/lecture/nlp-sequence-models/why-sequence-models-0h7gT
    - http://arunmallya.github.io/writeups/nn/lstm/index.html#/ (move forward the page by clicking the arrow on bottom right)
    - https://www.cs.toronto.edu/~tingwuwang/rnn_tutorial.pdf
    - https://brilliant.org/wiki/recurrent-neural-network/
    - http://www.cs.bham.ac.uk/~jxb/INC/l12.pdf
    - https://www.kth.se/polopoly_fs/1.801971!/deep%20learning.pdf
    - https://arxiv.org/pdf/1803.06396.pdf
    - Independent RNN https://arxiv.org/abs/1803.04831 (Not really for beginners but this is like the AlexNet of RNNs)
    - RNN Paper: https://www.mitpressjournals.org/doi/abs/10.1162/neco.1997.9.8.1735 
    - LSTM Paper: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.676.4320&rep=rep1&type=pdf 
    - GRU Paper: https://arxiv.org/pdf/1502.02367v4.pdf
    - Alex Grave's Thesis: http://www.cs.toronto.edu/~graves/phd.pdf

----


### 3.3: **Self-Attention Nets** (aka Transformer)

  - Blogpost that explains Self-Attention Nets
    - http://jalammar.github.io/illustrated-transformer/
    - https://ai.googleblog.com/2017/08/transformer-novel-neural-network.htm
    - https://ai.googleblog.com/2018/11/open-sourcing-bert-state-of-art-pre.html
    - https://mchromiak.github.io/articles/2017/Sep/12/Transformer-Attentionis-all-you-need/
    - https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html (Different attention)


  - Show me the code
    - Original Tensor2Tensor library: https://github.com/tensorflow/tensor2tensor
    - http://nlp.seas.harvard.edu/2018/04/03/attention.html
    - https://medium.com/@kolloldas/building-the-mighty-transformer-for-sequence-tagging-in-pytorch-part-i-a1815655cd8 
    - https://towardsdatascience.com/how-to-code-the-transformer-in-pytorch-24db27c8f9ec
    
    
  - Show me the math
    - Attention Is All You Need paper: https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf


**Words of advice:**

  - Why are there so few resources on "Transformer" for beginners? *Because it's rather new =)*
  - If you want to see the influence of "Transformer" architectures in NLP, check out the papers from NAACL 2018, ACL 2018, EMNLP 2018 from https://aclanthology.coli.uni-saarland.de/

----


### 3.4: Natural Language Processing (*for real*) 

**You might ask**, "Hey, I saw this ['throw away your RNN' blogpost](https://towardsdatascience.com/the-fall-of-rnn-lstm-2d1594c74ce0). Does that mean whatever above is not relevant?"

**Answer:** Natural Language Processing evolves really fast and as a field that mostly adopts/applies the "hottest" trend from mainstream machine/deep learning, every ~2-3 years the underlying state-of-art architecture for NLP changes (quite drastically).

The only way to keep up is not to chase the trends. Know that the lastest/hottest algorithm or pre-trained models exists, understand how they work and find ways to incorporate them into whichever project/method you're using/researching on. 

There's really no point in chasing any method (in NLP or any other sub-fields of computing) because 

 - if you're in the industry, what usually happens is that you try every possible method until you find  that fits your needs
 - if you're in academia, chasing state-of-art is going to drain you out and make your work mediorce/common, focus on the story and why things work more than how to make model X work on task Y.
   
In 2018, here's some recent trends: https://arxiv.org/pdf/1708.02709.pdf

Best way to keep up with NLP is to look at proceedings from these conferences (there's a lot but here's a few curated ones):
 - Association of Computational Lingusitics (ACL) and related conferences: https://aclanthology.coli.uni-saarland.de/
 - Text Analysis Conference (TAC): http://tac.nist.gov/publications/index.html
   - *Due to a lapse in government funding, this and almost all NIST-affiliated websites will be unavailable until further notice.* -_-||| 
 - Interspeech proceedings on https://www.isca-speech.org/iscaweb/index.php/online-archive 
 - Text, Speech and Dialogue conferences: https://link.springer.com/conference/tsd
 - SIGIR conferences: http://sigir.org/conferences/sponsored-conferences/ 
 - AAAI conferences: http://www.aaai.org/Conferences/conferences.php 
 - WWW conferences: http://www.iw3c2.org/
 
 
As an NLP researcher/scientist, I encourage you to read and re-read these slides from Prof. Min-Yen Kan every once in a while http://coling2018.org/wp-content/uploads/2018/08/180824-researchFastAndSlow-1.pdf 


