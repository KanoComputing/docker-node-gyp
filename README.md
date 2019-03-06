# kanocomputing/node-gyp

Set of docker images to build native node modules

## Building

Move to the desired nodejs version directory then run:

```
docker build . -t kanocomputing/node-gyp:<version>
```

## Pushing

Once you built a new image (for a new node version for example)

```
docker push kanocomputing/node-gyp:<version>
```
