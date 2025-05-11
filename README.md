# Movies API

A simple RESTful API for managing movies, built with Go.

## Features

- Add, update, delete, and retrieve movies.
- Search movies by title or genre.
- Lightweight and fast.

## Prerequisites

- [Go](https://golang.org/dl/) (version 1.18 or higher)
- A terminal or command prompt

## Installation

1. Clone the repository:
     ```bash
     git clone https://github.com/codewithtanvir/golang-crud-api
     cd movies-api
     ```

2. Install dependencies:
     ```bash
     go mod tidy
     ```

3. Run the application:
     ```bash
     go run main.go
     ```

## API Endpoints

### Base URL
```
http://localhost:8080
```

### Endpoints

| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | `/movies`        | Get all movies           |
| GET    | `/movies/{id}`   | Get a movie by ID        |
| POST   | `/movies`        | Add a new movie          |
| PUT    | `/movies/{id}`   | Update a movie by ID     |
| DELETE | `/movies/{id}`   | Delete a movie by ID     |

### Example Request

#### Add a Movie
```bash
POST /movies
Content-Type: application/json

{
  "title": "Inception",
  "genre": "Sci-Fi",
  "year": 2010
}
```

#### Response
```json
{
  "id": 1,
  "title": "Inception",
  "genre": "Sci-Fi",
  "year": 2010
}
```

## Project Structure

```
movies-api/
├── main.go
└── README.md
```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or suggestions, feel free to reach out:


- GitHub: [codewithtanvir](https://github.com/codewithtamvir)#
