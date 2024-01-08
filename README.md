# docker_tutorial_for_me

# Installation Own Dockerfile 
1. Install `Docker Desktop`
2. Open your location file
3. use vscode open file
4. create your own project. For example: `hello.js` file here.
5. create `Dockerfile` file
6. edit `Dockerfile` ## Dockerfile
7. run terminal
8. docker build -t <ProjectName> <ProjectLocation> `docker build -t hello_docker .` (. means you already inside project location that have `Dockerfile`)
9. `docker images` - check the project is already successful or not.
10. * if you want to run operating system path. you can use `docker run -it <ProjectName> sh`.


## Dockerfile (example - node.js)
```
FROM node:20-alpine

WORKDIR <FilePathNameInDockerList> [example:('/app')]

COPY . .

CMD <run Code> [example:('node hello.js')]
```

### Docker run localhost code 
`docker run -p 5173:5173 <project_name>`

### Check Docker port
`docker ps`

### Stop Docker port
`docker stop <container_id>` - container id can use the first character. For example: `docker stop as2`

### remove Docker daemon
`docker rm <conatiner_id> --force`

### RUNNING LIVE CODE DOCKER 
`docker run -p 5173:5173 -v "$(pwd):/app" react-project`

