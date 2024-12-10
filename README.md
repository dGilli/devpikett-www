# devpikett-www

build:
```shell
docker build -t dgilli/generic-httpd httpd)

```

run:
```shell
docker run -itp 8000:80 -v "$PWD":/usr/local/apache2/htdocs/ dgilli/generic-httpd
```

