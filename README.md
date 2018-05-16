1 2 3
4 5 6
7 8 9

You need to figure out the key code to a number pad. You are a given a list of directions (U=UP, D=Down, L=Left, R=Right) each refering to a button on the keypad. Each line of instructions corresponds to one button, starting at the previous button (for the first line starting at the middle button '5'); the button you reach at the end of each line is the button you actually press. If a move doesn't lead to a butotn, ignore it.

Suppose your instructions are:

ULL
RRDDD
LURDL
UUUUD
You start at "5" and move up (to "2"), left (to "1"), and left (you can't, and stay on "1"), so the first button is 1.
Starting from the previous button ("1"), you move right twice (to "3") and then down three times (stopping at "9" after two moves and ignoring the third), ending up with 9.
Continuing from "9", you move left, up, right, down, and left, ending with 8.
Finally, you move up four times (stopping at "2"), then down once, ending with 5.
So, in this example, the code is 1985.

