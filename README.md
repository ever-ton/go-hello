# go-hello 

Simple function in Golang using docker to create an small image.

## Docker build

```
docker build -t yourLogin/go-rocks . 
```

## Docker Run
```
docker run  yourLogin/go-rocks
```

## Push to Docker Hub
```
docker login

docker push yourLogin/go-rocks
