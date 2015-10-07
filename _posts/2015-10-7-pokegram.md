---
layout: post
title: "Pokemon in Telegram"
description: "Pokemon-based game in Telegram messenger."
tags: [pokemon, telegram]
comments: true
---

After 3 years of abandonment, I think I will finally fill this blog with something :smile:. Today I want to talk about my last side project, which is _PokeGramBot_. 

When it was almost the end of the semester, a friend asked me to help him on deciding which messenger platform that can be used as a bot development platform. The bot objectives is to store a chat group members progress on their activity. With certain command, a group member can store and asks their progress on some activity. The members can also compete with other group to reach certain achievement. There are a lot of other features, but I will not explain all of them here.

So, what messenger platform is suitable? There are a few messenger platform to choose from. Sadly, most of them doesn't open their bot API to public. WhatsApp falls on this category. Although a lot of people uses WhatsApp messenger, and there are some unofficial WhatsApp API on GitHub that enable something similar to developing chat bot, but we feel that it was not good and unstable enough. The same can be said for LINE chat. Although there are some LINE applications that uses bot, we think that it was only limited to official LINE application or affiliated party application. Slack looked promising as a bot development platform, but I personally thought that Slack was too complex, and that it would be overkill to use it for such application described before. And the last one is Telegram. It looks really really similar to WhatsApp, so users migrating from the already popular WhatsApp won't be too overwhelmed and confused. Even better is that it is an open source application, so we can play around with its already available Bot API (https://core.telegram.org/bots/api) without much worries. Also, it proclaimed that it is faster, way more secure and free (https://telegram.org/faq#q-how-is-telegram-different-from-whatsapp) :smiling_imp:. So we decide to choose Telegram to develop a bot application since it is an open source project, provided an open Bot API that easy to use, and an interface that looked very similar to WhatsApp.

In this post, I actually won't explain how to create the application described before :stuck_out_tongue:. Because of this event, I actually got motivated to try make something out of this Bot API. So, I decided to make a simple game.

## How the Telegram Bot API works

To create a bot, first you must talk to the Telegram's Bot Godfather, BotFather (https://telegram.me/botfather). Talk to the BotFather via the Telegram messenger app, and create you own bot app. You can follow the steps here: https://core.telegram.org/bots#botfather.

(to be continued)

Telegram Bot API (https://core.telegram.org/bots/api) + 
PokeAPI (http://pokeapi.co/) + 
Firebase API (https://www.firebase.com/) + 
Lumen (http://lumen.laravel.com/) + 
Heroku (https://www.heroku.com/)
= @PokeGramBot, Messenger based "Pokemon" Game in Telegram :smile:
Try it here: https://telegram.me/PokeGramBot
