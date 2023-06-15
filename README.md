# zk-battleships

## Rules:

- 10x10 grid
- Boats:
    - 1 Carrier (5 squares)
    - 1 Battleship (4 squares)
    - 1 Cruiser or Submarine (3 squares)
    - 1 Destroyer (3 squares)
    - 1 Patrol Boat (2 squares)
- Boats cannot be placed diagonally or overlapping
- Take a shot by using coordinates
- Player needs to say that a ship has been sunk

## Board commitment string

commitment strings follow this format 

- Use a string of characters where each character represents the state of a cell on the board.
- Use specific characters to denote different states: "." for empty or unknown cells, "C" for Carrier, "B" for Battleship, "S" for Submarine, "D" for Destroyer, "P" for Patrol Boat, "X" for hit cells, and "#" for sunk cells.
- Arrange the characters in a single continuous string.