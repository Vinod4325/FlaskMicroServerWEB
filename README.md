# Build Status Badge: ![](https://github.com/automate6500/python-web-app-cicd/workflows/Pipeline/badge.svg)

# Use Case: Continuous Integration and Delivery
Demonstrating GitHub-native CI/CD with GitHub Actions

Files include:

- Python web app and requirements.txt
- Dockerfile for creating a container for the app
- CI pipeline for linting and tests
- CD pipeline that builds and publishes Docker images to GHCR

:D


Deploy Commands : 

	docker pull ghcr.io/vinod4325/flaskmicroserverweb/flask-app:latest 	
	docker run -d --name flask-app --restart always -p 8080:5000 ghcr.io/vinod4325/flaskmicroserverweb/flask-app:latest 	