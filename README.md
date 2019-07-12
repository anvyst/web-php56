PHP5.6 Docker Image
---

Generic configuration with major tools to run PHP5.6 setup

## Usage

You can pull the image from Docker Hub: 

```bash
docker pull anvyst/web-php5.6
```


Quick memo on the docker run:

```bash
docker build -t anvyst/web-php5.6:1.0 .
```

To build with volume load:

```bash
docker run -d --name <name_of_container> -v <host_code_path>:<container_code_path> -p <host_port>:<container_port> anvyst/web-php56:1.0 ping 8.8.8.8
```

To run the container:

```bash
docker exec -it <name_of_container> /bin/bash
```
