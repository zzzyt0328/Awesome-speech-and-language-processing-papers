# Awesome speech and language processing papers

Speech and language processing (SLP) is a large field, covering a wide range of research topics. A classic book, "Speech and language processing - An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition" is from [Dan Jurafsky](http://web.stanford.edu/people/jurafsky/) and [James H. Martin](http://www.cs.colorado.edu/~martin/), which you can find [here](https://web.stanford.edu/~jurafsky/slp3/). 

The SLP field is moving fast. Here we are maintaining awesome speech and language processing papers. We hope the list of papers could serve for readers who are interested in entering the field and doing further research. We also include some tutorials, which are online freely accessible.

IEEE Signal Processing Society (SPS) uses Editor’s Information Classification Schemes (EDICS's) for the SPS transactions and conferences to classify and assign papers for reviewing and publishing. We will follow [the EDICS from SPS SLTC](https://signalprocessingsociety.org/community-involvement/speech-and-language-processing/edics) (Speech and Language Processing Technical Committee), but with some modifications.

_Disclaimer: We may miss some relevant papers in the list. If you have any suggestions or would like to add some papers, please submit a pull request or email us. Your contribution is much appreciated!_

1. [Automatic Speech Recognition (ASR)](#automatic-speech-recognition-asr)
2. [Language Modeling](#language-modeling)
3. [Dialog Systems](#dialog-systems)
4. Much more to be added


## Automatic Speech Recognition (ASR)

It includes a mix of EDICS topics:
- [SPE-RECO] Acoustic Modeling for Automatic Speech Recognition
- [SPE-LVCR] Large Vocabulary Continuous Recognition/Search (End-to-end approaches, Other LVSCR approaches)
- [SPE-ROBU] Robust Speech Recognition
- [SPE-ADAP] Speech Adaptation/Normalization
- [SPE-MULT] Multilingual Recognition and Identification
- [SPE-GASR] General Topics in Speech Recognition



1. **A tutorial on hidden Markov models and selected applications in speech recognition**. Lawrence Rabiner. Proceedings of the IEEE, 1989. [PDF](https://web.ece.ucsb.edu/Faculty/Rabiner/ece259/Reprints/tutorial%20on%20hmm%20and%20applications.pdf) (_HMM_)
2. **Speech Recognition with Weighted Finite-State Transducers**. Mehryar Mohri, Fernando Pereira, Michael Riley. Handbook on Speech Processing and Speech, Springer, 2008. [PDF](https://cs.nyu.edu/~mohri/pub/hbka.pdf) (_WFST_)
3. **State-of-the-Art of End-to-End Speech Recognition**. Zhijian Ou. Tutorial at The 6th Asian Conference on Pattern Recognition (ACPR 2021), Jeju Island, Korea, 2021.  [PDF](http://oa.ee.tsinghua.edu.cn/~ouzhijian/pdf/ACPR2021%20Tutorial%20State-of-the-Art%20of%20End-to-End%20Speech%20Recognition.pdf)
4. **Context-dependent pre-trained deep neural networks for large-vocabulary speech recognition**. George E. Dahl, Dong Yu, Li Deng, Alex Acero. IEEE Transactions on Audio, Speech, and Language Processing, 2011. [PDF](https://www.cs.toronto.edu/%7Egdahl/papers/DRAFT_DBN4LVCSR-TransASLP.pdf) (_DNN-HMM_)
5. **Connectionist temporal classification: Labelling unsegmented sequence data with recurrent neural networks**. Alex Graves, Santiago Fernandez, Faustino Gomez, and Juergen Schmidhuber. ICML, 2006. [PDF](https://www.cs.toronto.edu/~graves/icml_2006.pdf) (_CTC_)
6. **Purely sequence-trained neural networks for ASR based on lattice-free MMI**. Daniel Povey, et al. INTERSPEECH, 2016. [PDF](https://www.danielpovey.com/files/2016_interspeech_mmi.pdf) (_Kaldi_)
7. **Hybrid CTC/attention architecture for end-to-end speech recognition**. Shinji Watanabe, Takaaki Hori, Suyoun Kim, John Hershey, Tomoki Hayashi. IEEE Journal of Selected Topics in Signal Processing, 2017. [PDF](https://www.merl.com/publications/docs/TR2017-190.pdf) (_ESPnet_)
8. **CRF-based Single-stage Acoustic Modeling with CTC Topology**. Hongyu Xiang, Zhijian Ou. ICASSP, 2019. [PDF](http://oa.ee.tsinghua.edu.cn/~ouzhijian/pdf/ctc-crf.pdf) (_CTC-CRF_)
9. **Neural machine translation by jointly learning to align and translate**. Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio. ICLR, 2015. [PDF](https://arxiv.org/pdf/1409.0473.pdf) (_AED, Attention-based Encoder-Decoder_)
10. **Listen, attend and spell: A neural network for large vocabulary conversational speech recognition**. William Chan, Navdeep Jaitly, Quoc V. Le, Oriol Vinyals. ICASSP, 2016. [PDF](https://arxiv.org/pdf/1409.0473.pdf) (_LAS_)
11. **Sequence transduction with recurrent neural networks**. Alex Graves. ICML 2012 Workshop on Representation Learning, 2012 [PDF](https://arxiv.org/pdf/1211.3711.pdf) (_RNN-T_)
12. **Conditional random fields: Probabilistic models for segmenting and labeling sequence data**. Lafferty John, Andrew McCallum, Fernando Pereira. ICML, 2001. [PDF](https://repository.upenn.edu/server/api/core/bitstreams/4905e2c0-e9d5-4961-804b-973de8bdfc7c/content) (_CRF_)
13. **Conformer: Convolution-augmented Transformer for Speech Recognition**. Anmol Gulati, et al. Interspeech, 2020. [PDF](https://arxiv.org/pdf/2005.08100.pdf) (_Conformer_)
14. **Multilingual and Crosslingual Speech Recognition using Phonological-Vector based Phone Embeddings**. Chengrui Zhu, Keyu An, Huahuan Zheng, Zhijian Ou. ASRU, 2021. [PDF](https://arxiv.org/pdf/2107.05038.pdf) (_JoinAP_)

## Language Modeling
- [HLT-LANG] Language Modeling
- [HLT-LACL] Language Acquisition and Learning
- [HLT-UNDE] Spoken Language Understanding and Computational Semantics
- [HLT-MLMD] Machine Learning Methods for Language

1. S. F. Chen and J. Goodman, “An empirical study of smoothing techniques for language modeling”, Computer Speech & Language, 1999. (_N-Gram_) [PDF](https://pdf.sciencedirectassets.com/272453/1-s2.0-S0885230800X00101/1-s2.0-S0885230899901286/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQDL1QgahGW6Vc5lSlB4V7EMhJNwKza0cteZWruzfvgKUAIgQ1VI4t2BJvGMNWIif2tvIRxGoz%2F6RBEKOSdt1RicK0QquwUIz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDCEU7nXQalBtd4x1RiqPBezUE5qG8XimFM5XLTxeg6R%2FJy0PtRrYib0frG9w2aUpI%2FP9Q5Q46PGUDhlhcS4WdGcwebkrEUjxNpAy5RzOBQjRCFoJA8f6O6zurm%2Fef2g4cxKotbrftsBbrH0H47eXpMbk0D44GeBjfb6mRtRNw%2FRVefHik1Q9l%2B5a7GQ9Gs6hNsKaXt8YkB37NA00pp6MhBxru1tg72u%2BGAGQrnnEsO2BHeM7O9AZJs9VUssS14v9U0snYy0aDjHLCLCO8haaainOSDDdnZV4D8ODHb%2ByTl4CsGLUTo9btEAuBvpYncB5dNw66LN8yI2h7Gr%2FXXr6M%2BBYeqOHtkis6PW6rwHMR40KUu%2BduP0tUglKzC%2F3yA6%2B7f7y%2Bie1cVY3%2FDnZ1lBBVhi2H1bFf3W4zrgkn%2B98HYSJthTKurw8ui5OTLThFrT%2Bn4wFP6ajkPt%2FdoyusEjriLZl8jt%2FqCkPHQf7zsVj5IPf%2FJGjK6w2BzJ3VnI0wzJegIb3zkbtJILQSXZ6AYRPj12oRtW%2Fqf0dlvZCC6S8DvgMQ2TI%2FQlEdcA6X8a9ZP1frhL26EW%2Bnx1%2FSadtumjtT32rZU3BnUrzjkxE6z%2BfRt%2Ft8Emcf9zeUjKQmGL0auBdqch%2FauUDz2PmN0tbbzFJwspPjrqbEk2TBHadUjmExmKipt%2FZeI6s6%2Bj8dBBhVwK7YKChnekEXApwBbL4JTCEG82E7OqMAuCf62Fsg6818HcIkwB3qUCVoC9ASxg5HmgPS%2BA1i0due2%2Fp6piRl%2B7iB0L8vcWWsChwxdPB19lBUGVDS%2FS9bpP9Jcti%2FUMQaOgJ2HZJ5cyFcHjWBahXV3Dup%2B5i6GpNQ10A5UofT2nLGvYHk%2B2jdJUCDVDd7GIaPuUwmf31rgY6sQE3tvpD1RG3Fdw5Km16ZbCK9oqO2mZBA%2F9YIfSqwuXyiyv4rO0VSHs6vooUteYy4PWg2drjf%2B4ksTKEBGSIMRP10QdDYIZwbwijFuXjwqS2Oc9cEamhzDm8FlRwd7sj%2FojvIVDE2LZrp8Jtm%2Bo1r%2Ba5HY7XxQMXPzg9sWcbt8ZpqnW38EFcfx7hMPl8DommkrupQblgxp2ajixnBb2pFDf6We7sx3Jgr7t0Cy%2BgFcArO7E%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240227T071928Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY77AJ4G5C%2F20240227%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=c3af7bced64e495696448e09a8b304a2bd477d22af29d754f3679e2d8feb1c93&hash=4e542f35aa8789dd75ffb72f6adf3fa044ad62bf8003073e5d5ea0e1f5f815f1&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0885230899901286&tid=spdf-2d6e3fe4-cf54-499a-a871-2d6918b4fe83&sid=54e4f1ad7f19804c33895b44ed573490bd9fgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=10125a510d05025b0201&rr=85bea8df3da83517&cc=jp)

2. Zhijian Ou, "Energy-Based Models with Applications to Speech and Language Processing", ICASSP 2022 Tutorial. [PDF](http://oa.ee.tsinghua.edu.cn/~ouzhijian/ICASSP2022/ICASSP2022_Tutorial_EBM.pdf)

3. Bin Wang, Zhijian Ou, Zhiqiang Tan, "Learning Trans-dimensional Random Fields with Applications to Language Modeling", TPAMI, 2018. (_TRF_)

4. Radford, et al, "Improving language understanding by generative pre-training", 2018. (_GPT_)

5. Devlin, et al, "BERT: Pre-training of deep bidirectional transformers for language understanding", ACL 2019. (_BERT_)

6. Radford, et al, "Language models are unsupervised multitask learners", OpenAI Blog, 2019. (_GPT_-2)

7. Brown, et al, "Language Models are Few-Shot Learners", NeurIPS 2020. (_GPT_-3)



## Dialog Systems
- [HLT-DIAL] Discourse and Dialog

1.  **Task-Oriented Dialog Systems that Consider Multiple Appropriate Responses 
under the Same Context**. Yichi Zhang, Zhijian Ou, Zhou Yu. AAAI, 2020. [PDF](https://arxiv.org/pdf/1911.10484.pdf) (_DAMD_)
2. **A Simple Language Model for Task-Oriented Dialogue**. Ehsan Hosseini-Asl, Bryan McCann, Chien-Sheng Wu, Semih Yavuz, Richard Socher. NeurIPS, 2020. [PDF](https://arxiv.org/pdf/2005.00796.pdf) (_SimpleTOD_)
3. **Retrieval-Augmented Generation for Knowledge-Intensive NLP tasks**. Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela. NeurIPS, 2020. [PDF](https://arxiv.org/pdf/2005.11401.pdf) (_RAG_)
4. **Training language models to follow instructions with human feedback**. Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, Ryan Lowe. NeurIPS, 2022. [PDF](https://arxiv.org/pdf/2203.02155.pdf) (_InstructGPT_)

## Speech Perception and Psychoacoustics
- [SPE-SPER] Speech Perception and Psychoacoustics

## Speech Analysis
- [SPE-ANLS] Speech Analysis

## Speech Coding
- [SPE-CODI] Speech Coding

## Speech Generation
- [SPE-SPRD] Speech Production
- [SPE-SYNT] Speech Synthesis and Generation

## Speech Enhancement and Separation
- [SPE-ENHA] Speech Enhancement and Separation

## Speaker Recognition
- [SPE-SPKR] Speaker Recognition and Characterization

## Parsing
- [HLT-STPA] Segmentation, Tagging, and Parsing

## Retrieval
- [HLT-SDTM] Spoken Document Retrieval and Text Mining

1. **Dense Passage Retrieval for Open-Domain Question Answering**. Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih. EMNLP, 2020. [PDF](https://arxiv.org/pdf/2004.04906.pdf) (_DPR_)
2. **Text and Code Embeddings by Contrastive Pre-Training**. Arvind Neelakantan, Tao Xu, Raul Puri, Alec Radford, Jesse Michael Han, Jerry Tworek, Qiming Yuan, Nikolas Tezak, Jong Wook Kim, Chris Hallacy, Johannes Heidecke, Pranav Shyam, Boris Power, Tyna Eloundou Nekoul, Girish Sastry, Gretchen Krueger, David Schnurr, Felipe Petroski Such, Kenny Hsu, Madeleine Thompson, Tabarak Khan, Toki Sherbakov, Joanne Jang, Peter Welinder, Lilian Weng. arXiv:2201.10005, 2022. [PDF](https://arxiv.org/pdf/2201.10005.pdf) (_openai cpt-text, cpt-code_)

## Machine Translation
- [HLT-MTSW] Machine Translation for Spoken and Written Language

## Language Resources and Systems
- [HLT-LRES] Language Resources and Systems

## Multimodal
- [HLT-MMPL] Multimodal Processing of Language
