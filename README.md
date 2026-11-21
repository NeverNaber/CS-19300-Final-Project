# Java Chess

A two-player chess game built in Java, designed to let two people play together on the same computer through a graphical interface.

## The Problem

I would like to cure boredom by creating a game I can play with friends. I would like to make a 2 player chess game playable in a java window.

## How It Works

The project is being developed in Java using Swing and AWT.

Current elements:

- A swing implimentation of the chess board and pieces
- Text box to type in your move
- Play continues back and forth until a win or draw condition


## Tech Stack

- **Programming Language:** Java
- **IDE:** Visual Studio Code
- **GUI Library:** Java Swing
- **Graphics Library:** Java AWT
- **Version Control:** Git and GitHub

## Setup Instructions

### Requirements

- Java Development Kit (JDK) 11 or newer.
- Visual Studio Code or another Java IDE.

### Downloading the Repository

1. Open the [GitHub repository](https://github.com/NeverNaber/CS-19300-Final-Project).
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the downloaded ZIP file.
5. Open the extracted `CS-19300-Final-Project` folder in Visual Studio Code.

### Running the Application

1. Open the terminal in Visual Studio Code.
2. Create an output folder:

   ```bash
   mkdir out
   ```

3. Compile the Java files:

   ```bash
   javac -d out src/Main.java src/DrawingPanel.java
   ```

4. Run the application:

   ```bash
   java -cp out Main
   ```

When the application loads, you will see the starting board, pieces, and the text box to type your move into.

## Example

### Current Functionality

At startup, the project will show the set up chess board and pieces. To start the first move, type the square you wish to move from in the text box and press enter.


**Example of intended future input:**

```text
e2 (user presses enter) e4 (user presses enter) 
```

**Intended output:**

```text
White moves pawn from e2 to e4. Play switches to black's turn.
```

### Screenshot

NA

## Roadmap / Milestone Plan

The following checklist tracks the six original project milestones.

- [x] Get the board and pieces to show up visually.
- [ ] Get the logic for pieces moving and where they can go.
- [ ] Disallow pieces moving past an edge, onto a same-colored piece, etc.
- [ ] Implement captures and removing pieces.
- [ ] Implement final conditions like checkmate or stalemate.
- [ ] Implement miscellaneous conditions and rules like castling or not being able to move the king into check.

## MVP / Eisenhower Prioritization

### Do — MVP

- Board
- Captures
- Piece movement logic

### Schedule — Future Versions

- Misc conditions
- Additional chess rules
- All types of wins and draws

### Delegate — Use a Library

- Visual of board
- Visual of pieces
- Saving and loading unfinished games

### Delete — Cut It

- Proper notation
- Online usage
- Single-player against AI

## Demo

NA
