# run-pi-in-container

# Command

``` shell
# build image locally
docker build                    \
--tag pi-coding-agent:latest    \
.
```

``` shell
docker compose run --rm pi

# Ctrl + P, then Ctrl + Q
# exit the container without killing it.
```

``` shell
# after task
# Clean up work directory
git clean \
--force \
-d
```