# Comp Soc Docker-Compose Configs

These are the Docker-Configs used to power most of TU Dublin Computer Societys Services.
Most of the services are deployed on Docker Swarm and replicated across the nodes automatically.

All storage is within the /docker folder at the root of the filesystem.
For Wordpress installations a custom uploads.php is required to remove the file size restriction for uploads.

Within the service folder:
```sh
$ docker-compose up -d

Or

$ docker stack deploy -c docker-compose.yml test
```

To Take Down Services:
```sh
$ docker-compose down

Or

$ docker stack rm test
```
