MIST 4610 Group Project: NCAA College Football Database

Team Members:
Audrey Staples - https://github.com/audreystaples/mist4610groupproject 

Angela Ren

Sammy Effron

Tanner Sutherland

Tyler Schildkraut


Problem Description

We wanted to construct a data model that organizes key information used to navigate the NCAA college football landscape. The ultimate goal for our model is to represent the various relationships that exist among Coaches, Teams, Players, Rosters, Games, etc. in a way that mirrors how real NCAA programs operate. Although our data is hypothetical, it represents pertinent information that would meet managerial requirements within the NCAA ecosystem. From surveying game statistics to determining player status on a roster, our database provides insights that would prove highly useful to NCAA stakeholders. Ultimately, we aimed to create a database that would effectively aid managerial decision making within essential business units such as logistics management, decision-making, and reporting within an ever evolving industry.


Data Model Explanation

Our database is based on the NCAA with hypothetical data included for ease of data insertion. For instance, instead of the University of Georgia the entity is the Athens Bulldogs.

Our data model represents the key components of NCAA college football and how they interact with one another. Each team can have multiple coaches and players, with the rosters table serving as the link between teams and players to show which athletes play for which team in a given season, along with their position, jersey number, and start or end dates. The games table connects home and away teams to the stadium where each game takes place, while the tickets and seats tables manage game attendance and seat assignments. Coaches are tied to their respective teams, and players are connected to both game statistics and injuries to track performance and health over time. Altogether, this structure allows for efficient organization of data related to team management, player performance, scheduling, and ticketing, accurately reflecting the operations and relationships that exist within NCAA football programs.

<img width="638" height="700" alt="Screenshot 2025-10-22 at 10 09 00 PM" src="https://github.com/user-attachments/assets/a28ac496-6830-4f2a-96cf-64cd652cd0d6" />

Data Dictionary

<img width="902" height="295" alt="Screenshot 2025-10-22 at 10 13 45 PM" src="https://github.com/user-attachments/assets/be3afe6d-085d-4152-a56d-11718f81a2e7" />

<img width="879" height="244" alt="Screenshot 2025-10-22 at 10 14 05 PM" src="https://github.com/user-attachments/assets/0e5cb177-19b1-4c5b-8178-3bfad7b5c5d5" />

<img width="862" height="360" alt="Screenshot 2025-10-22 at 10 14 22 PM" src="https://github.com/user-attachments/assets/f7c89cbb-760e-4270-b73d-127cf0b00cbf" />

<img width="933" height="406" alt="Screenshot 2025-10-22 at 10 14 48 PM" src="https://github.com/user-attachments/assets/68f128f5-99c6-4afe-8e35-c9d26210eec1" />

<img width="948" height="342" alt="Screenshot 2025-10-22 at 10 15 07 PM" src="https://github.com/user-attachments/assets/590900da-c8b4-4675-ad55-2ef51ff074e9" />












