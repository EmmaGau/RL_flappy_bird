# Flappy Bird Text Assignment

## Intro

In this assignment, we explore Reinforcement Learning methods to play Text Flappy Bird.
Our task involved implementing and comparing two agents (Monte Carlo and Sarsa($\lambda$))that can solve one of the two versions
of the TextFlappyBird-v0 environment.

## Environnemt

The two environments differ only in the yielded observations. The TextFlappyBird-screen-v0
returns the array that represents the current state of the game screen encoded as integers while
the TextFlappyBird-v0 returns the horizontal and vertical distance of the player to the closest
upcoming pipe gap. We will be working with TextFlappyBird-v0.

- States: The states are represented by the X-axis and Y-axis distance from the closest
  upcoming pipe.

- Reward: As long as it stays alive the reward is equal to 1.

- Action: The Flappy bird agent can achieve two actions FLAP : when the bird ascend by flapping its wings.
  IDLE: when the bird remains stationnary without flapping

## Repo

You can play with the implemented agents using the 'flappy.ipynb' and see the resulting policies and state values functions
