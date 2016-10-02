# docker-cleaner

an alpine docker image to clean docker every hour

uses [`docker-gc`](https://github.com/spotify/docker-gc)

## how to

### install

install `docker`, then

```shell
git clone https://github.com/ahdinosaur/docker-cleaner
```

### build

```shell
docker build -t ahdinosaur/docker-cleaner .
```

### run

```shell
docker run -i ahdinosaur/docker-cleaner
```

### publish

```shell
docker push ahdinosaur/docker-cleaner
```
