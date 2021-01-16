# Getting-started-with-game-development-using-windows-forms

### Introduction
Playing video games is always fun, but what about making one? In this tutorial, we will use windows forms to build a game and go through the steps of making a small puzzle game called Mastermind. Mastermind is a puzzle game that tests the memory and the ability of the player to determine the exact output between all the possibilities.

### Prerequisites
Before we begin it would help the you as the reader to have the following:

A basic understanding of C# programming language.
Visual studio installed on your system.

If you don’t have Visual Studio installed on your computer, you can check this article on how to set up the C# environment in Visual Studio [here](https://www.geeksforgeeks.org/setting-environment-c-sharp/), and if you are new to windows forms you can check this tutorial that would help you understand The basics of it [here](https://www.section.io/engineering-education/getting-started-with-windows-forms-using-c-sharp/).


### How to play/win the game
The system of Mastermind will randomly produce 4 colors from 6 colors stored in the system (allowing duplicate colors), and those 4 colors will remain invisable to the player untill he win or lose the game. The player will have to guess the 4 colors produced by the system, you will have 10 chances to guess the colors before losing the game, and each try will give you a hint, if the player choses one of the colors included in one of the digits produced by the system but not in the right place it will glow red, but if the color is included in one of the digits & at the right place it will glow black. The player must have all the colors in right place in order to win.

### Building the form & the controls of the game
We will use the tool box to select the controls that we need in this game. First of all, we will add 10 labels for each chance, and for each label we will add 4 buttons for the colors one button for the try check and another 4 buttons for the hints, total 9 buttons for each try (label). Finaly 1 button for the start (GO) 4 buttons for the hidden colors produced by the system and 1 one button for the win or lose statement.

This is how the form should look like after including all the controls, and remember that you can always change the fonts & the colors to what ever that suits your taste!

![Mastermind_form](https://github.com/mohamedgh16/Getting-started-with-game-development-using-windows-forms/blob/main/Mastermind_form.png).

this is the table of the Texts & names of all the controls used in this form.
Text | Name
---- | ----
 1 | Label1
 2 | Label2
 3 | Label3
...
10 | Label10
empty | Col1
empty | Col2
empty | Col3
...
empty | Col40
Check | ch1
Check | ch2
Check | ch3
...
Check | ch10
empty | Show1
empty | Show2
empty | Show3
...
empty | Show40
GO    |   GO
empty | cool1
empty | cool2
empty | cool3
empty | cool4
empty | VIC

### Let’s start coding












