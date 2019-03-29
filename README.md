# Comp Soc Docker-Compose Configs

These are the Docker-Configs used to power most of DIT Comp Soc's services, 
All storage is within the /docker folder at the root of the filesystem.
For Wordpress installations a custom uploads.php is required to remove the file size restriction for uploads.

Within the service folder:
```sh
$ docker-compose up -d
```

To Take Down Services:
```sh
$ docker-compose down
```
