To create the docker image

`cd react-docker`
`docker build -t react-docker .`

To run this docker file
`docker run -p 5173:5173 react-docker`

To run and reflect changes / automatically copy changes to docker without rebuilding it
`docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker`
