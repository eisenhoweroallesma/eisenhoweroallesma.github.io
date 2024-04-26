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

Let's imagine that I was developing a fantasy-theme video game. This game allows players to wield many different types of magical weapons such as swords, staffs, and bows. Each weapon is given or not, unique abilities and attributes. But you want to make sure that there's only one inventory system that manages all the weapons in the game to avoid inconsistencies and ensure efficient resource management. That is where design patterns come in.

Now, to achieve this, I would have to create a class called manageInventory as a Singleton. A singleton class, in Java, ensures that only one instance of itself exists.This class allows the program to manage the inventory of weapons in the game. By implementing the Singleton, this ensures that there's only one instance of the inventory manager throughout the game.When a player acquires a new weapon, it will be added to the same inventory. This ensures that the player can engage with a single inventory instance, avoiding complications with duplicate inventories. This was just an example of how using a design pattern can be developed.

## My own experience

Currently, I'm working on a project with classmates called "Manoa Club Connects" that uses design patterns. Our program focuses on club listings and user accounts, in which we implement the Singleton classes. The club listing handles the storage and retrieval of club listings. By using the singleton class for the club listing, it makes sure that it prevents duplicate listing and makes it easy to access and update club information from different parts of the website. The user accounts manages users to different clubs as it keeps tracks of their status and other information. The singleton class being used for this purpose is to enhance efficiency in handling membership-related operations scuh as adding or removing users from the club membership's roster.
