# GroupMe bot that is created from Hubot repo
### Deploying to Heroku

1. Fork the repository to your GitHub account
    - And please star it to show your support. It's free for you and helps me a lot :yellow_heart:
2. Log in to Heroku
3. Create a new app
4. Deploy from your GitHub and select the repo
5. Configure environment variables (and optionally Redis)


### Configuration

Start by configuring the environment variables below:

- HUBOT_GROUPME_TOKEN
- HUBOT_GROUPME_ROOM_ID
- HUBOT_GROUPME_BOT_ID

And optionally configure a Redis server for blacklist persistence.


### Running

Once configured, you can run the bot with `./bin/hubot -a groupme`. 

You should now be able to open the GroupMe room you've chosen and tag everyone in the group by mentioning **@all**!
