# Discord Troll Database (short: DTDB)
A global database for Discord trolls, idiots and leecher snitches in order to keep them out of your server. Cause exposing noobs is fun!


## General Discord Hardening
* Use [DiscordCrypt](https://gitlab.com/leogx9r/DiscordCrypt) (or alternative [SimpleDiscordCrypt](https://gitlab.com/An0/SimpleDiscordCrypt) - **THEY ARE NOT COMPATIBLE TO EACH OTHER**) to get end-to-end encryption!
* In general use as less as possible Bots (they can expose you or people can search how to bypass them), use [webhooks](https://birdie0.github.io/discord-webhooks-guide/services/ifttt.html) instead
* Use [Rules Bot](https://discordbots.org/bot/rulesbot) in order to keep bots out and to verrify everyone read the rules before they see any channel
* Turn off the Discord "[Explicit Content Filter](https://blog.discordapp.com/discord-safety-boost-2d592ea3b14a?gi=af380bd8186a)" because this also sends statistics etc back
* Set the verification level to at least 5 Minutes (or higher) - Most people won't join you if you require a phone verification number, and it also exposes your number to Discord itself.
* Don't use any [Server Integrations](https://discordapp.com/streamkit) because this is tracking it's users for statistics etc.
* Enable the Widget to create ONE invite channel (the rules channel).
* (optional) You can use I2P/Tor to route the Discord traffic through  it but it's not necessary since the Discord traffic from and to the server is encrypted and protected against MITM. Discord itself uses TLS for text chat, etc and DTLS for voice over browser, xsalsa20 for voice over desktop app.


## Why not use a pre-made or self-hosted Bot to blacklist?
* Simple, no transparency. 
* No control or no options to undo something once they are in a hidden database. The bots itself might leak/expose or even track you and your user/channel/server.
* Bots like [Gaius Bot](https://gaiusbot.me) want money for _pro_ functions.


## To-Do

- [ ] Finish the webhook (WIP)
- [ ] Add an auto-update mechanism e.g. re-check the database every 12/24-hours 
- [ ] Maybe a whitelist only mode?
- [ ] Get some maintainers to help this little project 
