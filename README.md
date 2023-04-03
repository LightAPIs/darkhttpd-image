# darkhttpd-image

> darkhttpd Docker Image

## Usage

```sh
# pull
docker pull giterhub/darkhttpd:latest

# run
docker run -d \
    --name darkhttpd \
    --restart unless-stopped \
    -p 80:80 \
    -v $PWD:/www \
    giterhub/darkhttpd:latest /www
```

## Docker Hub Image

- [giterhub/darkhttpd](https://hub.docker.com/r/giterhub/darkhttpd)

## Credits

- [emikulic/darkhttpd](https://github.com/emikulic/darkhttpd)
