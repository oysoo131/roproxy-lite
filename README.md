# RoProxy Lite
A modified version of RoProxy made for self-hosting.

Setup is easy, simply deploy with the button below and configure environment variables. The KEY variable is optional, leave blank to not require an auth key.



When "KEY" environment variable is populated, a matching "PROXYKEY" header must be present. Requests must be made in the format /subdomain/path. E.g. https://games.roblox.com/docs -> https://roproxytest.heroku.com/games/docs
