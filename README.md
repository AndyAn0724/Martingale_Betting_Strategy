# Martingale_Betting_Strategy
Investigate/Visualize the famous martingale betting strategy (or double strategy)

## Overview
In this project, I am trying to explore the famous matingale betting strategy (or, double strategy) using Monte Carlo simulation in a Roulette game. *Learn more about roulette: https://en.wikipedia.org/wiki/Roulette*

## Martingale betting strategy
*From Wikipedia: https://en.wikipedia.org/wiki/Martingale_(betting_system)*
> A martingale is any of a class of betting strategies that originated from and were popular in 18th century France. The simplest of these strategies was designed for a game in which the gambler wins the stake if a coin comes up heads and loses it if the coin comes up tails. The strategy had the gambler double the bet after every loss, so that the first win would recover all previous losses plus win a profit equal to the original stake.

In short, let assume my strategy to play Roulette is like this: We start with some money. My first bet amount is $1. If I win the bet, I take my winnings and game over. Elseif I lose the bet, I **double** my next bet to twice of my previous bet. 

## Steps
1. Build a simple martingale gambling simulator
2. Experiment 1: Explore the strategy using Monte Carlo simulation. No bankroll limit, but we set a goal of winning $80 before we stop playing the game. Questions to investigate: 
   1. What is the estimated probability of winning $80 within 1000 sequential bets?
   2. What is the estimated expected value of our winnings after 1000 sequential bets?
3. Experiment 2: Explore a more realistic game with a $256 bankroll. Meaning, if he or she runs out of money, bzzt, that's it. An important corner case to be aware of is the situation where the next bet should be $N, but you only have $M (where M<N). Make sure you only bet $M. Questions to investigate: 
   1. What is the estimated probability of winning $80 within 1000 sequential bets?
   2. What is the estimated expected value of our winnings after 1000 sequential bets?
   3. Does the standard deviation reach a maximum value then stabilize or converge as the number of sequential bets increases?
