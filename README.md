
Hockey Trader
Introduction
Hockey Trader is a Java application designed to simulate player trades between teams in a hockey league. This application is developed to meet the requirements of the newest media mogul TEspn. It allows users to manage multiple teams within a league, make trades between teams, pick up players from waivers, and find players based on specific criteria. The application also logs all transactions for reference.

Features
League Management: Keep track of multiple teams in the league.
Roster Management: Each team has a roster of players with details such as name, position, salary, and jersey number.
Trade Simulation: Users can simulate trades between teams while ensuring salary cap and roster constraints.
Waiver System: Teams can claim players off waivers, following the same rules as trading.
Player Search: Search for players based on name or position across all teams and the waiver wire.
Logging: All transactions are logged in a file for reference.
Usage
Main Menu:

Users are presented with a main menu displaying various options.
Options include:
Display Teams
Make a Trade
Pick up a Player
Find Player
Exit
Display Teams:

Users can view a list of all teams in the league along with relevant information such as roster size and cap space.
Selecting a team displays its roster.
Choosing a player from the roster displays detailed player information and provides the option to waive the player.
Make a Trade:

Users can initiate a trade between two teams.
The trade process involves selecting trading teams, selecting players to trade, confirming the trade, and checking for trade validity based on salary cap and roster constraints.
Pick up a Player:

Allows a team to claim a player off waivers.
Users select a team and choose a player from the waiver wire.
Claiming a player follows the same rules as trading.
Find Player:

Users can search for players based on name or position.
Results display players matching the search criteria and denote whether they are on a team or the waiver wire.
Logging:

All transactions are logged in a file named Log.txt.
Each transaction generates a line in the log file, including details such as timestamp, teams involved, and transaction outcome.
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/Hockey-Trader.git
Compile the Java source files:
bash
Copy code
javac com/techelevator/*.java
Run the application:
Copy code
java com.techelevator.Application
Dependencies
Java Development Kit (JDK)
Git
Development
The application is developed in Java.
Unit tests are provided to ensure the correctness of the code.
Follows object-oriented principles for modularity and testability.
Contributing
Fork the repository.
Make your changes.
Test your changes thoroughly.
Create a pull request describing your changes.


