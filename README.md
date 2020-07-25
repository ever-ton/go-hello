# go-hello 

Simple Hellow Word in Golang using docker to create an small image.

## Docker build

```
docker build -t yourLogin/go-hello . 
```

## Docker Run
```
docker run  yourLogin/go-hello
```

## Push to Docker Hub
```
docker login

docker push yourLogin/go-hello
