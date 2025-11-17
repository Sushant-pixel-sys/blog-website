# Simple Blog

Two-page static blog (index + about). Built with HTML/CSS and containerized using nginx.

## Run with Docker (local)
1. Build: `docker build -t simple-blog:latest .`
2. Run: `docker run -d -p 8080:80 --name simple-blog simple-blog:latest`
3. Open: http://localhost:8080
