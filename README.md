Dino Arena
Project Description
Dino Arena is a turn-based dinosaur battle game inspired by mobile arena games like Jurassic World: The Game. The player creates a dinosaur, chooses a species, and fights an enemy dinosaur using action points each turn. Points can be spent on attacking, blocking, or reserving extra power for the next turn. I chose this idea because I like games where the player has to make simple strategic choices instead of only clicking one attack button.

The project changed near the end so it could be finished on time. My original idea included multiple dinosaur images, more enemy types, special abilities, and a longer tournament mode. I cut those features and focused on a smaller playable proof of concept with one battle screen, clear buttons, health tracking, and the main attack/block/reserve system.

Inspiration
The main inspiration is the battle system from Jurassic World: The Game, where players choose how many action points to use for attack, defense, or saving for later. My version is not a copy of that game, but it uses the same general idea of turn-based choices and point management.

Typical User Flow
The user types a dinosaur name.
The user chooses a dinosaur species.
The user clicks Create Dino to create the player dinosaur model object.
The user chooses Attack, Block, or Reserve each turn.
The game updates health, action points, and battle messages.
When a dinosaur reaches 0 health, the game announces the winner.
The user can click Restart to begin again.
Course Concepts Used
JavaFX GUI front-end with labels, text fields, choice boxes, buttons, layout panes, and event handlers.
Model classes to represent the game data separately from the GUI.
Constructors, getters, setters, toString, and equals.
Conditional logic for battle outcomes and game-over checks.
Random number generation for enemy actions.
Object interaction between HelloApplication, Dinosaur, and BattleGame.

## Demo

Place the animated image of your project demo here!

## UML Diagram

<img width="900" height="680" alt="image" src="https://github.com/user-attachments/assets/008c58d3-b53a-4052-a3fa-9b05b20bc665" />


## Wireframe

<img width="760" height="760" alt="image" src="https://github.com/user-attachments/assets/42acd7ec-d0c9-49e4-ace3-d02b5a9a5a93" />
