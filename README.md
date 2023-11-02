# Library API OpenAPI Specification

This OpenAPI spec defines the Library API, allowing you to manage books and authors.

## API Details

- **Title:** Library API
- **Version:** 1.0.0
- **Description:** STD22005
- **Base URL:** [https://library.com](https://library.com)

## Endpoints

### Books

- **GET /books**: Retrieve all books.
- **PUT /books**: Create or update books.

### Authors

- **GET /authors**: Retrieve all authors.
- **PUT /authors**: Create or update authors.
- **DELETE /authors**: Delete an author.

## Data Schemas

- **Book**: `id`, `bookName`, `author` (Reference), `pageNumbers`, `topic`, `releaseDate`
- **Author**: `id`, `name`, `sex` (M/F)

## Usage

Interact with the API via HTTP clients or explore it in [Swagger UI](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/FanomezanaNat/library-management/TD1/docs/api.yml).

