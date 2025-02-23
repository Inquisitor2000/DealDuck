# DealDuck
Scraper using puppeteer (Node.js) for local eshop platforms from Moldova.

.mjs instruction using headless puppeteer for individual eshop platforms:

#Darwin.md
#Enter.md
#Pandashop.md
#Ultra.md
#Gsmshop.md
#Smart.md
#Maximum.md
#Bomba.md

Including also a customized telegram bot to parse that information to a telegram bot. Using romanian/russian commands.
Automated userbase curating system.

Promo scheduler.
Poll system.
Metrics price histogram (not yet ready).

RL_Commands

[ send_msg ]

Sends predefined messages.
C:/Users/Admin/Desktop/DealDuck/message.json

[ send_ad ]

Sends predefined ads to users at fixed time autonomously.
Can be used to send ad with aproximation to time.
Text promo defined in Promo folder .json [3promos | 2 languages].

The images follow _ro | _ru rules.
promo1 = 09:00
promo2 = 13:00
promo3 = 17:00

[ send_poll ]

Sends poll to users.
The poll is predefined inside json.
poll.json ( do not delete )
The results are stored inside PollVotes.json

[ send_update ]

Announce that the bot is updating price DB.
Always use it.

[ send_sleep ]

Announce that the bot is shutting down for the night. If neccesary.
