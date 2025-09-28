# chess-using-python
Chess Game with AI
Aim

The aim of this project is to develop a fully functional chess game with graphical user interface using Python and Pygame, including an AI opponent using the Minimax algorithm with Alpha-Beta pruning. Players can play Human vs Human or Human vs AI.

Features

Playable chess game with graphical interface.

Implements all standard chess rules for pawn, rook, knight, bishop, queen, and king.

Supports capturing, check detection, and game over.

Displays valid moves, captured pieces, and status messages.

Includes AI opponent that evaluates positions and selects optimal moves.

AI uses Minimax with Alpha-Beta pruning for efficient decision making.

Technology Used

Python 3

Pygame for graphics

Requests & rembg to load piece images with transparent background

Algorithm

Move Generation:

Generates all legal moves for each piece based on chess rules.

Checks for captures, board boundaries, and friendly piece collision.

AI Decision Making:

Minimax Algorithm: Recursively evaluates board positions to maximize AI advantage.

Alpha-Beta Pruning: Optimizes search by pruning branches that cannot improve the current score.

Board Evaluation: Considers material, center control, and mobility.

Gameplay Flow:

Players select pieces and move them.

AI automatically plays when enabled.

Game detects check, checkmate, draw, and forfeit conditions.

Time Complexity

Move Generation: O(1)–O(7) per piece depending on type and position.

Minimax Algorithm: O(b^d), where:

b = average legal moves per turn (~20–30)

d = search depth

With Alpha-Beta Pruning: ~O(b^(d/2)) in best case.

Board Evaluation: O(n + m), n = white pieces, m = black pieces.
