

# UE4-Chess
A game of chess created using the Unreal Engine 4.

![chess1](https://user-images.githubusercontent.com/49829764/113481110-01bc7580-9498-11eb-8f87-29c519f21775.jpg)


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

![chess2](https://user-images.githubusercontent.com/49829764/113481121-0bde7400-9498-11eb-82e8-da4cdfb19b44.jpg)
![chess3](https://user-images.githubusercontent.com/49829764/113481124-0e40ce00-9498-11eb-8c1a-0c6a80cb7d25.jpg)
![chess4](https://user-images.githubusercontent.com/49829764/113481126-0f71fb00-9498-11eb-9ecf-ac75da7f8934.jpg)
