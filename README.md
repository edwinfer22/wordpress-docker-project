# WordPress Docker Project

This project runs a WordPress site using Docker and Docker Compose. It includes a WordPress service and a MySQL database service.

## Prerequisites

- Docker
- Docker Compose

## How to Run

1.  Clone this repository.
2.  Navigate to the project directory.
3.  Run the following command to start the services in the background:
    ```sh
    docker-compose up -d
    ```

## Accessing the Site

Once the containers are running, you can access the WordPress installation by navigating to the following URL in your web browser:

[http://localhost:8000](http://localhost:8000)

## Stopping the Services

To stop all the running services, use the command:

```sh
docker-compose down
```
