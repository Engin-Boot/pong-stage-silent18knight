# Sign up or login for the game

## Feature

It performs the player to create profile for the game

## Acceptance Criteria

### Scenario: Initially when someone enters the game then signing up is mandatory

  Given someone opens the game

  When someone try to start play

  Then they have to enter their name and create their profile for the first time.

### Scenario: Initially when someone enters the game after signup

Given someone opens the game again

When he try to play the game

Then he just have to enter his login credentials for the game to start
from the last checkpoint.
