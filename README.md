Project Overview
Client: The Gaming Room
Project: Draw It or Lose It - A Web-Based Multiplayer Game

Summary:
The Gaming Room requested the design of a web-based version of their Android game Draw It or Lose It. The game is a team-based multiplayer drawing and guessing game that requires real-time interaction and scalability to support multiple users simultaneously across various platforms, including mobile and desktop devices. Our goal was to create a software architecture that would accommodate their business requirements while ensuring performance, reliability, and cross-platform compatibility.

Project Details
Client and Software Requirements
The Gaming Room is a gaming company looking to expand their popular Android game Draw It or Lose It into a web-based platform that supports cross-platform play. The key software requirements were:

Cross-Platform Compatibility: Ensure the game runs smoothly across different platforms (desktop and mobile) using technologies like HTML5, CSS, and JavaScript.
Real-Time Gameplay: Implement real-time drawing and guessing features to enable players to interact seamlessly.
Unique Naming System: Enforce unique names for games, teams, and players to avoid duplication issues.
Scalability: Allow the game to handle an increasing number of users without impacting performance.
Singleton Pattern: Ensure only one instance of the game is in memory at any given time for performance and resource management.
Security: Incorporate user authentication and data security measures using secure protocols such as OAuth 2.0 and TLS encryption.

What I Did Well in the Documentation
In developing the software design documentation, I was able to clearly define the system architecture and illustrate the relationships between different components using UML diagrams. I took care to break down complex concepts such as class inheritance, memory management, and distributed systems in a way that could be understood by both technical team members and non-technical stakeholders. This ensured the documentation was both thorough and easy to follow.

Helpful Elements of the Design Document
The process of working through a design document forced me to think critically about the relationships between different components of the software and the architecture required to meet the client's needs. By creating UML diagrams and clearly outlining the technical and business requirements, I found it much easier to structure the code effectively, ensuring that the design principles and patterns were maintained throughout the development process.

Areas for Improvement
If I were to revise one part of the document, it would be the Evaluation section. I would have liked to provide a more in-depth comparison between the different operating platforms (Windows, Linux, and Mac) in terms of performance, security, and compatibility. Specifically, I would have expanded on how different server architectures (monolithic vs. microservices) could affect performance in a large-scale game environment. I would also focus more on how these platforms might support or hinder scalability as the game grows.

Addressing User Needs
To ensure the design met the user's needs, I incorporated user feedback about the Android version of the game into the design for the web-based platform. For example, ensuring real-time responsiveness and providing a clean, intuitive interface were priorities. I interpreted the need for smooth performance across all devices as a requirement to use web technologies that are compatible with most platforms while keeping the architecture scalable to avoid performance bottlenecks.

Considering the user’s needs is critical in software design because the success of the product depends on how well it addresses those needs. A user-friendly design that runs smoothly on all platforms ensures user satisfaction, which is essential for the game’s adoption and growth.

Approach to Designing Software
In designing the software for Draw It or Lose It, I utilized object-oriented principles, including encapsulation, inheritance, and design patterns like the Singleton and Iterator patterns. These principles ensured the game’s logic was modular, reusable, and maintainable. Moving forward, I would continue to focus on scalability and security by incorporating cloud-based services and microservices architectures, as these are becoming increasingly important in modern software design.

In future projects, I would also place greater emphasis on incorporating user feedback earlier in the process to better align the design with the actual user experience. Tools such as prototyping and wireframes could be employed to improve communication and refine the design before starting the full development cycle.

This design documentation demonstrates how I approached the challenges of creating scalable, cross-platform software while addressing the business needs of the client, The Gaming Room. It reflects my ability to translate technical requirements into clear design decisions that ensure both performance and user satisfaction.
