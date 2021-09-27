# Docker-in-Jenkins

This docker-compose file could map a docker UNIX Socket to TCP Socket so that you won't this problem in Jenkins:

```
dial unix /usr/run/docker.sock: connect: Permission denied
```