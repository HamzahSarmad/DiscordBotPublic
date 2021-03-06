# Discord Bot Public (README UPDATE PENDING)

## Table of Contents

* [Introduction](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)
* [Commands](#commands)

## Introduction

A general bot with some emphasis on simps as well as some other general functionality such as a basic leveling system.
## Technologies
* Python ver 3.8.2
* discord.py ver 1.3.3
* praw ver 7.0.0
* mysql-connector-python ver 8.0.19

## Setup
To run this bot first you need to install all of the required libraries listed in the technologies.
* [Installing and getting started with discord.py](https://discordpy.readthedocs.io/en/latest/intro.html)
* [Installing and getting started with mysql database for python](https://pythonspot.com/mysql-with-python/)
* [Installing mysql-connector for python](https://www.mysqltutorial.org/getting-started-mysql-python-connector/)
* [Installing reddit PRAW library](https://praw.readthedocs.io/en/latest/getting_started/installation.html)
* [Getting started with PRAW](https://praw.readthedocs.io/en/latest/getting_started/quick_start.html)

Once all of the required libraries are installed replace all the required key values.
To run the bot open commmand prompt and run the following command replacing "bot" with the name of the bot:
```
py public.py
```

## Commands
### List of the current commands for this bot:
* __-commands__ bring up a list of commands
* __-Acommands__ brings up a list of admin commands
* __-enlighten__ sends a paragraph of text to the channel
* __-info__ bot info
* __-simp__ gets a post from [TheSimpPolice](https://www.reddit.com/r/TheSimpPolice/) subreddit
* __-aww__ gets a post from [aww](https://www.reddit.com/r/aww/) subreddit
* __-wholesome__ gets a post from [wholesomememes](https://www.reddit.com/r/wholesomememes/) subreddit
* __-whiteknight__ gets a post from [Whiteknighting](https://www.reddit.com/r/Whiteknighting/) subreddit
* __-meme__ gets a post from one of the following subreddits: [dankmemes](https://www.reddit.com/r/dankmemes/), [BlackPeopleTwitter](https://www.reddit.com/r/BlackPeopleTwitter/), [CrackheadCraigslist](https://www.reddit.com/r/CrackheadCraigslist/)
* __-owner__ posts the owner of the server
* __-ping__ shows the response time of the bot
* __-eightball__ gives an answer to a question
* __-myinfo__ shows your information
* __-level__ shows your level
* __-xp__ shows your xp
* __-simpcount__ shows your simpcount

### List of Admin Commands
* __-simpy__ increases a specified users simpcount
* __-desimp__ decreases a specified users simpcount
