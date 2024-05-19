# Multi-Tech Project

## Overview

This repository contains three components:
- Go apps
- Next.js (TypeScript) apps
- WordPress site

## Setup

### Prerequisites
- Docker
- Docker Compose

### Running the apps

1. Clone the repository:
    ```sh
    git clone https://github.com/chamans094/multi-tech-app.git
    cd multi-tech-app
    ```

2. Build and run the apps:
    ```sh
    docker-compose up --build
    ```

3. Access the apps:
    - Go app: http://localhost:8080
    - Next.js app: http://localhost:3000
    - WordPress site: http://localhost:8000

## CI/CD

This repository uses GitHub Actions for Continuous Integration and Continuous Deployment. The workflows are defined in the `.github/workflows` directory.

### Coding Standards

- **Go**: Uses `golangci-lint` to enforce coding standards.
- **Next.js**: Uses `ESLint` to enforce coding standards.
- **WordPress**: Uses `PHPCS` to enforce WordPress coding standards.

## Contributing

Please follow the coding standards and ensure that all tests pass before submitting a pull request.


