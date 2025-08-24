CS 230 Portfolio Reflection
1. Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a client that developed the game Draw It or Lose It, which was originally created for Android. They wanted to expand their application so it could run on multiple operating platforms, both desktop and mobile. Their requirements included support for multiple teams and players, ensuring that game and team names were unique, and maintaining only one active instance of the game service at a time. The software also needed to be scalable, secure, and accessible through a web-based distributed environment.

2. What did you do particularly well in developing this documentation?

I think I did well in breaking down the client’s requirements and mapping them to design patterns like Singleton and Iterator. I also explained the advantages and trade-offs of different platforms clearly, which would help the client make informed decisions. My recommendations section was especially strong because it tied together storage, memory, and distributed systems in a way that addressed scalability and security.

3. What about the process of working through a design document did you find helpful when developing the code?

Writing out the design document first helped me think through how different parts of the system connect. It forced me to consider things like data storage, security, and performance before jumping into code. Having the UML diagrams and platform evaluation also made coding easier because I already had a structure to follow rather than making decisions on the fly.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the evaluation section, since that part required comparing multiple platforms in detail. I think I could improve it by going deeper into cost analysis and providing more specific examples of how deployment would look on each platform. Adding visuals or charts might also make it easier for a client to understand quickly.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by focusing on scalability, uniqueness of game/team names, and support for multiple platforms. These were translated into design choices like using the Singleton pattern for game service management, role-based access control for security, and recommending Linux for the server backend. Considering user needs is critical because software that doesn’t solve the user’s problems won’t be useful, no matter how well it’s built.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the design by starting with requirements, then mapping them to patterns and technologies that fit best. I used UML diagrams to visualize relationships between classes and relied on platform comparisons to justify technical choices. In the future, I would continue using this requirements-first approach, but I’d also add more prototyping and early testing to catch issues sooner. I’d also consider agile methods like incremental design and feedback loops to refine the software as it’s built.
