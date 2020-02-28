# Architecture

The entire system design base is power in the distribution of the contained data by using inter-relational services, so the amount of functionalities placed in a single services must be reduces to one and only one, this will allow to make services to work properly with each other. In order to make services to interact as desire we need to create a cohirent form, so the design pattern used includes a **coore** library that provides all interaction rules.

All backend services are docker images that will run on a docker environments, a Docker Swarm should be easily to use. There are services on various technologies provides Docker environment administration like [Portainer][portainer] and several other but this one is the one we have been using during the test and development process and rightly adjust to the needs of this project.

## Development

***Yet to be written***

[Return to readme](../README.md)

[portainer]:https://github.com/portainer/portainer
