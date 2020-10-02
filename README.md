# snort-docker
Docker file for snort

This is a dockerfile for easy installation of Snort in a linux environment

# To run the Dockerfile
```
docker build -t snortweb . --build-arg PPORK_OINKCODE=<your-oink-code-from-snort.org>
docker run -P8080:8080 snortweb
```
Once running, visit http://localhost:8080/
