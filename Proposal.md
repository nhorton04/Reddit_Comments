# Project 4 Proposal

### Objective

The objective of this project is to build a tweet generator. Specifically, a Trump tweet generator... :face_palm: Ideally, the generator will take a topic as input and produce a tweet about the topic.

### Why

Although we don't really need more Trump tweets than already exist, it seems like a good subject for this project because the tweets are characteristically disjointed - so there will be some cushion room for unnatural-sounding generated speech - but at the same time, they adhere to a specific formula that is quickly recognizable by the 'eye test'.

### How

I plan to try out different generative models. So far I've played around with training an LDA model on the corpus, but I want to get more advanced and try gpt-3. I just discovered gpt-3  - I tried to get gpt-2 working, but there are compatibility issues with tensorflow 2.0.

I also trained a model with textgenrnn, which seemed to get better preliminary results than the LDA model.

Finally, I want to create a flask app for inputting a topic, and returning a tweet about said topic. Maybe the flask app will contain a drop-down menu for trying different models for generation.

### Fallback

If this starts to seem like too much, I will just do topic modelling on the tweets dataset and visualize clusters of different topics.

---

*Dataset:*

The data was collected from http://www.trumptwitterarchive.com/archive
