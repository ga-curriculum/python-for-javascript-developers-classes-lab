# Objective

<aside>
🏆 This assignment is a deliverable! Turn it in to Clippy on March 28, 2023.

</aside>

Build a Tic-Tac-Toe game incorporating the web technologies and techniques you’ve worked with thus far:

- HTML
- CSS
- JavaScript
- DOM Manipulation

# Minimum Requirements

- Display an empty tic-tac-toe board when the page is initially displayed.
- A player can click on the nine cells to make a move.
- Every click will alternate between marking an `X` and `O`.
- Once occupied with an `X` or `O`, the cell cannot be played again.
- Provide a `Reset Game` button that will clear the contents of the board.
- Display whose turn it is (“X” or “O”).
- Provide win logic and display a winning message.
- Provide logic for a cat’s game (tie), also displaying a message.

# Getting Started / Hints

- Fork & clone the starter [**code repository**](https://github.com/SEI-Remote/ttt-weekend) by doing the following:
    1. Go into your labs directory (located at **`~/code/sei/labs`**)
    2. Fork the `ttt-weekend` repository to your GitHub account and clone it to your machine.
- **Follow the approach as described in the [Guide to Building a Browser Game](https://www.notion.so/Guide-to-Building-a-Browser-Game-82086de5cc9747b7b47308996455022a?pvs=21)**.
- Using `id` and/or `class` attributes will help you target elements for styling and wiring up your click event listeners.  These have already been added for you in this lab!
- Programs, including games, are frequently focused on manipulating data and displaying that data to a user. Decide on the data structures held in variables you will use to maintain the game’s *state* (data / status).
- Note that the values you use to represent your game state don’t necessarily have to match what you want to display to the user. For example, just because you want to display X and O doesn’t mean that you have to use those letters in your data structure. For example, in the pseudocode we’ve chosen to use 1 to represent player X and -1 to represent player O, for example. Then, in your `updateBoard` function, you would have the logic to translate data to what you want to display.  (The reasoning behind this will become apparent when you reach that part of the lab.)
- Wire up your click event listener(s). Using a single listener with event bubbling is recommended but not required.
- Lots of little functions!

# Pseudocode

Pseudocode is a detailed description of what an application must do, written in natural language instead of a particular programming language.

Well-written pseudocode should be easily translated into actual code.

The best way to get started is to start with the big picture of what the app needs to do:

```
1) Define the required variables used to track the state of the game

2) Store cached element references

3) Upon loading, the game state should be initialized, and a function should be 
   called to render this game state

4) The state of the game should be rendered to the user

5) Define the required constants

6) Handle a player clicking a square with a `handleClick` function

7) Create Reset functionality
```

Since most web apps are event-driven by nature. Coding an event-driven program generally requires that we set up the application when it loads (steps 1 - 5) and wait for the user to interact with the app (steps 6 & 7).

Now we can start adding as many detailed steps as desired.

Typically, pseudocode does not have to be as detailed as the following - it is highly detailed here to help you as much as possible:

## Step 1 - Define the required variables used to track the state of the game

<aside>
💡 None of these variables will need to hold a value when they are defined.
</aside>

a) Use a variable named `board` to represent the state of the squares on the board.

b) Use a variable named `turn` to track whose turn it is.

c) Use a variable named `winner` to represent if anyone has won yet.

d) Use a variable named `tie` to represent if the game has ended in a tie. 







