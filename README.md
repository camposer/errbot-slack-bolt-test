# Errbot Slack Bolt Test

Simple demo app using [Errbot Slack Bolt Backend](https://github.com/attakei-lab/errbot-slack-bolt-backend).

## Getting started

1. Create a Slack App as defined in [manifest.yml](manifest.yml)

2. Install dependencies: `pip install -r requirements.txt`

3. Initialize errbot: `errbot --init`

4. Create an `.env` file with the following variables:
```
SLACK_APP_TOKEN=<slack-app-token>
SLACK_BOT_TOKEN=<slack-bot-token>
SLACK_ADMINS=@slack_handle
```

5. Start errbot: `errbot`

6. Create a channel, invite `Errbot Bolt Test` and enter: "!help" or "!tryme"
