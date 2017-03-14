# Discovering Docker

## Questions

1. What is Docker?
2. How does Docker save you time and money?
3. What is a container and what is an image?
4. What is layering?

## Answers

1. Docker unifies various technologies for deployment. Seperation of
configuration and resource allocation.
   - Replace some VM use cases
   - Prototype software without disrupting host environment
   - Package software
   - Microservice architecture
   - Model Networks
   - Offline fullstack productivity
   - Reduce debugging overhead
   - Document software dependencies
   - Continuous delivery
2. Common pipeline with single output used on any target.
3. image is like a class, container is like a object
4. When a file is changed it is copied to a new layer. Layers are like diffs
between file systems.

## Notes

- Docker in Action by Jeff Nickoloff for thorough treatment of Docker basics.

### Key Concepts

- Images
- Containers
- Layers

### Docker Commands

- `docker build` - Build a Docker image (from Dockerfile?)
- `docker run` - Run a Docker iamge as a container
- `docker commit` - Commit a Docker container as an image
- `docker tag` - Tag a Docker image

### Creating a Docker Image

- Set up a container with `docker run` and do `docker commit` (technique 14)
- Write a Dockerfile and do `docker build`
- Configuration management tool (technique 47)
- Scratch image and import a set of files (technique 10)