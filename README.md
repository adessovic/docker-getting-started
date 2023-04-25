# Development with Docker

- Build, Run and Remove Docker Container

## Build the Container
Navigate to `/app` directory and run command 

```
docker build -t docker-getting-started .
```

## Start the app container

```
docker run -dp 3030:3030 docker-getting-started
```

Once it has started, open your browser an navigate to [http://localhost:3030](http://localhost:3030).

## Development

This project has a `docker-compose.yml` file, which will start the mkdocs application on your
local machine and help you see changes instantly.

```bash
docker compose up
```
Once development environment has started, open your browser and navigate to [http://localhost:8000](http://localhost:8000).

