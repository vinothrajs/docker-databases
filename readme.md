
# To Run the data base in the local machine or server

### Download the entire project 
### Install Docker and Docker Compose in the machine 
### use the below command to run the project

### Navigate to specific DB
1.  Mongo DB
```
cd mongo
```
2. Run the below command
```
docker-compose  up -d
```
# check for running containors
```
docker ps
```
# To Prune the volumes and data in DB
```
docker system prune -a --volumes
```
# To Stop the containor 
```
docker-compose down
```
# To View the logs of DB
```
docker logs container_name
```

