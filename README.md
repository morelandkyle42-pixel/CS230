# CS230
Operating Platforms

The Gaming Room Software Design Reflection

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was our client. They had an Android game called Draw It or Lose It and wanted it redesigned as a web app that would work on different platforms. The software needed to support games, teams, and players, making sure each had unique names and IDs. The design also had to consider things like operating systems, storage, memory, networking, security, and user access on various devices.

What did you do particularly well in developing this documentation?

I clearly explained what the client needed and linked those needs to my design choices. I organized the document to show why using a Linux server, a client-server setup, and a web-based design made sense for Draw It or Lose It. I also described how this design would allow the game to run on different devices without requiring separate versions for each system.

What about the process of working through a design document did you find helpful when developing the code?

Writing the design document helped me figure out the program’s structure before I started coding. It made me consider the main classes (Game, Team, Player, Entity, and GameService) and how they would interact. It also helped me see why using the singleton pattern for the GameService prototype was useful, as it centralized all game data.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could change one part, I would improve the system architecture section. I would give more details about how the browser, server, application logic, and database connect in the full game. A clearer diagram or explanation would help both the client and the development team better understand the system.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I focused on what The Gaming Room wanted the game to do for players to understand their needs. Since users needed to play on different devices, I suggested a web-based design instead of separate apps for each platform. Because the game had to manage teams, players, and sessions, I included server-side management and persistent storage. It’s important to consider user needs so the software solves the client’s problem and is easy to use. If you ignore user needs, the software might work but still not meet the project’s goals.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I started the software design by looking at what the client needed and figuring out the main parts of the system. I used object-oriented design to organize the prototype, using classes, inheritance, encapsulation, and the singleton pattern. In the future, I would do the same: review the requirements first, create a domain model, compare platform options, and make recommendations based on performance, scalability, security, and user needs.
