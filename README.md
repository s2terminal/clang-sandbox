# Docker C Sandbox

```
$ docker build . -t myclang
$ docker run --name myclang --interactive --tty --rm --volume $(pwd):/app myclang bash
```

```
# gcc main.c -o main
# ./main
```
