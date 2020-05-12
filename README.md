# Contêiner Mínimo com Golang


## Step 1

Command to build

```shell
docker build -t hello-golang-simple:1.0 . -f Dockerfile.simple
```

Commando to run

```shell
docker run -it hello-golang-simple:1.0
```

## Step 2 - Minimize

Command to build

```shell
docker build -t hello-golang-simple:1.1 . -f Dockerfile.multi
```

Commando to run

```shell
docker run -it hello-golang-simple:1.1
```

## Step 3 - Final

Command to build

```shell
docker build -t hello-golang-json:1.0 . -f Dockerfile.final
```

Commando to run

```shell
docker run -it -p 8030:8030 --name example-golang hello-golang-json:1.0 
```


## Referências

[Building Minimal Docker Containers for Go Applications](https://rollout.io/blog/building-minimal-docker-containers-for-go-applications/)

[https://www.callicoder.com/docker-golang-image-container-example/](https://www.callicoder.com/docker-golang-image-container-example/)

[GoLang e Docker](https://medium.com/trainingcenter/golang-e-docker-d2d9dedd82c0)

[Create the smallest and secured golang docker image based on scratch](https://medium.com/@chemidy/create-the-smallest-and-secured-golang-docker-image-based-on-scratch-4752223b7324)

[Building Minimize Golang Executable Docker Image with Alpine Linux](https://dinolai.com/notes/golang/minimize-golang-executable-docker-image-with-alpine-linux.html)

[Containerize This! How to build Golang Dockerfiles](https://www.cloudreach.com/en/resources/blog/cts-build-golang-dockerfiles/)

[Create a Docker image for GO](https://codefresh.io/docs/docs/learn-by-example/golang/golang-hello-world/)

[Golang Response Snippets: JSON, XML and more](https://www.alexedwards.net/blog/golang-response-snippets)