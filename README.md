# BUILD-DOCKER from GitHub

## Building root level Dockerfile - main branch

```sh
docker build https://github.com/htetkyawoo/build-docker.git -t build-docker:main
```

## Building root level Dockerfile - snapshot branch

```sh
docker build https://github.com/htetkyawoo/build-docker.git#snapshot -t build-docker:snapshot
```

## Building nested level Dockerfile - main branch

```sh
docker build https://github.com/htetkyawoo/build-docker.git#:nested -t build-docker:main
```

## Building nested level Dockerfile - snapshot branch

```sh
docker build https://github.com/htetkyawoo/build-docker.git#snapshot:nested -t build-docker:snapshot
```
