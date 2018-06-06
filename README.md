# Tootbot

This is a Python bot that looks up posts from specified subreddits and automatically posts them on Twitter and/or [Mastodon](https://joinmastodon.org/). It is based on [reddit-twitter-bot](https://github.com/rhiever/reddit-twitter-bot). Tootbot was created for the [@ItMeIRL](https://twitter.com/ItMeIRL) Twitter account, and is now used on a variety of other accounts.

**Features:**

* Tootbot can post to both Twitter and [Mastodon](https://joinmastodon.org/)
* Media from direct links, Gfycat, Imgur, Reddit, and Giphy is automatically attached in the social media post (unless the video file is too large or cannot be converted into a GIF)
* Links that do not contain media can be skipped, ideal for meme accounts like [@ItMeIRL](https://twitter.com/ItMeIRL)
* NSFW content and self-posts can be filtered
* Tootbot can monitor multiple subreddits at once
* Tootbot is fully open-source and runs locally, so you don't have to give an external service full access to your social media account(s)

Tootbot uses the [tweepy](https://github.com/tweepy/tweepy), [PRAW](https://praw.readthedocs.io/en/latest/), [py-gfycat](https://github.com/ankeshanand/py-gfycat), [imgurpython](https://github.com/Imgur/imgurpython), [Pillow](https://github.com/python-pillow/Pillow), and [Mastodon.py](https://github.com/halcy/Mastodon.py) libraries.

## Disclaimer

The developers of Tootbot hold no liability for what you do with this script or what happens to you by using this script. Abusing this script *can* get you banned from Twitter, so make sure to read up on proper usage of the Twitter API.

## Setup and usage

For instructions on setting up and using Tootbot, please visit [the wiki](https://github.com/corbindavenport/tootbot/wiki). **Heroku support is under development, but it does not work yet.**