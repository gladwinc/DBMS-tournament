# Sports Tournament DBMS
This project is a SQL-based database management system (DBMS) designed for managing data related to sports tournaments. It includes tables for storing information about players, coaches, referees, teams, matches, stadiums, and more.

## Proposal with Business Rules
Before beginning the project, a proposal was created that outlined the business rules and requirements for the database. This proposal included but is not limited to the following information:
- Each stadium can host multiples matches, and every match takes place in a single stadium.
- A player can be associated with zero or multiple doctors, and each doctor can oversee multiple players.
- A player can receive zero or more cards, with each card being linked to a single player.
- A player has the potential to score zero or more goals, and each goal is associated with a specific player.

## Entity Relationship Diagram (ERD)
After defining the business rules and requirements, an ERD was created to model the relationships between the different entities in the database. The ERD was fully modelled and normalized to ensure efficient and effective storage of data.

![ERD](/Project01/ERD.png)


## SQL Scripts
The SQL scripts for creating the database tables, inserting sample data, and performing queries are included in this project. The tables created are but not limited to:
- Player: stores information about players including their name, date of birth, player number, nationality, position, address and team
- Goal: stores information about goals scored during a match including the player who scored goal, the time it was scored, and the match
- Card: stores information about cards given to players during a match, including the type of card, the time, the player, the match it was given and the referee who gave it

The SQL scripts also include sample data for each of these tables.

## Conclusion

This project provides a comprehensive DBMS for managing data related to sports tournaments. The database is designed to efficiently store and retrieve information about players, teams, matches, and more, making it an essential tool for tournament organizers and sports enthusiasts alike.
