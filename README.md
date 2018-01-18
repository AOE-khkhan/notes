
<p align="center">
  <img src="images/logo.png" width=250>
</p>

<p align="center">

  <a href="https://github.com/hb-research/notes">
    <img src="https://img.shields.io/badge/DeepLearning-Notes-brightgreen.svg" alt="Project Introduction">
  </a>
  
  <a href="https://github.com/hb-research/notes">
    <img src="https://img.shields.io/badge/Summary-Code-brightgreen.svg" alt="Project Introduction">
  </a>

</p>

# notes: Notes of Deep Learning

## Category 

- [Background knowledge](#background-knowledge)
- [AI](#ai)
- [Computer Vision](#computer-vision)
- [Natural Language Processing](#natural-language-processing)
- [Optimization](#optimization)
- [Unsupervised & Generative](#unsupervised--generative)

---



## Background knowledge

- [Gaussian Process](notes/gausian_process.md) ****`Supervised`****, ****`Regression`****
- [Importance Sampling](notes/importance_sampling.md) ****`Approximate`****

---

- Deep Learning (2015) ****`Review`****
	- [nature](http://www.cs.toronto.edu/~hinton/absps/NatureDeepReview.pdf) | [note](notes/deep_learning.md)


## AI

- Building Machines That Learn and Think Like People (2016. 4)
	- ****`Cognitive`****, ****`Human-Like`****
	- [arXiv](https://arxiv.org/abs/1604.00289) | [note](notes/ml_learn_and_think_like_human.md) | [the morning paper](https://blog.acolyer.org/2016/11/25/building-machines-that-learn-and-think-like-people/)

## Computer Vision

- Deep Residual Learning for Image Recognition (2015, 12)
	- ****`Residual`****, ****`ImageNet 2015`****
	- [arXiv](https://arxiv.org/abs/1512.03385) | [note](notes/residual_network.md)


## Natural Language Processing

- Convolutional Neural Networks for Sentence Classification (2014. 8) 
	- ****`First CNN`****
	- [arXiv](https://arxiv.org/abs/1408.5882) | [code](https://github.com/DongjunLee/text-cnn-tensorflow) 
- Neural Machine Translation by Jointly Learning to Align and Translate (2014. 9) 
	- ****`Seq2Seq`****, ****`Attention(Align)`****, ****`Translation`****
	- [arXiv](https://arxiv.org/abs/1409.0473) | [note](notes/bahdanau_attention.md) | [code](https://github.com/DongjunLee/conversation-tensorflow) 
- Text Understanding from Scratch (2015. 2) 
	- ****`CNN`****, ****`Character-level`****
	- [arXiv](https://arxiv.org/abs/1506.07285)
- Ask Me Anything: Dynamic Memory Networks for Natural Language Processing (2015. 6) 
	- ****`Memory`****, ****`QA`****, ****`bAbi`****
	- [arXiv](https://arxiv.org/abs/1506.07285) | [code](https://github.com/DongjunLee/dmn-tensorflow) 
- Pointer Networks (2015. 6) 
	- ****`Seq2Seq`****, ****`Attention`****, ****`Combinatorial`****
	- [arXiv](https://arxiv.org/abs/1506.03134) | [note](notes/pointer_network.md) 
- Skip-Thought Vectors (2015. 6) 
	- ****`Sentence2Vec`****, ****`Unsupervised`****
	- [arXiv](https://arxiv.org/abs/1506.06726) | [note](notes/skip_thought.md)
- A Neural Conversational Model (2015. 6) 
	- ****`Seq2Seq`****, ****`Conversation`****
	- [arXiv](https://arxiv.org/abs/1506.05869)
- Teaching Machines to Read and Comprehend (2015. 6) 
	- ****`Deepmind`****, ****`Attention`****, ****`QA`****
	- [arXiv](https://arxiv.org/abs/1506.03340) | [note](notes/teaching_machine_read_and_comprehend.md)
- Effective Approaches to Attention-based Neural Machine Translation (2015. 8) 
	- ****`Seq2Seq`****, ****`Attention`****, ****`Translation`****
	- [arXiv](https://arxiv.org/abs/1508.04025) | [note](notes/luong_attention.md) | [code](https://github.com/DongjunLee/conversation-tensorflow) 
- Character-Aware Neural Language Models (2015. 8) 
	- ****`CNN`****, ****`Character-level`****
	- [arXiv](https://arxiv.org/abs/1508.06615)
- Neural Machine Translation of Rare Words with Subword Units (2015. 8) 
	- ****`Out-Of-Vocabulary`****, ****`Translation`****
	- [arXiv](https://arxiv.org/abs/1508.07909) | [note](notes/subword_nmt.md)
- A Diversity-Promoting Objective Function for Neural Conversation Models (2015. 10) 
	- ****`Conversation`****, ****`Objective`****
	- [arXiv](https://arxiv.org/abs/1510.03055) | [note](notes/diversity_conversation.md)
- Multi-task Sequence to Sequence Learning (2015. 11) 
	- ****`Multi-Task`****, ****`Seq2Seq`****
	- [arXiv](https://arxiv.org/abs/1511.06114) | [note](notes/multi_task_seq2seq.md)
- Multilingual Language Processing From Bytes (2015. 12) 
	- ****`Byte-to-Span`****, ****`Multilingual`****, ****`Seq2Seq`****
	- [arXiv](https://arxiv.org/abs/1512.00103) | [note](notes/byte_to_span.md)
- Strategies for Training Large Vocabulary Neural Language Models (2015. 12) 
	- ****`Vocabulary`****, ****`Softmax`****, ****`NCE`****, ****`Self Normalization`****
	- [arXiv](https://arxiv.org/abs/1512.04906) | [note](notes/vocabulary_strategy.md)
- Recurrent Memory Networks for Language Modeling (2016. 1) 
	- ****`RMN`****, ****`Memory Bank`****
	- [arXiv](https://arxiv.org/abs/1601.01272)
- Exploring the Limits of Language Modeling (2016. 2) 
	- ****`Google Brain`****, ****`Language Modeling`****
	- [arXiv](https://arxiv.org/abs/1602.02410) | [note](notes/exploring_limits_of_lm.md)
- Incorporating Copying Mechanism in Sequence-to-Sequence Learning (2016. 3) 
	- ****`CopyNet`****, ****`Seq2Seq`****
	- [arXiv](https://arxiv.org/abs/1603.06393) | [note](notes/copynet.md)
- Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models (2016. 4) 
	- ****`Translation`****, ****`Hybrid NMT`****, ****`Word-Char`****
	- [arXiv](https://arxiv.org/abs/1604.00788) | [note](notes/nmt_hybrid_word_and_char.md)
- Attention Is All You Need (2017. 6) 
	- ****`Self-Attention`****, ****`Seq2Seq (without RNN, CNN)`****
	- [arXiv](https://arxiv.org/abs/1706.03762) | [note](notes/transformer.md) | [code](https://github.com/DongjunLee/transformer-tensorflow)  
- Neural Text Generation: A Practical Guide (2017. 11) 
	- ****`Seq2Seq`****, ****`Decoder Guide`****
	- [arXiv](https://arxiv.org/abs/1711.09534) | [note](notes/neural_text_generation.md)
- Recent Advances in Recurrent Neural Networks (2018. 1) 
	- ****`RNN`****, ****`Recent Advances`****, ****`Review`****
	- [arXiv](https://arxiv.org/abs/1801.01078)


## Optimization

- Dropout (2012, 2014) 
	- ****`Regulaizer`****, ****`Ensemble`****
	- [arXiv (2012)](https://arxiv.org/abs/1207.0580) | [arXiv (2014)](https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf) | [note](notes/dropout.md)
- Batch Normalization (2015. 2) 
	- ****`Regulaizer`****, ****`Accelerate Training`****, ****`CNN`****
	- [arXiv](https://arxiv.org/abs/1502.03167) | [note](notes/batch_normalization.md)
- Training Very Deep Networks (2015. 7) 
	- ****`Highway`****, ****`LSTM-like`****
	- [arXiv](https://arxiv.org/abs/1507.06228) | [note](notes/highway_networks.md)
- Deep Networks with Stochastic Depth (2016. 3) 
	- ****`Dropout`****, ****`Ensenble`****, ****`Beyond 1000 layers`****
	- [arXiv](https://arxiv.org/abs/1603.09382) | [note](notes/stochastic_depth.md)
- Layer Normalization (2016. 7) 
	- ****`Regulaizer`****, ****`Accelerate Training`****, ****`RNN`****
	- [arXiv](https://arxiv.org/abs/1607.06450) | [note](notes/layer_normalization.md)

	
	
## Unsupervised & Generative

- Auto-Encoding Variational Bayes (2013, 12)
	- ****`Generative`****, ****`Approximate`****
	- [arXiv](https://arxiv.org/abs/1312.6114) | [note](notes/vae.md)
