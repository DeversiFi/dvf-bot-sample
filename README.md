# dvf-bot-sample

Simple bot implementation for DeversiFi.
After registering and depositing ETH, the bot will start selling/buying every 60 seconds.

## Setup

To install all packages and dependencies run:

```bash
  npm install
```

Make sure you add your data to config.js

```js
module.exports = {
  API_URL: "https://api.stg.deversifi.com",
  PROVIDER_URL: "YOUR PROVIDER URL (INFURA)",
  PRIVATE_KEY: "YOUR PRIVATE KEY",
};
```

After the config file is completed run the following script to register and deposit all your ETH.

```bash
  npm run setup
```

## Trade

To start running the bot:

```bash
  npm start
```
