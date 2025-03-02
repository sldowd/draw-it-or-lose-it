# Draw It or Lose It - Software Design Document

## Project Reflection

### Client Overview
The Gaming Room was looking to expand their Android game application "Draw It or Lose It" to multiple platforms. The game is similar to the 1980s TV show "Win, Lose or Draw," where teams compete to guess what is being drawn. Instead of players drawing images, the application renders images from a stock library as clues. Each game consists of four one-minute rounds, with drawings fully revealed at the 30-second mark. If the active team doesn't guess correctly in time, other teams get a 15-second opportunity to make one guess.

### Documentation Strengths
In developing the software design document, I effectively analyzed the technical requirements across different operating platforms. The document clearly outlined how the singleton pattern could be implemented to ensure only one game instance exists. I also provided a comprehensive evaluation of different operating systems, detailing their strengths and weaknesses for both server-side and client-side components, which gave the client valuable insights for making informed decisions.

### Benefits of the Design Document Process
Working through the design document before coding was instrumental in identifying potential issues early. It helped clarify the architectural structure needed for the application, especially for implementing unique identifiers for games, teams, and players. The domain model section provided a clear blueprint of the class relationships, which streamlined the development process and ensured consistency across the application.

### Areas for Improvement
If I could revise one part of the document, I would enhance the storage and memory management sections. I would include more specific metrics on performance impacts when loading high-definition images across different platforms, and provide more concrete implementation recommendations for caching strategies to optimize the user experience during gameplay.

### Implementing User Needs
I interpreted user needs by focusing on the game's core functionality - rendering images at a steady rate with strict timing requirements. The design accommodated multiple concurrent game instances with different teams and players, ensuring a seamless multiplayer experience. Considering user needs is crucial because ultimately, the success of the software depends on user satisfaction and engagement. Even technically flawless software will fail if it doesn't address what users actually want or need.

### Design Approach and Future Strategies
My approach to designing the software involved starting with a broad understanding of requirements, then breaking them down into specific components and relationships. I used object-oriented principles to create a flexible and maintainable architecture. In the future, I would incorporate more user testing feedback earlier in the design process and use iterative prototyping to validate assumptions about user interaction. I would also consider employing more formal UML modeling tools to better visualize complex relationships between classes and components.
