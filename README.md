# slack_github_test

this repository for testing development of a slackbot that will return a random PR out of all labeled for review

lambda triggered by cloudwatch

searching
https://api.github.com/search/issues?q=label:slack-daily-pr+state:open+org:kweic
