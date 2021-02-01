---
layout: base
title: Abstract Forward Models for Modern Games
description: Competition
background: /assets/img/Stratega.png
permalink: /competition/
---

**IEEE Conference on Games 2021 Competition**

Following up on the idea of the General Video Game AI (GVGAI) competition, we propose the General Strategy Game AI competition as a new and interesting challenge. While the complexity of GVGAI games has been limited, strategy games feature search trees of exceptional breadth and depth. In comparison, to existing strategy game competitions, our competition will focus on the development of a single agent which is capable of playing multiple strategy games with varying characteristics. Those include but are not limited to, turn-based vs. real-time strategy games, completely observable vs. partial information games, and a varying set of units, levels, abilities and game-modes.

To this end, we have developed Stratega, a general strategy games framework (https://github.com/GAIGResearch/Stratega). Stratega allows the creation of a wide variety of turn-based and real-time strategy games using a common API for agent development. Game components are defined using a YAML configuration file which makes the creation of new games and their balancing very simple. The framework has been built with stochastic forward planning agents in mind and supports full access to a game’s forward model, which has been optimized in terms of simulation speed.

During CoG 2021, we will hold the “General Strategy Game-Playing”-track, which invites all participants in creating their own agent for playing multiple strategy games. At the start of the competition we will provide a set of sample games for training. To keep the evaluation fair and overfitting to a minimum, we will use a hidden set of games to evaluate the agents. For a single game, Agents will be ranked based on their relative win-rate among all submitted agents and the baseline agents provided by the competition framework. The final score will be calculated using the Formula-1 scoring scheme, which favors agents that perform well in multiple games.

We plan to introduce additional tracks in future iterations of our competition.

More information on the CoG 2021 edition coming soon, please keep an eye on this place!
