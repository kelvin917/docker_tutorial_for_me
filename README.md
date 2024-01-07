# docker_tutorial_for_me

# Installation Own Dockerfile 
1. Install `Docker Desktop`
2. Open your location file
3. use vscode open file 
5. create `Dockerfile` file
6. edit `Dockerfile` ## Dockerfile


## Dockerfile (example - node.js)
```
FROM node:20-alpine

WORKDIR <FilePath>

COPY . .

CMD <run Code> [example:('node hello.js')]
```

