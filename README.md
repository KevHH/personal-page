
## Build docker image
You only need to do this once and in the future if there are changes to the Gemfile.

```
    docker build . -t github-page-docker -f _docker/Dockerfile
```
Use `--no-cache` to build without using cache.