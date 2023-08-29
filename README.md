# HelloWorld-Node-Docker

This is a simple Node.js application that uses Docker to run a web server and display a "Hello, World" message.

## Prerequisites

Before running this application, make sure you have the following installed on your machine:

- Node.js
- Docker

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Lalatenduswain/Hello-World-Node-Docker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd HellowWorld-Node-Docker
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

To start the application, run the following command:

```bash
npm start
```

This will start the web server on port 8080. You can access the application by opening your browser and navigating to [http://localhost:8080](http://localhost:8080).

## Docker

Alternatively, you can use Docker to run the application. Make sure you have Docker installed and running on your machine.

1. Build the Docker image:

   ```bash
   docker build -t helloworld-node-docker .
   ```

2. Run the Docker container:

   ```bash
   docker run -p 8080:8080 helloworld-node-docker
   ```

Again, you can access the application by opening your browser and navigating to [http://localhost:8080](http://localhost:8080).

## Contributing

If you would like to contribute to this project, feel free to submit a pull request. Any contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
