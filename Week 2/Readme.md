WEEK 2 project Overview ---
This project is completely a fun filled learning exercise for practising python. 


Problem statement ---
Create famous 'Frog leap' puzzle game. Try completing the game before starting to get an idea about its working.

Rules ---
The left set of frogs can only move right, the right set of frogs can only move left.
Frogs can move forward one space, or move two spaces by jumping over another frog from opposite side.
The puzzle is solved when the two sets of frogs have switched positions.


Steps to solve the problem:

Step1 ---
Display green and brown frogs on the left and right sides initially.

Initial Display ---
[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', 'G', '-', 'B', 'B', 'B']

Here 'G' represents Green frogs on the left side and 'B' represents brown frogs on the right side. The '-' defines the position of empty leaf. (You can change display according to your imagination or convinience)

Step2 ---
Accept positions of the frog that you want to move.

Example: If we enter position 2 then the game will look like this:-

[ 0 ,  1 ,  2 ,  3 ,  4 ,  5 ,  6 ]
['G', 'G', '-', 'G', 'B', 'B', 'B']

Step3 ---
Define Invalid moves and add conditional 'if' statements accordingly

Rules ---
Entered position should be between 0 to 6. Or a character 'q' to quit the game.
Entered position cannot be the position of empty leaf.
If the selected frog position cannot perform the contraints given in rule 2 then the move is invalid.

Step4 ---
Make the appropriate move by changing the game display
