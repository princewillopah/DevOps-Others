# static site structure 
my-website/
├── index.html
├── styles.css
├── Dockerfile
└── nginx.conf

#  Build the Docker Image
docker build -t my-website .

# Run the Docker Container
docker run -d -p 80:80 my-website
# Verify
Open your web browser and navigate to http://localhost to see your website running.

Summary
- HTML and CSS files: Define your webpage content and styles.
- Nginx configuration file: Customizes the Nginx server settings.
- Dockerfile: Sets up the Docker image using Nginx and your website files.
- Docker commands: Build and run the Docker container to serve your website.
This setup will serve your static website using Nginx inside a Docker container.