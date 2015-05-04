# Dockerfiles

## App Lists

1. [firefox](https://github.com/hangyan/Dockerfiles/blob/master/firefox/Dockerfile)


## Notes For GUI Apps

1. Run `xhost +` on your host os
2. add `-e DISPlAY` and `--net=host` when you use `docker run`,eg:

   `docker run --net=host -e DISPLAY firefox`

