# traefikv2-docker-swarm
Stack para desplegar traefik en un nodo manager de docker swarm


$ docker network create -d overlay proxy

$ docker stack deploy -c traefik.yml traefik

