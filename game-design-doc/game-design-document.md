# Game Design Document - Space Shooter

- [Game Design Document - Space Shooter](#game-design-document---space-shooter)
- [Overview](#overview)
- [Story](#story)
- [Gameplay](#gameplay)
- [Mechanics](#mechanics)
  - [Spaceship movement](#spaceship-movement)
  - [Fire bullet (no powerup)](#fire-bullet-no-powerup)
  - [Spawn powerup](#spawn-powerup)
  - [Collect powerup](#collect-powerup)
  - [Fire bullet - Powerup1](#fire-bullet---powerup1)
  - [Fire bullet - Powerup2](#fire-bullet---powerup2)
  - [Enemy spawn](#enemy-spawn)
  - [Enemy fire bullet](#enemy-fire-bullet)
  - [Enemy defeated](#enemy-defeated)
  - [Points](#points)
  - [Game over](#game-over)
- [Game Entities Statistics](#game-entities-statistics)
  - [Player spaceship](#player-spaceship)
  - [Bullets damage](#bullets-damage)
  - [Enemy1](#enemy1)

# Overview

Show how skilled you are and survive the waves of incoming spaceships! The more you survive, more points you get!

# Story

The war is coming and everyone is trying to become a *space shooter*. 

Why? The Military Defense needs the best pilots to win the war so they created a *virtual mission* to test your skills! 
The best shooter will be awarded with infinite pizza and beer for the rest of his life.

Play *Space Shooter* and take the highest score to show the Military Defence who is the best!

# Gameplay

The gameplay is an infinite side-scrolling shooter where enemies randomly appear and start firing at you.

Your objective is to survive and destroy as much enemies as you can to get points.

# Mechanics

## Spaceship movement

## Fire bullet (no powerup)

## Spawn powerup

## Collect powerup

## Fire bullet - Powerup1

## Fire bullet - Powerup2

## Enemy spawn

## Enemy fire bullet

## Enemy defeated

## Points

- You start with 0 points
- Every 5 seconds you get 10 points for surviving
- Every defeated enemy gives 25 points
- If you don't take any damage for 5 seconds, you get a 2x multiplier for every obtained score
- If you don't take any damage for 10 seconds, you get a 4x multiplier for every obtained score
- If you don't take any damage for 30 seconds, you get a 5x multiplier for every obtained score
  
## Game over

# Game Entities Statistics

## Player spaceship

|   Stat    |        Value         |
| --------- | -------------------- |
| HP        | 100                  |
| Fire rate | 4 bullets per second |

## Bullets damage

|  Stat   | Value |
| ------- | ----- |
| Normal  | 25    |
| Powerup | 50    |

- **Powerup** When the player takes a powerup, bullets become 25% bigger and they do more damage

## Enemy1

|  Stat  | Value |
| ------ | ----- |
| HP     | 100   |
