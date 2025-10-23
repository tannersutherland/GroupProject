# GroupProject

Problem Description

We wanted to construct a data model that organizes key information used to navigate the NCAA college football landscape. The ultimate goal for our model is to represent the various relationships that exist among Coaches, Teams, Players, Rosters, Games, etc. in a way that mirrors how real NCAA programs operate. Although our data is hypothetical, it represents pertinent information that would meet managerial requirements within the NCAA ecosystem. From surveying game statistics to determining player status on a roster, our database provides insights that would prove highly useful to NCAA stakeholders. Ultimately, we aimed to create a database that would effectively aid managerial decision making within essential business units such as logistics management, decision-making, and reporting within an ever evolving industry.



Data Model Explanation

Our data model represents the key components of NCAA college football and how they interact with one another. Each team can have multiple coaches and players, with the rosters table serving as the link between teams and players to show which athletes play for which team in a given season, along with their position, jersey number, and start or end dates. The games table connects home and away teams to the stadium where each game takes place, while the tickets and seats tables manage game attendance and seat assignments. Coaches are tied to their respective teams, and players are connected to both game statistics and injuries to track performance and health over time. Altogether, this structure allows for efficient organization of data related to team management, player performance, scheduling, and ticketing, accurately reflecting the operations and relationships that exist within NCAA football programs.

<img width="638" height="700" alt="Screenshot 2025-10-22 at 10 09 00 PM" src="https://github.com/user-attachments/assets/a28ac496-6830-4f2a-96cf-64cd652cd0d6" />

