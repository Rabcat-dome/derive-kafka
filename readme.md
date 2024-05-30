# no suitable node (scheduling constraints not satisfied on 2 nodes; unsupported platform on 1 node)

docker pull --platform linux/amd64  obsidiandynamics/kafdrop:latest

docker stack deploy -c kafka.yml --resolve-image never kafka