# i-heart-this-city
A Twitter bot that tweets out the worst shirt designs for tourists.

## Requirements
Before you start with this repo, you'll need to get some system requirements for [`node-canvas`](https://github.com/Automattic/node-canvas#installation). Once that's setup use `npm install`.

You'll then need to create a `twitter.json` file from the `twitter.example.json` file. This should be populated with Twitter API keys. If you need to authenticate for other twitter user. You'll need to run `npm install optimist oauth step colors` and then use `node auth.js --key=TWITTER_API_KEY --secret=TWITTER_API_SECRET` to get a pair of access keys.

## Development
You can run the main script `tweet.js` by using `npm run tweet`. This will send a tweet to [@ilikethiscity](https://twitter.com/ilikethiscity).