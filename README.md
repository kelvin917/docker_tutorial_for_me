# docker_tutorial_for_me

# Installation Own Dockerfile 
1. Install `Docker Desktop`
2. Open your location file
3. use vscode open file
4. create your own project. For example: `hello.js` file here.
5. create `Dockerfile` file
6. edit `Dockerfile` ## Dockerfile
7. run terminal
8. `docker build -t <ProjectName> <ProjectLocation>`
9. `docker images` - check the project is already successful or not.


## Dockerfile (example - node.js)
```
FROM node:20-alpine

WORKDIR <FilePathNameInDockerList> [example:('/app')]

COPY . .

CMD <run Code> [example:('node hello.js')]
```

