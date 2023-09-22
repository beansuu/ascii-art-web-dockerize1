Hello! Please use WSL for this program.
This is a program which takes text and transforms it into ascii

Authors: aburnaz & mtalli

### INSTALL DOCKER WINDOWS

1. download and install https://docs.docker.com/desktop/install/windows-install/
2. sing up
3. Start Docker Desktop

use WSL terminal
```bash
docker info
```
### now it works

### to build Container
```bash
docker build -t ascii-art-web-dockerize .
```
  install requierments

### to run Container
```bash
docker run --name=ascii-art-web-dockerize -p 80:8080 ascii-art-web-dockerize
```
**OR you can run this in your vscode terminal and it will build and run the Container automatically**
**bash run.sh**
## type in browser for Testing
http://localhost/docker
or
localhost:80

### to stop Container
```bash
docker stop ascii-art-web-dockerize
```

### to prune Container
```bash
docker builder prune -a
```


# ascii-art-web-docker

Here is an example of the website style: https://i.imgur.com/oVVEiRc.png

Enjoy! :D