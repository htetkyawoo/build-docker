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

## Building root level Dockerfile - tag v1.0.0

```sh
docker build https://github.com/htetkyawoo/build-docker.git#v1.0.0 -t build-docker:1.0.0
```

## Building nested level Dockerfile - tag v1.0.0

```sh
docker build https://github.com/htetkyawoo/build-docker.git#v1.0.0:nested -t build-docker:nested-1.0.0
```
