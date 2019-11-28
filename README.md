# CSGames Scraper

Envoie un message dans un "channel" Slack lorsque le site web des [CSGames](https://csgames.org/) change pour l'année courante.

Ce projet utilise les [GitHub Actions](https://help.github.com/en/actions) pour automatiser le processus.

## Configuration

Ajouter les secrets suivant au dépôt GitHub via dans la [section Secrets des Settings](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/creating-and-using-encrypted-secrets):
- `SLACK_BOT_TOKEN` : le jeton Slack permettant de communiquer dans un "workspace" Slack.
- `SLACK_CHANNEL` : l'identifiant du "channel" Slack.
