# random_image_bot
a flickr / twitter / tumblr bot that finds photos of within a coordinate box and posts google maps links along with the photo

example here [twitter @randomiceland](https://twitter.com/randomiceland/media)

the included credentials are my encrypted credentials

your credentials.json should contain your keys, tokens, and secrets, and have the format:

```
{
  "flickr": {
    "api_key": "",
    "secret": ""
  },
  "tumblr": {
    "consumer_key": "",
    "consumer_secret": "",
    "token": "",
    "token_secret": ""
  },
  "twitter": {
    "consumerKey": "",
    "consumerSecret": "",
    "callback": "http://...",
    "accessToken": "",
    "accessSecret": ""
  }
}

```
