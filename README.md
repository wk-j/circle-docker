## Docker

[![CircleCI](https://circleci.com/gh/wk-j/circle-docker.svg?style=svg)](https://circleci.com/gh/wk-j/circle-docker)

```bash
dotnet cake -target=Publish
docker-compose build
docker-compose up

open http://localhost/api/values
```