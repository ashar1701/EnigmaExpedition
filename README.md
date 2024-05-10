# ENIGMA EXPEDITION

## Description
ENIGMA EXPEDITION is an interactive educational escape room game designed to challenge players with puzzles and trivia while enhancing their knowledge across various topics. Players navigate through different levels, each presenting unique questions that require critical thinking to solve. Success in the game is measured by the accumulation of points and the ability to advance to subsequent rooms, with a leaderboard to rank high scores.

## Prerequisites
To build and run the software, you will need the following libraries:
- OpenCSV (Version 5.6 or higher)
- Apache Commons Lang (Version 3.14.0)

## Building the Software
### Obtaining the Libraries
1. Download the required libraries:
   - OpenCSV can be obtained from its [Source Forge repository page](https://sourceforge.net/projects/opencsv/files/opencsv/5.9/opencsv-5.9.jar/download).
   - Apache Commons Lang can be downloaded from its [Maven repository page](https://mvnrepository.com/artifact/org.apache.commons/commons-lang3/3.14.0).

2. Place the downloaded .jar files in the build path of the project. To do this in Eclipse, go to the Project tab then click on properties, edit the Java build path and add the external jar files.

3. If you do not have Eclipse IDE then place the downloaded `.jar` files into a `lib` directory within your project structure.

### Compiling from Source
1. Ensure you have Java Development Kit (JDK 19 or higher) installed on your machine.
2. Set up your environment variables to include the `JAVA_HOME` and update the `PATH` variable to include the path to the JDK binaries.
3. Navigate to your project directory from the command line.
4. Compile the source code using the Java compiler:

javac -cp "lib/*" group36/src/Start.java

Replace `group36/src/Start.java` with the path to your main Java file.


## Running the Software
1. Once the software is compiled, run the program using the following command:

java -cp ".:lib/*" Start

Ensure to replace `Start` with the fully qualified name of your main class.

2. If you have Eclipse workspace, simply run Start.java to start the game.

## User Guide
### Starting the Game
- Run the compiled software as outlined in the previous section.
- From the main menu, choose `PLAY` to start a new game or `LOAD GAME` to continue a previous session.

### Gameplay
- Navigate through the rooms by solving puzzles and selecting the correct answers based on the question.
- Your remaining lives and current score are displayed on the screen.

### Leaderboard
- Access the leaderboard from the main menu to view high scores and the fastest completion times.

### Settings
- Adjust game settings such as sound and display options through the `Settings` or `Pause` menu.

### Save
- Open the pause menu and click on Save to save your current game session

### Exit
- Click on the pause button in the pause menu to quit your current game session without saving.

### How To Play
- Click on the How to Play button in the main menu to access the rules of the game.

### Instructor Dashboard
- Instructor dashboard can be accessed by the instructor only by using the password given in the next section. The dashboard provides game statistics of each player.

### Debug Mode
- The game moderators can access this mode to jump to any room. The password is provided in the section below.

## Passwords
To access the instructor dashboard or the game moderator mode, enter the password below:
Password: `HELLO123`


## Teacher Mode
To access instructor dashboard, where the instructor can see player statistics:
1. On the main menu, click the 4th button from the right (button with a person pointing to a board)
2. Log in with the password given below`
- Password: `HELLO123`

To access the How to Play mode:
1. Start the game
2. Click on the How To Play button and read the instructions.



