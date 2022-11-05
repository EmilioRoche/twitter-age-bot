# Demo for simple Python Twitter Bot

## What?

A twitter use can @fruta_bot asking about calories in a specific fruit, and the bot will auto reply with the correct response about the fruit and its calories. Keyword(s) is specified to "calories", and can filter out what fruit is mentioned in the tweet.

## Why?

* I built this twitter bot so I could have some more practice using Python, as well as build something fun that isn't web or application specific. I like to continue learning other applications.

## How?

* The twitter bot uses the Twitter Developer Platform, specifically the Twitter API. For the fruit data, I use a free external API provided by [fruityvice] (https://www.fruityvice.com/). When the fruit string is parsed out of the tweet, I do an API call to this API and get back the calories information.

### Demo for when a user tweets about a valid fruit and uses correct keywords
![Demo](https://user-images.githubusercontent.com/32501779/200094262-761d5cfd-6b38-481f-b38d-e55789412b27.gif)
