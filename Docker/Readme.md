<h1 align="center">Docker</h1>

![Docker Setup](../public/logo-docker.png)
Docker is an operating system-level virtualization solution for delivering software in packages called containers.

We assume users have Docker correctly installed on their computer if they wish to use this feature. Docker is available for Linux as well as macOS and Windows. For more details, visit: [https://www.docker.com/](https://www.docker.com/).

## Running the E-commerce Website with Docker

### Quick Start

To run this E-commerce Website with Docker, take the following steps:

1. **Clone the repository and navigate to the Docker directory:**

   ```bash
   git clone https://github.com/Kalpeshgunjal07/React-Ecomerce-WebSite.git
   cd React-Ecomerce-WebSite

   ```

2. **Build the Docker image:**
   ```bash
   docker build -f Docker/Dockerfile -t ecommerce-website .
   ```
3. **Run the Docker container:**
   ```bash
   docker run -p 8080:80 ecommerce-website:latest
   ```
4. **Access the application:**
   Open your browser and navigate to http://localhost:8080. Your E-commerce Website should now be running in a Docker container.
