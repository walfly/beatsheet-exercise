# BeatSheet Exercise Starter
This guide provides instructions on how to run the beetsheet backend in a docker container.

## Requirements

To use this Docker container, you will need to have Docker installed on your system. If you do not have Docker installed, you can download it from [here](https://www.docker.com/products/docker-desktop).

## How to Run Docker Compose

1. Run the following command to create the Docker container:

    ```bash
    docker compose create
    ```

2. Run the following command to start the Docker container:

    ```bash
    docker compose start
    ```

Alternatively, you can create and start the container by running:

    ```bash
    docker compose up
    ```
  
This command will start the Docker container defined in the `docker-compose.yml` file. The BeatSheet API will be accessible at the port defined in the `docker-compose.yml` file.

## Notes
Please ensure that the port defined in the `docker-compose.yml` file is not being used by any other applications to avoid any port conflict.
