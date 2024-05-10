# prisoners-dilemma
This program emulates different strategies in a long term game of prisonners dilemma

Rules
=====
Two players play n consecutive rounds. In each round they can either betray the other player or cooperate with them. If both players cooperate with each other they both get 3 points. If player A betrays player B, player A gets awarded 5 points and player B zero points and vice versa. If both players betray each other they get only 1 point each. This program runs 200 consecutive rounds of this game and prints the results.

Building
========
As of now there is only build script for linux.
Note that hte build script uses `g++`
To build just do:
```bash
git clone https://github.com/saladwithgrass/prisoners-dilemma
cd prisoners-dilemma
./build.sh
```
