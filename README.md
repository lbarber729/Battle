# Battle
A project that creates a web app that allows two players to play a game of Battle

The aim of this project is to -
- Set up a web project with Testing frameworks
- Set up basic  project structure with Sinatra, RSpec and Capybara ready to go

### How to use 
- Clone this repo to your machine
- Run Bundle
- Run Rackup
- Visit localhost:[port number]

![Alt Text](https://media.giphy.com/media/VJwEmAHaC5fTn7AJrc/giphy.gif)
### User Stories
```
As two Players,
So we can play a personalised game of Battle,
We want to Start a fight by entering our Names and seeing them
```

Object | Behaviours
-|-
Players  |  
Game  | input names

---
```
As Player 1,
So I can see how close I am to winning
I want to see Player 2's Hit Points
```

Object | Behaviours
-|-
Players  | 
Hitpoints  | Can see hitpoints

---
```
As Player 1,
So I can win a game of Battle,
I want to attack Player 2, and I want to get a confirmation
```

Object | Behaviours
-|-
Players  | Can attack another player

---
```
As Player 1,
So I can start to win a game of Battle,
I want my attack to reduce Player 2's HP by 10
```

Object | Behaviours
-|-
Players  | Can attack another player
Hitpoints  | Reduce hitpoints

---
```
As two Players,
So we can continue our game of Battle,
We want to switch turns
```

---
```
As Player 1,
So I can see how close I am to losing,
I want to see my own hit points
```

---
```
As Player 1,
So I can lose a game of Battle,
I want Player 2 to attack me, and I want to get a confirmation
```

---
```
As Player 1,
So I can start to lose a game of Battle,
I want Player 2's attack to reduce my HP by 10
```

---
```
As a Player,
So I can Lose a game of Battle,
I want to see a 'Lose' message if I reach 0HP first
```
### Status
- I managed to get up to and complete the user story that asks to reduce Player 2's HP by 10
- All test are passing 
