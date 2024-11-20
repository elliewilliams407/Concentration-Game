# Concentration Game:

## Overview
Concentration is a single-player card matching game where players must find and match pairs of cards. This project implements the game using Java and the Big Bang library, providing an interactive graphical interface.

### Game Rules
1. The game starts with a grid of face-down cards. 
2. Each turn, the player flips two cards to find a match. 
3. If the cards match, they are removed from the board. 
4. The game ends when all pairs are matched. 



## How to Play
### Start the Game:

Run the game to start at the difficulty selection screen. \
Choose between: \
    (1) Easy Mode: Match cards by value only. \
    (2) Hard Mode: Match cards by value and suit color (red/black). 

### Flip Cards:

Click on a card to flip it over. \
Flip two cards per turn to check for a match. 

### Match Cards:

If the cards match, they are removed from the board. \
If they do not match, they are flipped back face-down on the next turn.

### Timer and Reshuffle:

A timer counts down from 15 seconds. \
If the timer runs out, the cards reshuffle automatically.

### Winning the Game:

Match all pairs of cards to win. \
A congratulatory message is displayed when you win. 

### Controls:

  R Key: Resets the game. \
  H Key: Returns to the mode selection screen.

# How to Download and Play the Game
## 1. Clone the Repository or Download the ZIP 
- Option 1: Clone via Git: \
    1. Open a terminal and run the following command:
     ```bash
    git clone https://github.com/yourusername/Concentration-Game.git
    ```
    2. Navigate to the downloaded folder:
    ```bash
    cd Concentration-Game
- Option 2: Download as ZIP:
1. Go to the repository's main page on GitHub.
2. Click the green Code button and select Download ZIP.
3. Extract the ZIP file to a folder on your computer.

## 2. Open the Project in Eclipse
1. Open Eclipse IDE.
2. Click File > Import... > General > Existing Projects into Workspace.
3. Select Next, then browse to the folder where you downloaded the project.
4. Ensure the project is selected and click Finish.

## 3. Set Up Dependencies
If your game uses the Big Bang library or any other external libraries, follow these steps: \
1. Download the required .jar files (e.g., BigBang.jar) and place them in a lib/ folder in the project directory.
2. Add the libraries to your project’s build path:
- Right-click on the project in the Project Explorer.
- Select Build Path > Add External Archives....
- Browse to the location of the .jar files and add them.

## 4. Compile and Run the Game
1. Ensure the project is selected in the Project Explorer.
2. Click Run > Run As > Java Application.
3. Select the Concentration class (or the main class, depending on your project structure).
4. The game will launch and display the graphical interface.

## 5. System Requirements
- Java Development Kit (JDK): Version 8 or higher.
- Eclipse IDE: Any version supporting Java development.
- Ensure your system has sufficient memory and screen resolution to run the game smoothly.

# Optional: Running the JAR File
If you included a runnable .jar file in your repository, you can add instructions for running it directly:

```bash
#### Running the JAR File
1. Download the `.jar` file from the [Releases](https://github.com/yourusername/Concentration-Game/releases) section.
2. Open a terminal and navigate to the folder containing the `.jar` file.
3. Run the following command:
   ```bash
   java -jar ConcentrationGame.jar
```
The game will start in a new window.
``` bash
---

### Example for `README.md`
```markdown
# Concentration Game

## Overview
Concentration is a single-player card-matching game implemented in Java. The objective is to match pairs of cards from a shuffled deck while choosing between two difficulty levels: Easy and Hard.

## How to Download and Play the Game

### 1. Clone the Repository or Download the ZIP
- Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Concentration-Game.git
```

## 2. Open the Project in Eclipse
1. Open Eclipse IDE.
2. Import the project via File > Import... > Existing Projects into Workspace.
3. Browse to the project folder and click Finish.

## 3. Set Up Dependencies
1. Ensure all required libraries (e.g., BigBang.jar) are added to the lib/ folder in the project.
2. Right-click the project, select Build Path, and add the .jar files to the project.

## 4. Compile and Run
1. Select the project in Eclipse.
2. Click Run > Run As > Java Application.
3. Select the Concentration class and enjoy the game.

## Running the JAR File
If you prefer, download the precompiled .jar file from the Releases section and run it using:

```bash
Copy code
java -jar ConcentrationGame.jar
```
