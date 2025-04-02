## docker --network

### Create a network
```bash
docker network create favorite-net
```
### List networks
```bash
docker network ls
```
### Inspect a network
```bash
docker network inspect favorite-net
```
### Remove a network
```bash
docker network rm favorite-net
```
### Connect a container to a network
```bash
docker network connect favorite-net my-container
```
### Disconnect a container from a network
```bash
docker network disconnect favorite-net my-container
```

