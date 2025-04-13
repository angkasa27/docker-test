*COMMAND*

Init new docker
`docker init`

Run Docker Compose (make sure has compose.yaml)
`docker compose up`

Watch Docker Compose (make sure has compose.yaml)
`docker compose watch`

Check all running container
`docker ps`

Check all available container
`docker ps -a`

Stop running container
`docker stop [First 3 Digit of CONTAINER ID]`
`docker stop 33a`

Remove all container
`docker container remove`

Remove specific STOP container 
`docker rm [First 3 Digit of CONTAINER ID]`
or 
`docker rm [3digits] --force` to kill it


*PUBLISH DOCKER IMAGE*

tag it 
`docker tag react-docker angkasa27/react-docker`

then push it
`docker push angkasa27/react-docker`

