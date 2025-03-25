# Docker Scout demo service
![scout-demo-service-tutorial](https://socialify.git.ci/julioaranajr/scout-demo-service-tutorial/image?description=1&language=1&name=1&owner=1&pattern=Solid&theme=Dark)

A repository containing an application and Dockerfile to demonstrate the use of Docker Scout to analyze and remediate CVEs in a container image.

Read the [Docker Scout Quickstart](https://docs.docker.com/scout/quickstart) for a full walkthrough. You can build and run the image with the following command:

```shell
docker build -t scout-demo:v1 .
docker run scout-demo:v1
```

The application consists of a basic ExpressJS server and uses an intentionally old version of Express and Alpine base image.
