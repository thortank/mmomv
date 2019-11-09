# (MMO)RPG Maker MV

## Summary
This is a project I started in 2016 and on which I worked for only few weeks. In 2019 I stumbled upon an old version of the code which I have tested & refactored (a little bit). I also decided to restart working on it on my free time - which I almost have not - and open source it with the hopes that some other cool people upgrade it!

## History
I have used RPG Maker since its 2000 version. Discovered it when I was a kid and used it to make many (very bad) games. It clearly impacted a lot on my creativity and my development desires. Later on, as a French-speaking person, I discovered a (now dead) project named FROG Creator which was a dedicated at creating MMORPG in a RPG Maker-like environment. 

With the release of RPG MAKER MV which allows usage of JavaScript and its HTML5 export, I decided to give it a try and discovered quickly that yes, RPG Maker MV could easily be used to create an MMORPG creator interface.

## How to use ? 

Video : [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TcAmU2bdKvE/0.jpg)](https://www.youtube.com/watch?v=TcAmU2bdKvE)

### Plugins requirement 

**Disclaimer :** *All the files are already contained in the project.*

- Orange Custom Events : http://download.hudell.com/OrangeCustomEvents.js
- Orange Custom Event Creator : http://download.hudell.com/OrangeCustomEventCreator.js

### Launch steps
1. `git clone` the repo
2. Install [NodeJS](https://nodejs.org/en/) and `npm i` in the `server` folder
3. Install [RethinkDB](https://rethinkdb.com/docs/install/) and `rethinkdb` in the `server` folder
4. `node mmo.js` in the `server` folder
5. Start the RPG Maker MV project.

Congratulations! Your game is now an MMORPG. 

### Current functionalities
- Synchronised player movements
- Synchronised skins
- Persistance of position & skin
- Persistance of player stats
- Persistance of inventory & equipments
- Persistance of local switches
- Persistance of global switches
- Global and local map system
- In-game chat

### Improvements to do :
- Improve in-game chat UX with keybindings and so on
- Add RESTFUL API for outside game interactions
- Create inter-players interactivity (trades, pvp, ...)
- (Continuous) Refactore entire codebase
- (MUCH LATER) Server-side anti-cheat