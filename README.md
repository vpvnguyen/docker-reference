# docker-reference

Learning and experimenting with Docker containers

## Setup (Windows)

- Enable virtualization
  > AMD: SVM Mode
- Update Windows to latest build
- Install/Update the WSL 2 Linux kernal
  > https://docs.microsoft.com/en-us/windows/wsl/wsl2-kernel
- Install Docker
- Follow Docker setup steps from docs
- If the tutorial was followed, navigate to `http://localhost/tutorial/` for getting started docs

## Command Syntax

```
docker run -d -p 80:80 docker/getting-started
```

- `-d` - run the container in detached mode (in the background)
- `-p 80:80` - map port 80 of the host to port 80 in the container
- `docker/getting-started` - the image to use

> Combine single character flags to shorten the full command: `docker run -dp 80:80 docker/getting-started`
