# Go_Backend_Project

A beginner-friendly REST API project built with Go, designed for learning CRUD operations.

## Project Structure

```
go_crud_project/
├── cmd/
│   └── students-api/
│       └── main.go
├── config/
│   └── local.yaml
├── storage/
│   └── storage.db
├── go.mod
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites
- Go 1.16 or higher installed
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Rishiraj029/Go_Backend_Project.git
cd Go_Backend_Project
```

2. Install dependencies:
```bash
go mod download
```

3. Run the application:
```bash
go run cmd/students-api/main.go
```

## Features

- RESTful API endpoints
- CRUD operations for student management
- YAML-based configuration
- SQLite database storage

## Configuration

Edit `config/local.yaml` to configure your local development environment.

## License

This project is open source and available under the MIT License.

## Author

Rishiraj029
