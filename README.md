compose-mesos
-------------

A [docker-compose](https://docs.docker.com/compose/yml) setup for a local Mesos cluster based on the article [Mesos Sandbox Using Docker Compose](https://spof.io/blog/2015/06/23/mesos-sandbox-using-docker-compose)

Example:

```
docker-compose up
open http://docker.local:5050
```

Add `docker.local` to your `/etc/hosts` or replace it with whatever makes sense for your setup.
