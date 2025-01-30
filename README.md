# E-Commerce Web Application

Welcome to the **ecom-web-app** repository! This project is a containerized e-commerce web application designed for deployment using Docker Compose.

## Repository Structure

```
ecom-web-app/
├── api/                   # Backend API service
├── web/                   # Frontend web application
├── docker-compose.yml     # Docker Compose configuration
└── README.md              # Project documentation
```

## Prerequisites

- **Docker:** Ensure Docker is installed on your system. [Get Docker](https://docs.docker.com/get-docker/)

## Setup and Deployment

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/Kavetec/ecom-web-app.git
   cd ecom-web-app
   ```

2. **Build and Start Services:**

   Use Docker Compose to build and run the application services:

   ```sh
   docker-compose up --build -d
   ```

   - The `--build` flag builds the images before starting the containers.
   - The `-d` flag runs the containers in detached mode.

3. **Access the Application:**

   Open your browser and navigate to [http://localhost](http://localhost) to view the e-commerce site.

## Shutting Down

To stop and remove the application containers, execute:

```sh
docker-compose down
```

## Contributing

We welcome contributions! To get started:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request for review.

## Contact

For questions or support, please reach out via the Kavetec community.

