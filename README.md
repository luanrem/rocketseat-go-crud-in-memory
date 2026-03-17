# In-Memory CRUD API in Go

A beginner-friendly Go challenge focused on building a REST API. The goal is to develop a User CRUD (Create, Read, Update, Delete) system with in-memory storage, practicing core HTTP concepts such as methods, status codes, and JSON handling in Go.

## About

This project is a practical challenge from [Rocketseat](https://www.rocketseat.com.br/) designed to reinforce fundamental Go and HTTP skills by building a complete REST API from scratch — no database required.

## Features

- Create a new user
- List all users
- Get a user by ID
- Update a user
- Delete a user

## Tech Stack

- [Go](https://go.dev/)

## Getting Started

### Prerequisites

- [Go 1.21+](https://go.dev/dl/)

### Running

```bash
go run main.go
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/users` | Create a new user |
| GET | `/users` | List all users |
| GET | `/users/{id}` | Get a user by ID |
| PUT | `/users/{id}` | Update a user |
| DELETE | `/users/{id}` | Delete a user |

## License

This project is for educational purposes.