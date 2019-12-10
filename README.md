### Gamedoora Incubator
Docker files to setup and run the gamedoora app

##### STEPS TO RUN:
1.```docker-compose build```
2. ```docker-compose up -d```
3. ```docker-compose logs -f```

##Most used docker commands:
1. ```docker-compose build``` to build all applications
2. ```docker-compose build <application_name>``` to build particular application
3. ```docker-compose up``` to run all application in terminal
4. ```docker-compose up -d``` to run all application in terminal in detached mode
5. ```docker-compose up <application_name>```to run single application in terminal 
6. ```docker-compose up -d <application_name>```to run single application in detached mode
7. ```docker-compose ps``` to see all the applications running with their port
8. ```docker ps``` to see the containers list
9. ```docker images``` to see the list of images
10. ``` docker-compose stop <application_name>``` to stop a application
11. ``` docker-compose rm <application_name>``` to remove a application from list
12. ```docker exec -it <container_id> bash``` to go into the container using container_id received from "docker ps"
13. ```docker-compose logs -f``` to view current logs of all applications
14. ```docker-compose logs -f <application_name>``` to view current logs for particular application
15. ```docker stop $(docker ps -a -q)``` stop all the stopped containers
16. ```ddocker rm $(docker ps -a -q)``` kill all the stopped containers
17. ```docker images -a``` to list all the images
18. ```docker rmi $(docker images -a -q)``` to remove all the images

#####Reference: https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes

