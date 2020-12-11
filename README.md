# Checkers
## Summary
Browser-based two-player checkers game developed for "CS3249 User Interface Development" Assignments, using an implementation of checkers rules by Ted Benson <eob@csail.mit.edu>. Navigate to http://diptivm.github.io/checkers/), and click and drag the checkers to play. A yellow arrow indicates the direction of play in the current turn.
## Rules
(Source: Assignment prompt)
* Each player starts with their pieces lined up on the two rows closest to their own side.
* Players play from opposite ends of the board, and take turns moving pieces diagonally forward from one square to another.
* A turn consists of moving one piece diagonally-forward to an adjacent unoccupied square.
* If one player's piece, the opponent's piece, and an empty square are lined up, then the first player can "jump" the other player's piece. In this case, the first player jumps over the other player's piece onto the empty square and takes the other player's piece off the board. Multiple sequential jumps by one piece are allowed on a single turn.
* If a player's piece moves into the last row on the opposite side, it becomes a king piece, and can now move forward or backward.
* The game ends when a player loses all of their pieces, or is put in a position where they can’t move.
## Implementation
1. Black-and-white checker board is displayed using vector graphics, while each checker is represented by an HTML object with an image file. 
2. Javascript is used to handle click-and-drag events on the board.
3. Uses an implementation of the rules of American Checkers by Ted Benson <eob@csail.mit.edu>



