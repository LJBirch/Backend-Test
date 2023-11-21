# Backend-Test

## Getting Started

These instructions will get you a copy of the API up and running on your local machine.

### Prerequisites

- Docker
- Git (optional, if you're cloning the repository)

### Installing

1. **Build the Docker Image**:

    Navigate to the directory containing the Dockerfile and run:

    ```bash
    docker build -t infer_api .
    ```

2. **Run the Docker Container**:

    ```bash
    docker run -p 8000:8000 infer_api
    ```

    This command runs the container and maps port 8000 of the container to port 8000 on your host machine.


### Using the Application

#### Accessing the API

Once the container is running, you can access the API endpoints at `http://localhost:8000`.

##### Available Endpoints

- `/infer` (POST): For inferring images. You need to send an image.

#### Test Images

In the `images` folder, you will find test images that you can use to test the `/infer` endpoint.


