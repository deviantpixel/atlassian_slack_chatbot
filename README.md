# atlassian_slack_chatbot

> Slackbot built with Node.js and Slackbots.js that provides Atlassian confluence  information results for a custom chatbot.

## APIs Used:
[http://someURL.forumone.com/api/](http://someURL.forumone.com/api/)

## Slackbots (slack-bot-api)
[https://github.com/mishk0/slack-bot-api](https://github.com/mishk0/slack-bot-api)

## Quick Start

``` bash
# Install dependencies
npm install

# Serve on localhost:3000
npm start

# Create bot in Slack and generate and include your OAuth bot token

# Change the Bot name from yourbotname to your desired bot name

# Add your Atlassian api key to the getAtlassianSearchResult function

# Update the URLs in getAtlassianSearchResult by changing from https://yourDomain.atlassian.net... to your Atlassian confluence domain.

# Update the handleMessage function calls to your confluence channel name(s)

# Update all messages as desired
```

## App Info

### Author

Keenan Holloway
[Keenan Holloway](https://github.com/deviantpixel)

### Version

1.0.0

### License

This project is licensed under the MIT License
