# Expo with Node 14

Simple helping container with pre-installed expo

## Updating
 After version update or other maintenance you need to build and image and push to hub.

```sh
# Building new image
docker build -t syndicatedb/expo . 

# Tagging
docker tag syndicatedb/expo syndicatedb/expo:latest
docker tag syndicatedb/expo syndicatedb/expo:5 # Expo version

# Pushing to hub
docker push syndicatedb/expo:5
docker push syndicatedb/expo:latest
```

## Images
* syndicatedb/expo:5 (syndicatedb/expo:latest)
* syndicatedb/expo:4