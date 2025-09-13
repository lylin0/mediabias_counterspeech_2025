# Counterspeech for Mitigating the Influence of Media Bias: Comparing Human and LLM-Generated Responses

This repository contains the dataset presented in the paper "Counterspeech for Mitigating the Influence of Media Bias: Comparing Human and LLM-Generated Responses".

# Overview
This dataset is developed based on the dataset [BAT – Bias And Twitter](https://www.sciencedirect.com/science/article/pii/S246869642300023X), and takes a step further by linking media bias, offensive comments, and counterspeech. This dataset is annotated through MTurk, more details can be found in our [paper](https://arxiv.org/pdf/2508.15855) and the structure is shown in Figure 1.

- Media Bias
  
  The news articles and political bias, reliability scores are from Ad Fontes Media’s website. Specifically, the articles are divided into 4 reliability classes (Reliable,
Generally Reliable, Mixed Reliability, and Unreliable) and 5 bias classes (HyperPartisan Left, Skews Left, Middle, Skews Right, and Hyper-Partisan Right).

- Comments

  Comments on news articles are from Twitter. They are labeled by:
  
  CQ1: Is there at least a term, or expression with any pejorative connotation?

  CQ2: Are there terms, or expressions with any pejorative connotation used against hate target groups?
  
  CQ3: Does the Comment support or oppose the Article?

- Counterspeech
  
  The reply to the offensive comments would be labeled by:

  RQ1: Please determine whether the Reply is a counterspeech. 
  If it is a counterspeech, please directly select its strategy.

  There are 9 categories:
  
  A. Affiliation: Depicting a positive affective relationship;
  
  B. Counter question: Questioning the message;
  
  C. Denouncing: Denounce the message as being hateful;
  
  D. Hostile language: Abusive, hostile, or obscene response;
  
  E. Humor and sarcasm: Humorous or sarcastic response;
  
  F. Pointing out hypocrisy or contradiction: Points out the hypocrisy or contradiction;
  
  G. Positive tone: Use empathic, kind, polite, or civil speech;
  
  H. Presenting facts: Tries to persuade by correcting misstatements;
  
  I. Warning of consequences: Warns of possible consequences of actions.

  If the reply is a counterspeech but not included in these 9 categories, it will be labeled by J. Other.


# Citation
@article{lin2025counterspeech,
  title={Counterspeech for Mitigating the Influence of Media Bias: Comparing Human and LLM-Generated Responses},
  author={Lin, Luyang and Feng, Zijin and Wang, Lingzhi and Wong, Kam-Fai},
  journal={arXiv preprint arXiv:2508.15855},
  year={2025}
}
