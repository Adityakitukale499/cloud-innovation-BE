# cloud-innovation-BE

````markdown
# Movie API Server

This Node.js Express server provides movie data from a JSON file, allowing you to retrieve, filter, and sort movies.

## Features

- Retrieve all movies
- Filter movies by rating
- Sort movies by release year

## Getting Started

### Prerequisites

- Node.js and npm installed on your system

### Installation and Running

1. **Clone the repository and navigate into the directory:**

   ```bash
   git clone https://github.com/Adityakitukale499/cloud-innovation-BE.git
   cd cloud-innovation-BE
   ```
````

2. **Install dependencies and start the server:**

   ```bash
   npm install
   npm start
   ```

The server runs at `http://localhost:8000`.

## API Endpoints

### Get All Movies

- **URL**: `/movies`
- **Method**: `GET`
- **Query Parameters**:

  - `rating`: Comma-separated list of ratings (e.g., `rating=3,5`)
  - `order`: Sort by year, `asc` or `desc`

- **Example**: `GET /movies?rating=5&order=asc`

### Get Movie by ID

- **URL**: `/movie/:id`
- **Method**: `GET`

- **Example**: `GET /movie/20`

## JSON Data File

Movies are stored in `db.json`:

```json
{
  "movies": [
    {
      "id": 20,
      "Title": "The Pirates of Somalia",
      "Year": "2017",
      "imdbID": "tt5126922",
      "Type": "movie",
      "rating": 5,
      "Poster": "https://m.media-amazon.com/images/M/MV5BMjA2OTIwNjA0NV5BMl5BanBnXkFtZTgwMDYxNTYxNDM@._V1_SX300.jpg"
    },
    ...
  ]
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are welcome.

## Contact

Created by [Your Name](mailto:youremail@example.com) - feel free to contact me!

```

### Instructions to Use This README

- **Replace Placeholder Information:**
  - Update `"https://github.com/yourusername/movie-api-server.git"` with your actual GitHub repository URL.
  - Include your name and contact information in the "Contact" section.

### How to Use

- **Save this content** as `README.md` in the root directory of your project.
- This version combines all steps into one smooth workflow, making it easy for users to follow the instructions and run your Movie API server.
```
