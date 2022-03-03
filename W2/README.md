# Table of content

2. Week 2
    1. Smoothing
    2. LM Evaluation
    3. Introduction to Neural Processing
        1. Neural Networks
        2. Feedforward Networks
    4. Neural LM


# Smoothing:
smoothing is a cross domain concept, applied in many cases (namely [lable smoothing in machine learning](https://www.linkedin.com/pulse/label-smoothing-solving-overfitting-overconfidence-code-sobh-phd)). Here we focus on smooting in probabilistic language models, epecifically n-gram language models.



# LM Evaluation:

## Entropy concept:

+ [Entropy and information theory](https://www.youtube.com/watch?v=_PG-jJKB_do)
+ [Entropy and tranmiting data and huffman coding](https://www.youtube.com/watch?v=M5c_RFKVkko)
+ [Where the hell comes from the entropy fomula](https://www.youtube.com/watch?v=YtebGVx-Fxw)
+ [Entropy and cross-entropy](https://www.youtube.com/watch?v=ErfnhcEV1O8)
+ [the-relationship-between-perplexity-and-entropy-in-nlp](https://towardsdatascience.com/the-relationship-between-perplexity-and-entropy-in-nlp-f81888775ccc)
+ [Entropy and preplixity and its application in language models evaluation](https://www.youtube.com/watch?v=NCyCkgMLRiY&t=9s)


# Neural Language Models:

## Basics: 
> [Neural Network Architectures & Deep Learning](https://www.youtube.com/watch?v=oJNHXPs0XDk)

> [Train vs Validation/development vs test/holdout   ](https://towardsdatascience.com/train-validation-and-test-sets-72cb40cba9e7)

> [Train/val/test  link2](https://www.datarobot.com/wiki/training-validation-holdout/)

> [Epoch vs (mini)Batch vs Batch size vs  number_of_batches/ Steps_per_epoch/ number_of_iterations](https://towardsdatascience.com/epoch-vs-iterations-vs-batch-size-4dfb9c7ce9c9)

[Advantages of splitting train data into smaller chuncks (mini-batch) than sending whole training into optimizaiton process at once]()

    1. It just uses less RAM
    
    So, Why not a mini-batch of size 1?
        + larger mini-batch helps generalization
        + Alongsides the previous reseaon, single sample has a sharp fluctuation of loss funtion in training process
        + More importantly, due to "special" tensor operation, processing 2 batches of 10 samples is faster than 20 samples 

## Optimization
> [Backward / 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

> [Linear Regression with SGD / AI-Singapore](https://aisingapore.org/tags/linear-regression/)

## Activation Functions
> [Softmax vs Simple probability function](https://stats.stackexchange.com/questions/189331/why-is-the-softmax-used-to-represent-a-probability-distribution)

## Criterion/ Metric/ Loss function
.

## Debugging: 
> [How to diagnose ML models?](https://machinelearningmastery.com/learning-curves-for-diagnosing-machine-learning-model-performance/) 

> [Troubleshootin Neural Networks UC Berkely](https://www.youtube.com/watch?v=f1JRFu7X-c8)


# W2 Further reading:

> **Token vs word** : by Yaakov HaCohen-Kerner added an answer June 29, 2014
A simplified definition of a token in NLP is as follows: A token is a string of contiguous characters between two spaces, or between a space and punctuation marks. A token can also be an integer, real, or a number with a colon (time, for example: 2:00). All other symbols are tokens themselves except apostrophes and quotation marks in a word (with no space), which in many cases symbolize acronyms or citations. A token can present a single word or a group of words (in morphologically rich languages such as Hebrew) as the following token "ולאחי" (VeLeAhi) that includes 4 words "And to my brother".
A stirng as written by one of the previous researchers who responded
is a oncept taken from programming languages.
