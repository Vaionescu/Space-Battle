# Space Battle

* Fork of Guardian Coding Challenges repo, repurposed for further dev of Space Battle (the game) *

## Introduction

**Space Battle** is a game born out of (more exactly evolved from) the weekly Guardian engineering coding challenges of Summer 2018.

The game has three kind of objects: **Capital Ships**, **Battle Cruisers** and **Energy Carriers**. The main idea is simple: you control a space fleet and your objective is to destroy enemy space ships before they destroy yours.

You could play on the command line, as all the actions (from generating energy to building or moving your ships and shooting at enemies) are simple HTTP requests. You may also want to build a bot, in the programming language of your choice, and let it play for you. There will be a game client, if you want to play in real-time.

A new game starts at the beginning of every hour. This means that if you make some mistakes, don't worry, you get a fresh start at the next hour.

## Playing

Right now the game server is being rewritten in Python 3. A game client is also planned.

The game server will host several worlds.

Each world can be of the following types:
 - Realtime PVP: Players fight against each other.
 - Realtime PVE: Only one player. The player fights against bots.
 - Bot Wars: The players can join using bots they have written.

### How do I join?

Players need a UserKey to interact with the game server. The UserKeys will be generated upon request (for now).

### Where can I find the game server?

There is no official server right now, although there will be one.

### What should I do first?

You can either wait for the game client to be created, or try and make your own client! (or a bot, for the "Bot Wars" worlds)

Everything you need to know in order to play can be found in the game manuals.

## Game manuals

- **game_api.md**: Read this if you intend to play using HTTP requests, create your own game client or develop a bot.
- **game_rules.md**: More details about the game and the rules.
- **game_urls.txt**: Quick sum-up of all the end points.

## Roadmap

The rough roadmap is:
- Rewrite the game server in Python 3
- Create a game client in Python 3

~The API and game rules can evolve through user requests (not necessarily in backwards compatible ways), so don't hesitate to hit me up with a request or an idea.~

## Acknowledgements

The original game is the result of the hard work of the people at Guardian. It will be further developed by myself.
