---
layout: post
title: Pathfinding and rendering improvements
date: 2019-10-7 19:40:00
---

We now can move in our room! 

I've added pathfinding A* algorithm to move our habbo around the room, with dinamic change of path (you don't need to complete the path to start a new one).

![pathfinding added to habbunity](https://imgur.com/SinUYyv.gif)

Also changed some things in rendering and now it's a little better (still not perfect).

For now I'm importing the player's body in layers (as you can see in the image). I think that's a good choice for when we start to add clothes and other effects.

![layer import of player's body](https://i.imgur.com/lBpCQaF.png)

The next steps are:
- Start to dynamically update our grid including information about the room (e.g. where you can and can't walk);
- Add some animation to the main character;
- Add some walls?

See ya! =)
