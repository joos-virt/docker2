# docker2
Docker

https://github.com/hamnsk/go_psql_redis_example

https://gitlab.com/k11s-os/lessons/docker/-/tree/main/Swarm
```
docker swarm init
docker node ls

Run this commands on node to be removed
docker swarm leave
docker node ls

Run this command on master node
docker node rm node2

Add node to Existing Cluster
Run this command on master node
docker swarm join-token worker
```
https://docs.portainer.io/start/install/server/swarm/linux
```
curl -L https://downloads.portainer.io/ee2-18/portainer-agent-stack.yml -o portainer-agent-stack.yml
docker stack deploy -c portainer-agent-stack.yml portainer
docker ps
https://localhost:9443
```


https://github.com/mesaguy/ansible-prometheus

https://github.com/cloudalchemy/ansible-grafana

https://github.com/vegasbrianc/prometheus
