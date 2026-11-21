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

- Java Development Kit.
- Git.
- Visual Studio Code or another java runner.

### Cloning the Repository

1. Open a terminal.

2. Clone the repository:

   ```bash
   git clone https://github.com/NeverNaber/CS-19300-Final-Project.git
   ```

3. Navigate into the project folder:

   ```bash
   cd CS-19300-Final-Project
   ```

### Running the Application

You will need a computer capable of opening a java swing window.

1. Create an output folder:

   ```bash
   mkdir out
   ```

2. Compile the application:

   ```bash
   javac -d out src/Main.java src/DrawingPanel.java
   ```

3. Run the application:

   ```bash
   java -cp out Main
   ```

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
