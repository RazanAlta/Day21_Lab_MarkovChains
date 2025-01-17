# Day21_Lab_MarkovChains

![image](https://user-images.githubusercontent.com/87912604/202931625-9087af1b-27d5-47a4-affe-b320a29b14bf.png)
# Markov Chains 
- A Markov chain is a stochastic model created by Andrey Markov that outlines the probability associated with a sequence of events occurring based on the state in the previous event.

# Usage:
- financial modeling.
- Google’s page rank algorithm, which determines what links to show first in its search engine, is a type of Markov chain. Through mathematics.
- NLP,text generation.

# short explination
 - MarkOv chains uses our observations to predict an approximation of future events.
 
 
 Example of NLP text generation using MArkov chains:
 https://builtin.com/sites/www.builtin.com/files/styles/ckeditor_optimize/public/inline-images/2_markov-chain.jpg
 
 ## what is subreddit ?
 - Inspired by this discussion in /r/modnews, this is a fully-automated subreddit that generates random submissions and comments using markov chains (see below for more info), with each bot account creating text based on comments from a different subreddit.
 
How are the comments/submissions created?

- The text for titles/comments/text-posts are generated using "markov chains", a random process that's "trained" from looking at real data. If you've ever used a keyboard on your phone that tries to predict which word you'll type next, those are often built using something similar.

## How are the comments/submissions created?

- You feed in a bunch of sentences and even though it has no understanding of the meaning of the text, it picks up on patterns like "word A is often followed by word B". Then when you want to generate a new sentence, it "walks" its way through from the start of a sentence to the end of one, picking sequences of words that it knows are valid based on that initial analysis. So generally short sequences of words in the generated sentences will make sense, but often not the whole thing.
 
 
 
 
the reddit bot: https://www.reddit.com/user/SubredditSim-SS
