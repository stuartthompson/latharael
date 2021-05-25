# Latharael

A fantasy universe where the goal is to learn, grow, adapt, and survive. This
is a simulated world in which automated scripts attempt to thrive.

## Motivation

This software was written to grant the author a journey. I wanted to build a 
game where players described their actions as a set of scripted responses as
opposed to playing their characters directly. The objective for the players is
to understand how to craft a better automated operator to survive and to grow
in the simulated world more quickly and efficiently before. The objective for
the author is to learn about all of the technologies and tools necessary to
host and run this design.

## Basic Premises

A view of the simulated world is provided to each of the players via a game
state. Their actions and choices are made as calls to the game API, which can
also reveal further information about the world and current situation in
response to actions such as scanning or searching.

## Simulation and Timing

The world simulation is built around the concept of a tick. Each tick is like
the ticking of the second-hand on a conventional clock, and represents the
smallest unit of passing time that the game and its players understand. Within
each tick, all players are given a limited period of time in which to perform
actions before the next world state update is run.

### Logs and Player Journals

The world will track all game and player state changes within master logs.
Each player will additionally have access to a journal, which logs in detail
the information they received, the actions they took, and a breakdown of the
responses they received to those actions along with reasonable explanations of
why those responses occurred. A heavy emphasis is placed upon timing, with the
duration of particular actions, the time taken for a player to respond, and
their relations to the overall world tick cycle being explained and
documented in sufficiently reasonable detail as to allow a player character
author to understand how they may adapt and change their player script to
effect improved or, at the least, different actions in future iterations.

## License

Please see the included 
[LICENSE](https://github.com/stuartthompson/latharael/blob/omega/LICENSE.md).

## Changelog

This project documents significant changes in the included 
[CHANGELOG](https://github.com/stuartthompson/latharael/blob/omega/CHANGELOG.md).

## Issues

Bugs, issues, change requests, and other feedback are tracked in
[ISSUES](https://github.com/stuartthompson/latharael/issues)

## Roadmap

A rough project roadmap *(not necessarily in alignment with the project
milestones or issues list)* is maintained in the included
[ROADMAP](https://github.com/stuartthompson/latharael/blob/omega/ROADMAP.md).