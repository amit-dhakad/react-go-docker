# Dockerized React and Go Lang Sample Project

This project demonstrates how to use Docker to containerize a sample application with a frontend built using React and a backend built using Go Lang.

## Table of Contents

- [Dockerized React and Go Lang Sample Project](#dockerized-react-and-go-lang-sample-project)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
    - [Building the Docker Image](#building-the-docker-image)
    - [Running the Docker Container](#running-the-docker-container)
    - [Usage](#usage)
    - [Project Structure](#project-structure)
    - [Contributing](#contributing)
    - [License](#license)

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- Docker: [Installation Guide](https://docs.docker.com/get-docker/)
- Git: [Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Getting Started

Follow these steps to get the project up and running on your local machine:

### Building the Docker Image

 Clone the repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

1.Navigate to the project directory:

```bash
cd <project-directory>
```

2.Build the Docker image using Docker Compose:

```bash
docker-compose build
```

### Running the Docker Container

1.Start the Docker container:

```bash
docker-compose up
```

Open your web browser and visit http://localhost:3000 to access the React frontend.

Test the backend API by visiting http://localhost:8080/api.

### Usage

- The React frontend is accessible at http://localhost:3000.
- The Go backend API is accessible at http://localhost:8080/api.

### Project Structure

The project directory is structured as follows:

```go
project-root/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── Dockerfile
│   └── ...
│
├── backend/
│   ├── main.go
│   ├── go.mod
│   ├── go.sum
│   └── ...
│
├── docker-compose.yml
└── README.md
```

### Contributing
Contributions are welcome! Feel free to submit issues and pull requests.

### License
This project is licensed under the MIT License.