# docker_commands
<HR>
docker-machine start node_name;                 #Use to start a stopped node
docker-machine stop node_name;                  #Use to stop a running node
docker-machine ls;                                         #Use to check docker nodes
docker-machine ip node_name;                      #Use to check ip of a node
docker node ls;                                                #Use to check node list
docker ps;                                                        #Use to check running services;
docker service scale web=6;                           #Use to scale a application
docker service logs -f service_name;              #Use to see the log of a service
docker node inspect self;                                #Use to check node information
docker node inspect node_name                    #Use to check node information
docker node ps node_name;                           #Use to check running services in a node
docker node inspect — pretty node_name;    #Use to check node information 
docker container ls                                         #Use to check container list
docker container rm container_name;            # Use to remove a container
docker image ls;                                            # Use to check image list
docker image rm image_name;                     #Use to remove image
docker-compose build                                   #Use to build images 
docker-compose up                                        #Use to deploy images
docker-compose up --build                           #Use to deploy images after build
docker-compose down                                  #Use to shutdown container
docker exec -it docker-mysql bash;              #Use to access mysql container
docker stack services  book_manager;         # Use to check services under book_manager stack
docker stack rm service_name                     #Use to remove a service from stack
docker stack ls                                              # Use to check stack list
