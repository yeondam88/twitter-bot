# twitter-bot

```
To start a twitter bot
you would need to add your config.js file to the directory.

//config.js
/** TWITTER APP CONFIGURATION
 * consumer_key
 * consumer_secret
 * access_token
 * access_token_secret
 */
 
 module.exports = {
      consumer_key: 'YOUR KEY',
      consumer_secret: 'YOUR SECRET',
      access_token: 'YOUR TOKEN',
      access_token_secret: 'YOUR TOKEN SECRET'
 };
//

npm start

```

## Features
### 1. Retweet Bot
      - Find latest tweet according the query in params (Every 50 min, it will restart)
### 2. Favorite Bot
      - Find a random tweet and 'Favorite' it (Every 60 min, it will restart)
### 3. Auto reply when someone follows
      - When someone follows the bot, it automatically reply to that person.



### TODO: Add more features... 
