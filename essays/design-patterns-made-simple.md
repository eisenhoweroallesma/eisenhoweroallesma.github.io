---
layout: essay
type: essay
title: "Design Patterns Made Simple"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - Reflection
  - Javascript
  - Design Patterns
---

<div class="text-center p-4">
  <img width="200px" src="../img/eslint-img.png" >
</div>

## Developing a video game

Let's imagine that I was developing a fantasy-theme video game. This game allows players to wield many different types of magical weapons such as swords, staffs, and bows. 
Each weapon is given or not, unique abilities and attributes. But you want to make sure that there's only one inventory system that manages all the weapons in the game to avoid inconsistencies and ensure efficient resource management.
That is where design patterns come in.

Now, to achieve this, I would have to create a class called manageInventory as a Singleton. Short defintion of what a singleton class is a class in Java that ensures only one instance of itself exists.
This class allows my program to manage my inventory of weapons in the game. By implementing the Singleton, this ensures that there's only one instance of the inventory throughout the game.
When a player aquires a new weapon, it will all go in the same inventory and the player can engage with the same inventory instance without having complications with duplicate iventories.

## My own experience






