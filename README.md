# Travel-Plan
1. Functional and non-functional requirements

      Functional requirements:
      The app should allow users to design a travel route within one city.
      The app should allow users to plan short trips ranging from 1-15 days.
      Users should be able to search for points of interest in the database and add them to the map as pins.
      The app should be able to suggest a reasonable route based on the order of the points of interest.
      
      Non-functional requirements:
      The app should have a simple and clean user interface.
      The workflow should be easy to understand and navigate.
      The app should be user-friendly and have a high level of user empathy.
      The app should be innovative and have standout features.

2. Problem statement:
The problem that Travel Planner aims to solve is the difficulty in planning travel routes, especially in unfamiliar locations. The current solution is to rely on travel guides or online resources, which can be time-consuming and not always reliable. This app aims to provide a visual and interactive solution to help users plan their travel routes more efficiently and accurately. This matters because planning a travel route can greatly affect the quality of a trip, and having a reliable and user-friendly tool can enhance the overall travel experience.

3. Proposals:
    High-level design:
    Component diagram:
    Front-end: React
    Back-end: Spring Boot
    Database: MySQL

    Sequence diagram:
    User searches for points of interest in the database
    User selects points of interest and adds them to the map as pins
    App suggests a route based on the order of the pins
    User can adjust the route by rearranging the order of the pins

    Data flow diagram:
    User input (searched points of interest)
    Database search
    Map overlay
    Route suggestion

    Low-level design:
    Class diagram:
    User class
    Point of interest class
    Map class
    Route class
    Database class

    Decision flow diagram:
    User inputs search query
    App searches the database for relevant points of interest
    App displays search results to the user
    User selects points of interest and adds them to the map
    App suggests a route based on the order of the pins
    User can adjust the route by rearranging the order of the pins

    Sequence diagram:
    User searches for points of interest in the database
    App searches the database and returns results
    User selects points of interest and adds them to the map
    App suggests a route based on the order of the pins
    User adjusts the route by rearranging the order of the pins

4. Decision matrix:
      User experience and usability (most important)
      Accuracy and reliability of the suggested route
      App performance and responsiveness
      Security and privacy of user data
      Scalability and maintainability of the app
