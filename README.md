# Rule-Based Game AI Project
This is the final project i made for collage to show my knowledge in data structures and algorithms and how i can use researched algorithms to solve an NP-HARD problem.

It combines three well known techniques for creating a rule-based AI agent in games: **behavior trees**, **utility functions** and **BlackBoard**.

# Information About The Project
The project was made in unity and visual studio 2022. it contains around 9k-10k lines of code written across many classes.

All of the classes are categorized inside the `Assets/` folder, if you want to check out the code yourself (everything else besides what's inside the `Assets/` folder was added by unity).

The layout of the important directories:

```text
Assets/
├── Algorithm/      # Handles AI behavior algorithms, pathfinding, and map representation
├── DataStructures/ # Contains all custom data structures built from scratch
├── EntityLogic/    # Manages interaction logic between the player and enemy entities and how the entities state change every tick
├── SavingSystem/   # Handles saving and loading game states
└── Script/         # Defines specific entity behaviors and runtime execution logic(player,enemy,camera,interactable objects,
                      the game manager, projectiles and more.
```
The main focus of the project was the implementation of a group of agents that can dynamically cooperate with each other while scaling linearly with every agent added(which is the NP-HARD problem to solve).Every algorithm and data structure was made from scrath without using any external tools or built-in algorithms.

The project was built in 2 months on the free version of unity where i started with zero knowledge about unity, meaning i had to both create the project and also learn everything on the way. While it's algorithmically really big and complex, From a real game developer perspective, it's rough and far from being good.

I hope this project can give you the base algorithmic idea for much better implementations that would be more fit for an actual game, and not just a college project.
This project is composed of many different computer science concepts - between different design patterns, OOP concepts, Data-oriented and event-driven techniques, complex algorithms and more.

If you know how to speak Hebrew, i have provided a pdf called `project book` i submitted along with my project, that contains all the needed information to understand how most things work.

Or better than that, you can check out the main source i learned most of the techniques from called <a href="https://www.gameaipro.com/">Game AI pro</a>. IMO, it's an absolute must to read it for pretty much any type of game for which you want to make your own AI from zero without relying on external tools. It's free and covers so many topics in the world of Game AI( but most of the code examples are written in C++, so you might want to be profficent enough in that language to understand) so check it out if you want.

