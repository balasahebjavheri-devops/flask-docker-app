# Flask Docker App

A simple Flask application containerized with Docker, demonstrating core Docker concepts: image building, port mapping, and Docker Hub deployment.

## Tech Stack
Python, Flask, Docker

## Routes
- `/` — returns a welcome message
- `/health` — returns a health check JSON response

## Run Locally
\`\`\`bash
docker build -t flask-docker-app .
docker run -d -p 5000:5000 flask-docker-app
curl localhost:5000
\`\`\`

## Docker Hub
Pull this image directly:
\`\`\`bash
docker pull balasahebjavheri1995/my-flask-app
\`\`\`# flask-docker-app
