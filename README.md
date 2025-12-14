# Tic-Tac-Toe
Tic Tac Toe Game (Python Console) Classic Tic Tac Toe game built in Python using boolean state arrays (xstate, zstate) for efficient position tracking. Players alternate placing X/O on a 3x3 grid by entering numbers 0-8. Features custom printboard() with nested ternary logic for clean board display.


Tic Tac Toe Game (Python Console)
Classic 2-player Tic Tac Toe built in Python using boolean state arrays (xstate, zstate) for efficient position tracking. Players enter numbers 0-8 to place X/O on a 3x3 grid.

🎮 Features
Console-based gameplay (X vs O)

Efficient board state with separate X/O boolean lists

Position validation (empty spots only)

Clean board printing with nested ternary logic

🚀 How to Run
Clone repo: git clone https://github.com/Venkat-Sai-Charan-Saragani/tic-tac-toe.git

Navigate: cd tic-tac-toe

Run: python main.py

text
Example board:
0 | 1 | 2
--|---|--- 
3 | 4 | 5
--|---|--- 
6 | 7 | 8

X's chance
enter the number: 

🧠 TECH HIGHLIGHTS
python
# Nested ternary for clean board display
zero = 'X' if xstate[0] else 'O' if zstate[0] else '0'
Debugged from set/dict errors to string outputs

Pure Python - no dependencies

Efficient state checking (X first, then O, then empty)

📝 GAME RULES

X starts first

Enter position 0-8 for empty spots

3 in a row/column/diagonal wins

Numbers show available positions


##SCREENSHORT OF THE GAME
<img width="710" height="412" alt="image" src="https://github.com/user-attachments/assets/f6f5c52f-3e45-44e9-88c3-da9eb271b222" />

