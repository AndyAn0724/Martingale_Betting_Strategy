# Martingale_Betting_Strategy
Investigate/Visualize the famous martingale betting strategy (or double strategy)

## Overview
In this project, I am trying to explore the famous matingale betting strategy (or, double strategy) using Monte Carlo simulation in a Roulette game. *Learn more about roulette: https://en.wikipedia.org/wiki/Roulette*

## Martingale betting strategy
*From Wikipedia: https://en.wikipedia.org/wiki/Martingale_(betting_system)*
> A martingale is any of a class of betting strategies that originated from and were popular in 18th century France. The simplest of these strategies was designed for a game in which the gambler wins the stake if a coin comes up heads and loses it if the coin comes up tails. The strategy had the gambler double the bet after every loss, so that the first win would recover all previous losses plus win a profit equal to the original stake.

In short, let assume my strategy to play Roulette is like this: We start with some money. My first bet amount is $1. If I win the bet, I take my winnings and game over. Elseif I lose the bet, I **double** my next bet to twice of my previous bet. 

We will investigate this strategy with/without a bankroll limit.  
