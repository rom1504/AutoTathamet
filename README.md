# AutoTathamet
[![NPM version](https://img.shields.io/npm/v/autotathamet.svg)](http://npmjs.com/package/autotathamet)
[![Build Status](https://img.shields.io/circleci/project/MephisTools/AutoTathamet/master.svg)](https://circleci.com/gh/MephisTools/AutoTathamet) 
[![Discord Chat](https://img.shields.io/badge/discord-here-blue.svg)](https://discord.gg/9RqtApv)  

Create Diablo2 bots with a powerful, stable, and high level JavaScript API.

<img src="docs/images/follow_example.gif" width="300" height="300"><img src="docs/images/pickit_example.gif" width="300" height="300">

## Features

* chat
* follow
* pick up items

## Roadmap

* map
* inventory

## Usage

```js
const { createBot } = require('autotathamet')

async function start () {
  const bot = await createBot({
    host: 'battlenetip',
    username: 'myusername',
    password: 'mypassword'
  })
  await bot.selectCharacter('mycharacter')
  await bot.createGame('mygame', '', 'game server', 0)
}

start()

```

## Documentation

* See docs/API.md
