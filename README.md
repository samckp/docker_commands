# docker_commands
<HR><BR>
docker-machine start node_name;                 #Use to start a stopped node  <BR>
docker-machine stop node_name;                  #Use to stop a running node  <BR>
docker-machine ls;                                         #Use to check docker nodes   <BR>
docker-machine ip node_name;                      #Use to check ip of a node   <BR>
docker node ls;                                                #Use to check node list   <BR>
docker ps;                                                        #Use to check running services;   <BR>
docker service scale web=6;                           #Use to scale a application   <BR>
docker service logs -f service_name;              #Use to see the log of a service   <BR>
docker node inspect self;                                #Use to check node information   <BR>
docker node inspect node_name                    #Use to check node information  <BR>
docker node ps node_name;                           #Use to check running services in a node  <BR>
docker node inspect — pretty node_name;    #Use to check node information   <BR>
docker container ls                                         #Use to check container list  <BR>
docker container rm container_name;            # Use to remove a container  <BR>
docker image ls;                                            # Use to check image list  <BR>
docker image rm image_name;                     #Use to remove image  <BR>
docker-compose build                                   #Use to build images   <BR>
docker-compose up                                        #Use to deploy images  <BR>
docker-compose up --build                           #Use to deploy images after build  <BR>
docker-compose down                                  #Use to shutdown container  <BR>
docker exec -it docker-mysql bash;              #Use to access mysql container  <BR>
docker stack services  book_manager;         # Use to check services under book_manager stack  <BR>
docker stack rm service_name                     #Use to remove a service from stack  <BR>
docker stack ls                                              # Use to check stack list  <BR>
