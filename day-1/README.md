# The Setup 

# The docker file 

```
FROM golang:1.15-alpine as dev
WORKDIR /work
```

# Build the docker file 
```
cd day-1
docker build --target dev . -t go
docker run -it -v ${PWD}:/work go sh // this is windows powershell
docker run -it -v $(pwd -W):/work go sh // this is git bash 
go version

```