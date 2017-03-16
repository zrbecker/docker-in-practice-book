# Understand Docker

## Covered

- Docker architecture
- Tracing the internal's of Docker on your Host (Debugging?)
- Docker Hub
- Docker Registry
- Container communication

## Notes

- Can I restrict which repositories my Docker daemon will attempt to obtain
images from? Mainly can I restrict images from DockerHub?

## Architecture

- Docker cli talks to Docker daemon through RESTful API.
- Docker daemon talks to Docker Hub and other public/private respositories which
store Docker images. (We should be able to regenerate an internal private
Docker repository from documents stored in the version control repository)
