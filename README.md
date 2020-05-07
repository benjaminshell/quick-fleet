# quick-fleet
Quickly spin up Docker instances to run Kolide Fleet

Note: It was intentional to put a symlink in the directory pointing to the parent. This is to provide easy compatibility with another project until another method is determined.


## Start instances
cd quick-fleet

docker-compose up

## Start instances detached
docker-compose up -d

## Remove instances
docker-compose down

## Remove instances and volumes
docker-compose down --volume
