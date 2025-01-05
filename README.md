This is a Twitter Bot that will  add friends and Direct Message automatically without being banned or shadow banned by the api/community

his project utilizes the Tweepy library to interact with the Twitter API, enabling automated actions such as tweeting, liking, retweeting, and streaming real-time tweets based on defined rules. Here's a breakdown:

Setup and Authentication:

The script begins by authenticating with Twitter using API keys, secrets, and tokens.
Two methods are employed: tweepy.Client (for modern API v2 operations) and tweepy.API (for older API v1.1 operations).
Basic Twitter Interactions:

Functions like creating tweets, liking, retweeting, replying, and fetching timelines or user tweets are demonstrated with commented-out examples.
For instance, a tweet is created, and tweets from a specific user's timeline (e.g., "narendramodi") are fetched and printed.
