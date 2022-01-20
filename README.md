# Project Zomboid Server

## Usage

### Start server
```shell
# run server in detached mode
docker-compose up -d

# view logs
docker-compose logs -f
```

### Stop server
```shell
docker-compose stop
```

## Folders
- `server-data` - mandatory if you want to keep configuration between each restart
- `server-files` - optional, contains all the files of the application

## Configuration
The server config is located at `/server-data/Server/pzserver.ini` (Will be created after first start)

## Admin Commands
see [pzwiki.net](https://pzwiki.net/wiki/Dedicated_Server#Admin_Commands)


## Docker image
Image is [afey/zomboid](https://hub.docker.com/r/afey/zomboid) from dockerhub. 
If you need more information, checkout the readme.
