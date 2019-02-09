## Coreference Resolution

Tips for Feature Construction of Mentions:
- Engineering the surrendings of the mention
- Add additional information about the mention

Workflow:
- Extract Mentions
- Extract relevent words of the mentions
- Based on the corpus, generate embeddings for each mention
- Perform pair-wise ranking

> Packages
> 
[1] [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP)
[2] [Spacy](https://spacy.io/)
[3] [NeuralCoref](https://github.com/huggingface/neuralcoref)

> Online Resources
> 
[1] [Stanford Course](http://web.stanford.edu/class/cs224n/)

> References
[1] [NeuralCoref Medium Blog](https://medium.com/huggingface/state-of-the-art-neural-coreference-resolution-for-chatbots-3302365dcf30)
[2] [Deep Reinforcement Learning for Mention-Ranking Coreference Models](https://cs.stanford.edu/people/kevclark/resources/clark-manning-emnlp2016-deep.pdf)
[3] [Improving Coreference Resolution by Learning Entity-Level Distributed
Representations](https://cs.stanford.edu/people/kevclark/resources/clark-manning-acl16-improving.pdf)
[4] [Recent Advance in Word Embeddings](https://arxiv.org/pdf/1706.00286.pdf)