# Project 4 Proposal

### Objective

The objective of my project is to compare and contrast the most common topics across different subreddits and use visualizations to aid my analysis and emphasize insights. For the purposes of this project, I want to look at subreddits that have unique "styles".

An example of this is r/wallstreetbets, where there are lots of "inside jokes", lingo, and other unique and repeated kinds of text. A very different type of subreddit is r/science, which is strictly moderated - no off topic comments or jokes are allowed, and any offending comments are quickly deleted by a moderator. These two different approaches to moderation result in dramatically different kinds of content, and I'm curious to examine the differences with these ML tools. My analysis will not be limited to these two subreddits - I plan on including more subreddits in my analysis - the exact subreddits are still TBD, but they will have "unique styles".


### How

I plan to try all the different tools we have been introduced to. In my notebooks, I plan on exploring the differences in results between nltk / spaCy and countVectorizer / TF-IDF.

I plan to use LDA and NMF for topic modelling, and compare/contrast the results. I will use K-Means for clustering, and visualize these results with something like Plotly or Tableau (will use Seaborn and Matplotlib for preliminary analysis).

Finally, I want to create a flask app to display the final results. Maybe an interactive demonstration on the app would allow the user to experiment with different numbers of clusters in the K-Means algorithm and see what topics are returned.

---
