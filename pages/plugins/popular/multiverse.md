---
description: Learn how to use Multiverse-Core.
name: plugins/popular/multiverse
---

# Multiverse

## OVERVIEW

Multiverse provides the easiest to use world management solution for your Minecraft server

## CREATING A WORLD

The create command allows you to add new worlds to your server thus allowing many different worlds of many different types.

To create a Multiverse world, use `/mv create (worldName) (worldType)`. You can replace world name with your preferred world name, and replace world type with **normal**, **nether**, **flat_world** and others which you can view [here](https://github.com/Multiverse/Multiverse-Core/wiki/Command-Reference#create-command). This requires the permission **multiverse.core.create**.

## CREATING A VOID WORLD

You can't make a void world with Multiverse out of the box, for that you need the plugin `VoidGenerator`, which is in the plugins panel.
To use it, simply use the command `/mv create (worldName) (worldType) -g VoidGenerator`.
For more info about VoidGenerator, click [here](https://www.spigotmc.org/resources/voidgen.25391/).

## TRAVELING TO A WORLD

The teleport command allows you to teleport yourself or others to a specified world.

To teleport to a Multiverse world, use `/mv tp [player] (worldName)`. The player parameter is optional, and you can replace world name with the world you want to travel to. This requires the permission **multiverse.teleport.self.NAME** OR **multiverse.teleport.other.NAME**.
You can also use Minehut's built in world teleportation command, which is `/world (worldName)`.
