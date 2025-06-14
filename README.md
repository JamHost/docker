# docker
**You need to be logged in and root for this**
Clear the cache:
```
docker image prune -a && docker builder prune --all
```
Build image
```
docker build -f <FILE> -t <USERNAME>/<IMAGE_NAME>:<VERSION> .
```
And then push it
```
docker push <USERNAME>/<IMAGE_NAME>:<VERSION>
```