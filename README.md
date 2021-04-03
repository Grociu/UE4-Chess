# UE4-Chess
A game of chess created using the Unreal Engine 4.

# Unreal Engine Version 4.26.1

# Features
- Populates the board with chess pieces.
- Assings the two players a color of pieces at random.
- Starts the game and sets the White player to be active.
- Players can make moves by selecting pieces with the mouse, then selecting a target square then pessing Space Bar to make the move.
- Player camera can be rotated using WSAD.
- Upon making a move, the camera automatically switches to the other players' view.

# Implemented rules
- Standard chess piece movement rules including castling, en passant and pawn promotions.
- Highlights the legal moves for a selected piece, considering current and future boardstate (a move will not result in a check for the moving player).
- Various game end scenarios handles: checkmate, stalemate, draw by threefold repetition, draw by the 50 move rule, draw by insufficient mating matereial.
