# Sample docker application

Echos "Hello world!" when run.

Requires:
* [Docker](https://www.docker.com/)
* [Boot2Docker](http://boot2docker.io/)
* JDK (to compile java file locally)

To run:

```
# compile class
javac helloworld.java

# build image
docker build -t SampleDockerProject .

# run image
docker run -it --rm --name my-running-app SampleDockerProject
```
