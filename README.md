# hippo-dockerizer
Dockerize an existing Hippo Project with 1 command

## Run this inside a Hippo Project

```bash
$ docker run --mount type=bind,source=$(pwd),target=/home/myhippoproject bcanvural/hippo-dockerizer:v1
```

Then run deploy2tomcat.sh

```bash
$ ./deploy2tomcat.sh
```


Source code of image can be found at https://github.com/bcanvural/hippo-dockerizer-source
