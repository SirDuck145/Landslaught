# Landslaught
A very simplistic deck-builder rts / lane defense.

## Map Overview
The map will be set, something of a similar style to a MOBA map<br/>
On opposite sides of the map each player has a base<br/>
Units can be spawned at each base, they walk along the lanes<br/>
The map will have multiple "Control points" which add cards to the players deck<br/>

## Card Overview
The player will have a hand of cards<br/>
These cards can be played for mana which is generated<br/>
every set period of time, for now say every two seconds<br/>
Ever card has a manacost, image, text.<br/>
*Example card 1: Warrior, costs 2 mana, spawns a warrior to walk down a lane*<br/>
playing the card onto a lane targets that lane<br/>
*Example card 2: Rain, costs 1 mana, Lowers soldier moral in an area. (Soldiers can rout I guess idk)*

### Roadmap
First design a simple map with one single lane, no points of holding<br/>
The map will simply have two opposing bases.<br/>
Second implement the warrior card, with no mana cost<br/>
Implement Mana cost, get it to work with the warrior.<br/>
