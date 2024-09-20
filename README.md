# README - Music Tracker Service

<marquee> **Welcome to the Music Tracker Service!** </marquee>

## Project Description

This project is a service that allows users to log the songs they are listening to and view the most played songs over specified time intervals. The system allows users to:

1. View the songs they have listened to most recently, with defined intervals.
2. View their most listened-to songs of all time.

## Features

- **Song Logging**: Users can log the songs they are listening to, including information such as the song name, band/artist, and composer. This data is stored in a database.
- **Most Played Songs Report**: Users can view the most played songs over various periods, such as "last week", "last month", or "all time."
- **Login System**: The system includes a login page where users can access their data and view their music listening habits.

## Endpoints

- **Log a Song**:  
  Endpoint that receives information such as:
  - Song name
  - Band/Artist
  - Composer
  - (Other relevant details as needed)

  Example request (in JSON format):
  ```json
  {
    "song": "Bohemian Rhapsody",
    "band": "Queen",
    "composer": "Freddie Mercury"
  }
  ```
- **Music discovery**:  
  View Most Played Songs:

  - **Endpoint that returns the most played songs, with options to filter by time intervals.**
  - **Endpoint that returns the most played songs for a user, with options to filter by time intervals.**
  
## Creation Criteria

    - Database:
    The project uses a database to store information about the songs the user listens to. This can be either a relational (SQL) or non-relational (NoSQL) database, depending on preference.

    - Language:
    Use the language you are most comfortable with. Although Kolek uses Typescript, the language used in this project can vary as long as it meets the requirements. [Specify which language was used, e.g., Node.js, Python, etc.]

    - Front-End Interface:
    The system includes a page where users can view their most played songs, with filters for defined time intervals (last week, last month, etc.).

## Bonus Points

    - Dockerization:
    The project includes Docker configuration files to facilitate execution in different environments.

    - Unit and Integration Testing:
    Tests were implemented to ensure system stability. [Specify the testing tool used, such as Jest, Mocha, PyTest, etc.]

    - End-to-End (e2e) Testing:
    e2e tests were added to simulate user interaction with the system, ensuring the interface works correctly.
