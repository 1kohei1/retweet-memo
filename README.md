# retweet-memo
Use retweet as memo and look them back

# Features

* Instant sync with your retweets
* Easy to bulk update category
* Keep retweeted tweet even the author deleted it
* Strong search (possibly)(really nice to have)
* Add custom note to it (any string other than hashtag will be a note)
* Theme switcher (nice to have)

# How it works

1. Retweet with comment with hashtags
2. Hashtag will be a category 

# How technically works

1. Get third app authentication from twitter
2. Create IFTT which listens when signed up user retweets (needs research)
3. The action will be sending that tweet to our micro service
4. Analyze the hashtag and record them

# Tech stack

* Firebase (for real time documentation sync)
* GCP or any cloud service that can be easily scaled without less stress
* React Native
* Electron
* React
