# quick-fleet
Quickly spin up Docker instances to run Kolide Fleet

# A few notes
- It takes a few minutes for fleet to make necessary changes to the database on first start. 
- It was intentional to put a symlink in the directory pointing to the parent. This is to provide easy compatibility with another project until another method is determined.
- A standard cert for HTTPS has been included. It is best practice to use/generate your own.


### Start instances
```sh
cd quick-fleet
docker-compose up -d
```

### Remove instances
```sh
docker-compose down
```

### Remove instances and volumes
```sh
docker-compose down --volume
```