# Streamline

- **Name:** E.J. Yu
- **Date:** April 27, 2019

## Program Description

Streamline is a game where you navigate a piece around a board to get
to a goal. Sometimes there will be obstacles in your path, so you have
to figure out how to get around those in order to reach the goal. It's
simple and fun!

Use the W, A, S, and D keys on your keyboard to move your piece around
the board. Those will help you get around obstacles and get to your goal.
If you hit the edge of the board, there's a cool mechanic: you can snake
around the board and come out on the other side! This will allow you to 
reach areas you'd never be able to reach, had you only been able to move
up to the edge of the game board. So use this to your advantage to get
around because you will stop IF you hit obstacles!

Sometimes people make mistakes though, and that's alright. Using the U key
on your keyboard will undo your last move. So if you find that you've
gotten yourself stuck, you can always undo your last move to get back to a
position where you can make reasonable progression again.

Sometimes people have other things to do though (like download Joker for
Smash Ultimate), and that's alright. This game will let you save your game!
The O key on your keyboard will save your game, so once you're done
doing the important things (or not-so-important things) in life, you can
always load your save data to start your Streamline session again from 
where you last were when you saved. You won't be able to undo moves made
from before you had saved though, so watch out.

If you get frustrated and need to rage quit, you can use the Q key to 
quit the Streamline game, or the current level if you have a bunch
of levels queued.

## How I Tested My Game

    (1) During my method implementations, I would create a set of testers
        in a main() method that I'd temporarily put in the class, and run
        my program. These would help me ensure that specific parts of a 
        method works as intended. After the implementations, I'd use the
        GameManager program to run the Streamline game and see if the
        parts of the game that I've implemented so far would work. And
        this is the main way I'd test everything. 

    (2) Testing implementations after they're written ONLY (rather than
        testing as you go) is dangerous because it's hard to identify what
        the problem may be if you've written everything up already.
        Especially when you have a logic error that's applyed in multiple
        areas of your code, debugging after the method implementations
        can prove to be an extremely tedious process. It's better to
        test as you go since you can take steps to ensure that small parts
        of your code at a time work exactly as you intend them to work!

    (3) Relying solely on visual testing isn't an accurate way of testing
        the game's functionality, because there are things you can't see
        in a game that are really important to its functionality. One of
        the many instances of those things have to include the logic of 
        a game: you can't see the logic behind board rotations or character
        movements, per se. That's why visual testing shouldn't be your
        only method of testing your program.

## VIM / Linux Questions

1. VIM:

    (1) New line above: O
        New line below: o

    (2) 13w

    (3) rY

    (4) R

    (5) :help :sbuffer

    (6) :tabnew

2. Unix / Linux:

    (1) tail -13 ParseJSON.java

    (2) mv Paul.java Alex.java

    (3) touch Rick.java

    (4) cp Gary.java Leo.java

    (5) echo I love computer science!
