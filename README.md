# Movie Application with Spring Boot, MongoDB, Java, and React

Welcome to the Movie Application repository! This project is designed to demonstrate the integration of Spring Boot, MongoDB, Java, and React to create a comprehensive movie application that allows users to browse, search, and discover information about movies.

## Features

- Browse a collection of movies with details such as title, release year, genre, and more.
- Search for movies based on different criteria like title, genre, release year, etc.
- View detailed information about each movie, including a brief overview and cast.
- User-friendly web interface built with React for seamless interaction.
- Backend powered by Spring Boot, providing RESTful APIs to manage movie data.
- Data storage and retrieval managed through MongoDB, ensuring flexibility and scalability.

## Technologies Used

- Frontend: React
- Backend: Spring Boot (Java)
- Database: MongoDB

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js and npm (for React)
- Java Development Kit (JDK)
- MongoDB

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/movie-application.git
   cd movie-application
   ```

2. **Frontend Setup:**

   ```bash
   cd frontend
   npm install
   npm start
   ```

   This will start the React development server and you can access the application at `http://localhost:3000`.

3. **Backend Setup:**

   Open the project in your preferred Java IDE.

   - Configure MongoDB connection settings in `src/main/resources/application.properties`.

   - Build and run the Spring Boot application.

4. **Access the Application:**

   Open your web browser and navigate to `http://localhost:3000` to access the Movie Application.

## API Endpoints

The backend exposes the following RESTful API endpoints:

- `GET /api/movies`: Get a list of all movies.
- `GET /api/movies/{id}`: Get details of a specific movie by ID.
- `GET /api/movies/search?query={searchQuery}`: Search for movies based on the provided query.
- `POST /api/movies`: Add a new movie.
- `PUT /api/movies/{id}`: Update details of a movie.
- `DELETE /api/movies/{id}`: Delete a movie.

## Contributing

We welcome contributions from the community! To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request describing your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project was inspired by the love for movies and the desire to showcase the integration of different technologies.
- Special thanks to the Spring Boot, MongoDB, Java, and React communities for providing powerful tools and resources.

Feel free to reach out to us with any questions or suggestions!

**Happy movie browsing! 🍿🎬**
