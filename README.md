# "Battle Duel"

## User Stories

1. As a user, I can create a hero to duel an enemy
2. As a user, I can choose my hero's name, strength, and health
3. As a user, I can take turns with the computer opponent until one of us wins

## Code Requirements

1. A command line application that takes input from the user
2. An entity wins when the other entity has 0 or less than 0 health
3. Must have some sort of random element: the game should play differently each time, even with the same stats for the hero
4. Must have an abstract class Combatant with an abstract method attack(Combatant c) that child classes will implement
5. Must have an interface to add some special ability that child classes can use in combat

## Bonus

1. Hero can battle a group of enemies