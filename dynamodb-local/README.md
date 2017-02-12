# What's in this image

This image contains the latest AWS dynamodb-local version. It's also optimized so the image size is kept as small as possible.
If you find that the dynamo version is outdated, just send a PR to this repo so docker hub will trigger a new build automatically

### start a dynamodb instance

```
docker run -it --name dynamo marcosnils/dynamodb-local
```

This image will expose port 8000 by default. That's the port you will need to use as an endpoint for your local dynamo apps


### What other options can I use with dynamo?

```
docker run marcosnils/dynamodb-local
```

This command will print all the possible options you may use as a `[COMMAND]` argument for your docker image


