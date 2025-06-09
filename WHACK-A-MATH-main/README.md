## Overview

WhackAMath is an educational math game aimed at improving the mental math capabilities of grade school children. Built as a course project for Computer Science 2212, the game was developed by a team of 5.  
**My Contributions**:  
- Main game loop  
- Level progression  
- Lives and score system  
- Game visuals  

## Features

- **Level-Based Gameplay**: Progress through increasingly difficult math questions.
- **Leaderboard**: Tracks and displays top scores.
- **Debug Mode**: Start the game at any level.
- **Instructor Mode**: View encrypted player stats.
- **Visual Timer and Score System**: Enhances engagement and challenge.

## Requirements

### Software

- IntelliJ IDEA (Windows)
- Java JDK 11+
- JavaFX SDK (from [gluonhq.com](https://gluonhq.com/products/javafx/))

## How to Build from Source

1. Download JavaFX from [https://gluonhq.com/products/javafx/](https://gluonhq.com/products/javafx/)
2. Open the project in IntelliJ IDEA (Windows)
3. Go to `File > Project Structure > Libraries`
4. Click `+` → `Java`
5. Navigate to the downloaded JavaFX folder, select the `lib` directory, and import it
6. Confirm the prompt to add to project
7. Click `Apply` and `OK`  
    *(Repeat steps 4–7 if necessary)*
8. Go to `Run > Edit Configurations`
9. Click `+` → `Application`
10. Set any title and select `SignInMain` as the main class
11. In VM options, add the following (replace `<add your path here>` with your actual path):
``` --module-path "<add your path here>" --add-modules javafx.controls.javafx.fxml ``` 
12. Click `Apply` and `OK`
13. Build and run the project from this configuration
## How to Run from Executable

1. Open the ZIP file containing the project.
2. Run `whackAmole.exe`.
3. Sign in and follow on-screen instructions.

## Software Modes

### Debug Mode

- **Password**: `debug`  
- Start from any level.

### Instructor Mode

- **Password**: `instructor`  
- View encrypted game stats and administer levels.

## Gameplay Instructions

1. **Sign In**
- Pick a username.
- Click “Help” for instructions.
- Access leaderboard, Instructor Mode, or Debug Mode as needed.

2. **Select “Play Game”**

3. **During Gameplay**
- Click the mole with the correct answer.
- Timer: top-left
- Lives: top-right
- Remaining questions: bottom

4. **Progression**
- Complete each level to move on.
- Select next level at result screen.

5. **Game Over**
- Game ends when lives run out.
- View leaderboard or return to main menu.
- Option to reset and start over.

