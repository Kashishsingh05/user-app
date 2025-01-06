# Rock Paper Scissors Game

A Java-based GUI implementation of the classic Rock Paper Scissors game.

## Project Overview

This project implements a graphical user interface version of Rock Paper Scissors using Java Swing. Players can compete against the computer through an intuitive interface with real-time score tracking and game state updates.

## Rubric Implementation

### 1. Core Feature Implementation
- Complete game logic (rock beats scissors, scissors beats paper, paper beats rock)
- Score tracking system
- Move validation
- Game state management
- Reset/replay functionality
- Visual feedback for game outcomes

**Key Components:**
- Game logic controller
- Score management system
- Move validation system
- Game state tracker

### 2. Error Handling and Robustness
- Exception handling for UI components
- Input validation
- Graceful error recovery
- User feedback for errors
- Crash prevention mechanisms

**Implementation:**
- Try-catch blocks for component initialization
- Input validation for player moves
- Error dialogs for user feedback
- State validation before actions
- Resource cleanup on exit

### 3. Integration of Components
- Layered architecture design
- Modular component structure
- Consistent user interface
- Proper layout management
- Component communication

**Key Features:**
- Separate panels for scores, game buttons, and results
- Consistent styling across components
- Efficient component communication
- Responsive layout design

### 4. Event Handling and Processing
- Button click events
- Keyboard shortcuts
- Mouse hover effects
- Game state updates
- Animation handling

**Implementation Details:**
- ActionListener for buttons
- KeyBindings for keyboard controls
- MouseListener for hover effects
- SwingWorker for background processing
- Timer for animations

## Technical Requirements

- Java Development Kit (JDK) 11 or higher
- Java Swing library
- Window manager supporting GUI applications

## Controls
- Mouse clicks on game buttons
- Keyboard shortcuts:
  - 'R' - Rock
  - 'P' - Paper
  - 'S' - Scissors
  - 'Ctrl + N' - New Game

## Project Structure
```
src/
├── main/
│   └── java/
│       ├── RockPaperScissors.java
│       ├── GamePanel.java
│       ├── ScorePanel.java
│       └── ControlPanel.java
└── resources/
    └── images/
        ├── rock.png
        ├── paper.png
        └── scissors.png
```

## Testing
- Unit tests for game logic
- Integration tests for UI components
- Error handling validation
- Event processing verification

## Known Issues
- None currently reported

## Future Enhancements
- Multiplayer support
- Sound effects
- Animation improvements
- Statistics tracking
- Theme customization
