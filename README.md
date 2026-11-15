# run-pi-in-container

# Command


``` shell
# build image locally
DATE=$(date +%F)

time docker build                   \
--no-cache                          \
--tag "run-pi-in-container:${DATE}" \
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