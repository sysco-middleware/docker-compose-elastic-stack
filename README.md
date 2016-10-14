# Docker Compose: Elastic Stack


## With [Docker-Machine](https://docs.docker.com/machine/)

Create one docker-machine

### KVM (Linux)

```bash
docker-machine create --driver kvm --kvm-cpu-count 2 --kvm-memory 4096 elastic-machine0
eval $(docker-machine env elastic-machine0)
```

## Start-up

```bash
docker-compose build
docker-compose up -d
```
