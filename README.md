
## Build docker image
You only need to do this once and in the future if there are changes to the Gemfile.

```
    cd _docker && docker build . -t github-page-docker
```
Use `--no-cache` to build without using cache.