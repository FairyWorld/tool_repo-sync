# Contributing

🙌🏻 🙌🏼 🙌🏽 🙌🏾 🙌🏿

Thanks for your interest in contributing to this project! Before making any contributions, be sure to read the [Code of Conduct](CODE_OF_CONDUCT.md).

## Development

1. Create a Github OAuth app with callback url `http://localhost:3000`
2. Create .env from .env.example and fill out the values
3. Run `script/server`

## Production (Heroku)

1. Create a Heroku app
2. Create a Github OAuth App with Heroku app domain as the callback url
3. Add config vars from `.env` under Heroku app settings
4. Add build packs `heroku/nodejs` and `https://github.com/wei/heroku-buildpack-static.git` under heroku app settings
5. Deploy to Heroku