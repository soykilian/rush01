# RUSH 01 for the 42piscine
The goal is to solve the Skyscraper game with a program in C. 
The puzzle of the game follows the sudoku structure but with some restrictions. It looks like this:

<img src="https://www.brainbashers.com/gifs_tower/skyhelp0.png" alt="Alt text" title="Optional title">

The generated program finds the solution given the numbers on the arrows as an argument. 

## Instalation & compilation
Install it with 
```sh
git clone
```
Compile the files
```sh
gcc *.c
```
## Usage
The example above should be passed to the program this way:  

<img width="736" alt="Screen Shot 2022-10-01 at 8 05 03 PM" src="https://user-images.githubusercontent.com/79358300/193422447-7c1a2dee-661d-44ac-b18f-d9a3bf788d64.png">

The solution of this puzzle looks like this :

<img width="92" alt="Screen Shot 2022-10-01 at 8 07 27 PM" src="https://user-images.githubusercontent.com/79358300/193422465-9f5d4ea2-2222-4057-9463-c33e8590f476.png">
## Algorithm

It is basically done by using a recursive function depending on a main condition that when is not fulfilled the recursion goes back. In other words, with backtracking
