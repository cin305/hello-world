# hello-world
#include <iostream>
using namespace std;

C++ array puzzle 
// Create a C++ program using Arrays, that resembles a puzzle that automatically runs. ( Prompt user: Only user input required is to enter how many characters user wants to use on the right side of board, and on the left side of board- means you must allocate the array dynamically). By pressing the Enter key, each move is made. (Only one move at a time). Use an underscore as the blank space '_'. Create .cpp and .h header files. Must be modular program (As many seperate .cpp as required to compile program.)
Start of program compile: 
ZYXW_ABC // Start
ZYX_WABC // Move 1
ZYXAW_BC // Move 2
ZYXAWB_C // Move 3
ZYXA_BWC // Move 4
......so on and so forth until the right characters are all on the left side, and left characters are on the right side, and space is in the middle again.... to look like this:
ABC_ZYXW // End
***Rules: 
You may only move one person at a time forward to an open square.




•    You may only pass someone (1 person) from the opposite group onto an open square in any given move.



- Can't pass character in same group
-Can't trade places 
-Can't move back 
- If a character doesn't follow rule, all characters start over //

