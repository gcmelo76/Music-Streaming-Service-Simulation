# Music Streaming Service Simulation

A web-based music streaming service simulation built with **Python**, **Flask**, and **PostgreSQL**, designed to handle authentication, music management, and playlist functionality. The project uses **Postman** for API testing and provides a user-friendly interface for managing music-related data.

---

## Features

- **User Authentication**: Secure token-based authentication using JSON Web Tokens (JWT).
- **Music Management**:
  - Add, update, delete, and retrieve music records.
  - Search music by title, artist, or genre.
- **Playlist Management**:
  - Create and manage personalized playlists.
  - Add or remove music from playlists.
- **Admin Dashboard**: Real-time updates for administrative tasks using REST APIs.

---

## Technologies Used

- **Programming Language**: Python
- **Framework**: Flask
- **Database**: PostgreSQL
- **API Testing**: Postman
- **Authentication**: JSON Web Tokens (JWT)

---

## Getting Started

### Prerequisites

- Python 3.7 or higher installed.
- PostgreSQL installed and configured.
- Postman installed for API testing.

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/gcmelo76/Music-Streaming-Service-Simulation.git
   cd Music-Streaming-Service-Simulation

2. **Install Dependencies**
   pip install -r requirements.txt

3. **Set Up the Database**
   Use pgAdmin or the command line to create a PostgreSQL database.
   Run the provided SQL script (schema.sql) to initialize the database schema.

4. **Configure Database Connection**
   Update the config.py file with your PostgreSQL credentials.

5. **Run the Flask Application**
   python app.py


