# CSGames Scraper

Send a message in a [Slack](https://slack.com/) channel when the [CSGames](https://csgames.org/) website of the next edition change.

This project uses [GitHub Actions](https://help.github.com/en/actions) to automate the process.

## Configuration

Add the following secrets in the GitHub repository [Secrets Settings](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/creating-and-using-encrypted-secrets):
- `SLACK_BOT_TOKEN` : Slack token to access your workspace.
- `SLACK_CHANNEL` : Slack channel id.
