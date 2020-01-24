---
layout: project
type: project
image: images/randomdung.jpg
title: Random Dungeon
permalink: projects/randomdung
# All dates must be YYYY-MM-DD format!
date: 2018-05-18
labels:
  - Game
  - RPG
  - Procedurally Generated
summary: A simple rpg dungeon crawler game
---

I tried writing a simple procedurally generated rpg game in Java after a year in the Computer Science program. It was entirely text-based and suffered from horrible balancing issues. After a while, the player character outscaled the monsters and you would basically be unkillable.

Here is a little snipbit of the console log:

-You encountered Slime
[Slime][HP: 5]
- Fight(f) Run(r) Item(i) Shop(p) Status(s)
f
-- You hit slime for 2 [HP: 3]
- Slime hit you for 1 [HP: 19]
- You hit slime for 2 [HP: 1]
-- Slime hit you for 1 [HP: 18]
-- You hit slime for 3 [HP: 0]
-- Slime hit you for 1 [HP: 17]
-- You defeated Slime! Gained 5 EXP [EXP: 5/10]
- Continue(c) Rest(r)

While the game was not very good, it was a great learning experience. It forced me to consider various things like character stats, some way to implement a random damage calculator that scaled depending on things like levels and items, and some system to procedurally generate enemies based on the player character.
