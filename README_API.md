# The PYnals 
## Flag capture with characters

## Description
The Pynals is a game developed in Python with the library [PytactX by Jusdeliens](https://jusdeliens.com/).
> 2 teams are fighting agaisnt each other to stay in the flag zone without any ennemy in with them.
## 🎲 Rules
### Components of the arena

![Arena schema](map_avec_zone.jpg)
_Map size: 30x30_
There is many elements in the map:
- 🔴: target area
- 🔵: spawn area
- 🟡: spawn area
- 🟩: jungle

### Players 
There is 3 different profiles.

|Statistics|Light|Medium|Heavy|
|-----|-----|-----|-----|
|Life points|30|60|100|
|Couldown between 2 moves|100|250|500|
|Couldown between 2 fires|200|400|800|
|Hit fire|15|25|30|

### How to win
To win, you and your team must have 200 points.

### How to play
You and your team spawn in one of the two areas. Yoou can choose the profiles as you want (3 heavies, 2 lights and 1 medium, one of each...).
You have two ways to have points:
- Kill an enemy robot and you receive 5 points
- Stay 20 seconds in the target area and you have 100 points
- If you are killed, you respawn in you area after 5 seconds.
- The jungle is a specific area because you are slower than on the paths.

### Rules
- Only one agent per computer
- No network attack (DDOS)
- You can't use AI to write your code
- You can only use the pytactx's API but without certains functions like shockwave


## 🎮 Use cases
### Player
- choose his name
- move in x or y in 1 move
- turn in four directions (N, S, W, E)
- reload

## ✅ pre-requisties
- Python 3.12 or higher
- An arena in Pytactx
## ⚙️ Installation
Installation of necesary packages automatically occur when an agent is created
## 🧑‍💻 Author
Pytactx by Julien Arné

Designed by Mathiys Tola

Inspirated by Swevvenn

Developped by :
- Maxaug61
- Malagagne
- Swevvenn

## ⚖️ License
