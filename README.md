# Plain HTML-CSS-JS Exercice: [Memory Game]

## Setup 

Find the tech case on Github: https://github.com/kuddl/tech_case_memory_game

### Setup on your own machine

```
- Download the project to your machine
- Open ZIP file and open HTML file in browser
- If you want to be safe, connect/fork it to a repository with your GitHub account
```

> Just make sure you don't lose any work!

### Notes

- Look at the code and get familiar with it before doing anything.
- Read all the instructions before starting so you get an idea of the order in which you will build the page.
- Please stop/record the time while working on the assignment. It should be less than 3h. If you cannot finish within this timeframe, just stop anyway, we still have enough code to talk about. (just be honest to yourself and to us and keep the times "real" ;) ).
- Bring your solutions to the tech interview session. If we do it remote: You can share your screen in our meeting (MS Teams), or you can use your Github fork of the project).
- When you finish the assignment, we will set up (probably already have) a tech interview (approx. 1h - 2h), where we discuss the solutions and topics around the challenges. There is no perfect score for the assignment. We will use it mainly as a basis for discussion.
- It should be a little fun to work with code, so do not worry, and have some fun.

## The Story

```
You neighbor wants to launch a new online game: Memory (brand new idea! never seen before)

A junior developer in your team already got onto it, and create a rough prototype.
But since the neighbor wants to see progress, we will have the game as a prototype ready for presentation.

A few days before the meeting with the client, the junior developer shows you the code since he has some problems and needs your help.
So you step in and you will help your colleague.

The game should be familiar (even though it never existed before ;) ) 
The game is playable but has some "flaws". You will fix them.
Keep reading for more information. 
```

## Your tasks

### 0. As a little warm up
- Go to google fonts, and find the "Merriweather" font. Use it in the project for all text.

### 1. Make the user names persistent
As you might have experienced, in the first screen, you will see a form to fill in the names of the players. As soon as you start the game, the names will be visible at the top. But if you reload the page, you start at the first screen.

The acceptance criteria : 
- make the names persistent (choose any technique), so that when you reload the page, the names are still valid and shown at the top, and the board is ready to play.
- it is OK that the board will "restart" with a reload. At least we do not have to "log in" again
- be prepared to present your solution in the tech interview

### 2. Create a "real world card flip animation"
When you click on the card, the "image is shown"; but in a boring way
To impress your neighbor with the skills of our frontend team, we want to create a sexy "card flip animation". 

The acceptance criteria : 
- make a sexy card flip animation (like[ this one](https://www.w3schools.com/howto/howto_css_flip_card.asp))
- it should work for "click" and for the "hide" of the cards
- make sure that the "hide all cards" action is also animated
- Nice to have: the animation should be CSS only (the click handling can be still Javascript)
- Notice: you are allowed to search the internet for solutions and implement them here. But make sure you understand, how it works and can explain it in the interview.


### 2. Refactoring the code
As you implemented the first 2 tasks, you probably changed already some code and improved the code quality.
The code of our junior dev is not ideal; it works, but is not "pretty" nor "stable".
You will refactor the code and in our tech interview, a Merkle Dev takes the role of the junior dev, and you will "explain" and "teach" him, what you have changed and why.
Take a few minutes (approx. 30 minutes) and do some refactoring to the code.
The acceptance criteria : 
- Important: DO NOT re-write the whole script. Use the current code and improve it step by step 
- Look at only 2 aspects of the code to refactor. Use the 2 "biggest pain points" in your understanding (e.g.: refactor some parts into functions; better naming for variables; splitting the code in files)
- make sure you have a "copy" of the before and after state available in the interview to follow the steps of your refactoring (bad example: senior dev to junior dev:  "... this is the new code, it should look like this. Now please follow my example!")


### N.Food for thought / discussion

You are now done with the coding part of this test. This section is not about code and does **not require you to write any code**. Read the bullet points, think about the questions, and maybe write some short notes about them. We will discuss these topics in our interview.

- The repository consists of only 3-4 files. What is necessary in your opinion to do or add to this "folder", so that you would call it a "project", that a team can work on in the future (e.g. add Readme.md (for the game not the challenge); add .gitignore; move files into folders ....)
- The names of the players are now "persistent" (thanks to your work). But the rest of the game is not. What would your proposed solution be, to make it persistent for reloads. (just collect some ideas)
- 
 
## Good luck and have fun!
