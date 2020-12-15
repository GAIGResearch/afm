---
layout: papers
title: Abstract Forward Models for Modern Games
description: Stratega
background: /assets/img/Stratega.png
permalink: /stratega/
---



Stratega, a general strategy games framework, has been designed to foster research on computational intelligence for strategy games. In contrast to other strategy game frameworks, Stratega allows to create a wide variety of turn-based and real-time strategy games using a common API for agent development. While the current version supports the development of simple real-time and turn-based strategy games, actively development continues today to incorporate all kind of complexities that are usually found in this type of games: economy, resource management, technology trees, inventories, production, diplomacy, etc.  

The ability to provide a wide range of games is achieved by utilising YAML-files to configure tiles, units, actions, and levels. Therefore, the user can design and run a variety of games to test developed agents without specifically adjusting it to the game being generated. The framework has been built with a focus of statistical forward planning (SFP) agents, and it counts on a simple API to for programming players. For this purpose, agents can access and modify game-states and use the forward model to simulate the outcome of their actions. While SFP agents have shown great flexibility in general game-playing, their performance is limited in case of complex state and action-spaces. 

We hope that the development of this framework and its respective agents helps to better understand the complex decision-making process in strategy games. Stratega can be downloaded at [https://github.com/GAIGResearch/Stratega](https://github.com/GAIGResearch/Stratega), and a full design document of the framework can be read [here](https://arxiv.org/abs/2009.05643).