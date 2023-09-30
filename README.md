# swarm + portainer

# portainer

Projeto Portainer 

para rodar o swarm 

Criando os node manager01 


docker swarm init --advertise-addr MANAGER-IP

em seguida será gerado o token para aplicar nas outras maquinas

caso necessite recuperar o token digite seguinte comando no node manager

docker swarm join-token worker

comando para listar os nodes

docker node ls

comando para promover um node para manager

docker node promote HOSTNAME NODE

chmod +x start.sh
./start.sh


