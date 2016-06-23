# sanbi-bika-docker


Since there are several docker build, which we need to perform, we need `docker-compose`

Follow https://docs.docker.com/compose/install/, for more information:


```
curl -L https://github.com/docker/compose/releases/download/1.6.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
docker-compose --version
docker-compose version: 1.6.2
```


## Finally to build plone:

```
# this runs the sequence of docker builds.
docker-compose up -d
```
